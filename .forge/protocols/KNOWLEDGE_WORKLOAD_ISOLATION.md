# FORGE — KNOWLEDGE WORKLOAD ISOLATION & CHECKPOINT PROTOCOL

**Authority:** FORGE-0006, human-approved 2026-10-08.
**Applies to:** substantive Lucien knowledge-acquisition lanes beginning with W07, plus any later lane explicitly brought under this protocol.
**Does not replace:** W01 K0–K7, source authority, licensing, record schemas, current SSOT, or Maintainer acceptance law.

## Purpose and evidence boundary

Long source-acquisition runs risk context saturation, attribution errors, inconsistent later records, unsourced synthesis, and mistaken validation claims. Those are operating risks, not proof that every long session fails. This protocol manages them through bounded work and Git-persisted state. Session separation is a control, not a substitute for source inspection or independent review.

**Hard invariant:** conversation state or worker report is never the sole authority for resuming. Each restart uses live Git, exact SHA, completed artifact checks, and the applicable active handoff.

## Authority and roles

- Human Technical Authority owns objective, risk tolerance, and acceptance authority.
- Forge Maintainer defines the run, exact branch/SHA, allowed source families, task stages, caps, checkpoints, stage-release gates, and final acceptance. Only Maintainer may authorize scope expansion and K7.
- Source Qualification Worker executes only its K0–K2 bounded stage.
- Observation Worker executes only the authorized K3 batch(es).
- Comparison/Synthesis Worker executes only K4–K6 from verified observation records.
- Reviewer/Validator independently reviews evidence and validates the exact checkpoint. A worker's own summary is not independent validation.
- A single model may perform roles in distinct passes when necessary, but must explicitly change role and not skip gates.

## Stage topology

```text
Maintainer run authority and exact source
  → A: K0–K2 discovery, provenance, qualification
  → STAGE_A_CHECKPOINT / Maintainer release
  → B1..Bn: K3 observation batches
  → EACH BATCH_CHECKPOINT / source-link + scope checks
  → STAGE_B_CHECKPOINT / Maintainer release
  → C: K4–K6 comparison, contradictions, candidate synthesis, review packet
  → STAGE_C_CHECKPOINT / independent Maintainer exact-candidate review
  → K7 Maintainer-only acceptance/rejection/defer/promotion
```

No stage may infer release from its own successful write. A stage can be completed in one conversation for a genuinely small task only when the handoff allows it and provides a reason; separate sessions are the default for substantial lanes. Checkpoint and review requirements do not disappear if two stages share a session. No fixed number of conversations is an authority rule.

### Stage A: acquisition and source qualification (K0–K2)

Inputs: accepted run handoff, exact baseline, source families, provenance constraints.

Outputs: REQUEST, source qualification/registry changes as authorized, source-ID map, access/recency/license limits, source-family counts, A checkpoint.

No observation-to-pattern inference or candidate promotion. A missing/blocked source remains BLOCKED/UNKNOWN rather than silently replaced.

### Stage B: bounded extraction (K3)

Inputs: Maintainer-released Stage A SHA, source-ID map and approved source list, observation schema.

Default batch target: **5–8 observation records**, grouped by source or tightly related evidence context. The number is a scheduling heuristic, not a requirement to manufacture observations. Handoff may authorize fewer or more when necessary, with rationale and a hard total cap. One batch should have a single bounded source set and independently traceable evidence locations.

After each batch: persist observation JSON, update observation index/checkpoint, validate unique IDs and source references, record exact final commit SHA, and report NOT RUN for unexecuted checks. Never assume all observations are correct merely because JSON parses. Next batch must re-resolve the preceding checkpoint commit; fix-forward within the same branch when allowed.

### Stage C: comparison, synthesis, review packet (K4–K6)

Inputs: Maintainer-released Stage B SHA, complete validated observation index and source identities.

Outputs: cross-source comparison, contradictions, context boundaries, counterexamples, unresolved questions, 0..N bounded candidates linked to source/observation IDs, K6 packet, exact candidate SHA.

Candidate is `CANDIDATE` only; accepted_by/accepted_at remain empty as schema allows. No observation quotas or forced candidates. K6 is not K7.

## Required checkpoint artifact

At minimum a run must maintain `<RUN_ROOT>/checkpoints/CHECKPOINT_LEDGER.md` using `.forge/templates/KNOWLEDGE_CHECKPOINT_TEMPLATE.md`. The handoff may require a machine-readable summary additionally, but may not invent new accepted evidence statuses.

Every checkpoint records:

1. run / stage / batch ID, worker role, current disposition (DRAFT / READY_FOR_REVIEW / RELEASED / BLOCKED);
2. exact input baseline branch + SHA, exact output branch + SHA, and commit(s) created;
3. allowed files and actual changed files, source IDs and observation ID range;
4. source URLs/versions/SHAs; relevant limitations/rights;
5. checks actually run and results using `.forge/VALIDATION.md` labels;
6. checks NOT RUN / NOT OBSERVED / UNKNOWN;
7. contradictions, blockers, decisions required and safe continuation point;
8. Maintainer stage-release reference (issue/comment or committed decision) where required.

Checkpoint files are evidence pointers, not authority; a release is effective only when the Maintainer explicitly records it and the active handoff/SSOT permits downstream execution.

**Self-reference law:** A checkpoint cannot reliably cite its own commit SHA inside the same commit. Record the finalized commit SHA in the stage report or issue comment after commit; the next worker must resolve live Git and verify both the artifact and final commit. Do not fabricate self-referential checkpoint identity.

## Branch and checkpoint integrity

- Run has one Maintainer-issued working branch by default. Maintain bounded sequential checkpoint commits; do not create new branches per observation batch without authority.
- Before a new session: resolve canonical `main`, current run branch, exact checkpoint SHA, ancestry, stage gate, and all required files. Compare expected hashes/record IDs where the handoff requires it.
- If baseline moves, checkpoint is missing, a file has changed unexpectedly, a prior source is inaccessible, or a stage gate disagrees: `SOURCE_DRIFT` or `BLOCKED` as appropriate; STOP and return to Maintainer. Never silently rebase, fast-forward, overwrite, reconstruct from chat, or skip the gap.
- Separate immutable historical accepted knowledge from mutable run artifacts. Changes to past ACCEPTED/CANDIDATE statuses require a new acceptance decision; no silent mutation.
- Source mutation after a test/check resets evidence tied to the pre-mutation candidate. Report validations only for the exact SHA/version actually checked; verification metadata from old SHAs may remain historical, not current PASS.

## Workload-based split / continuation

Maintainer should split a lane if any of these raise material attribution or correctness risk:

- multiple heterogeneous sources with different normative/reference/implementation classes;
- more than one evidence family and roughly 20+ observations;
- high contradiction count or unresolved licensing/version drift;
- many record schemas/IDs/cross-links;
- large context consumed, imminent compaction, or degraded source recall;
- repeated attribution/linkage/checking failures.

Do not use a token-percentage threshold as fabricated objective quality science. Session warnings, confusion, inability to locate current source, missing exact SHA, or unsourced claims trigger immediate CHECKPOINT / STOP / RESTART unless safely recoverable within an explicitly bounded current stage.

Small, low-risk work may remain a single worker session when the handoff expressly permits and still records all stage outputs and checks. Do not make every minor edit a new conversation.

## Fresh-session boot contract

A new worker session receives, in order:

1. repo, role, run ID, stage/batch scope, accepted baseline `main@SHA`, target branch and **exact last released checkpoint SHA**;
2. AGENTS.md, current SSOT and governing accepted decisions;
3. active run handoff and this protocol;
4. checkpoint ledger, released stage packet, source-ID registry and authorized output paths;
5. explicit negative cases, validation contract, stop conditions, return structure.

Worker must read Git files rather than rely on pasted summaries, unless Maintainer explicitly authorizes portable source/excerpt mode with exact source identity and no repository mutations.

## Independent validation / stop conditions

Before release or final review, verify (where applicable):

- ancestry/branch SHA, scope diff and prior accepted-record integrity;
- qualified source identities, rights, dates/versions, authority weights;
- JSON parsing AND schema conformance separately (do not mark schema PASS on parse alone);
- unique source and observation IDs and all cross-reference links;
- raw observations bounded/descriptive; candidates evidence-linked/counterexample-aware;
- no K7 promotion, frontend stack/adoption, new dependencies, external mutation or out-of-corpus crawling;
- tests/browser/AT/runtime only if truly executed on the exact candidate.

If review detects incomplete batch, source contamination, invented evidence, or contradictions, return bounded REWORK. Do not roll back accepted knowledge or pre-authorize escalation by implication.

## Release and W07 boundary

Maintainer must issue an exact-SHA stage A handoff, accept/release Stage A, issue Stage B batch scopes, release Stage B, then authorize Stage C and finally independently review K6. A single governing W07 run handoff may predefine conditional stage boundaries, but release records remain required.

**This policy does not define, activate or execute W07.** Existing W07 INPUT REQUIRED / REVIEW and application IMPLEMENTATION BLOCKED remain in force until separate Maintainer handoff and gate change.
