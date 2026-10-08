# KIRION FORGE: MAINTAINER — W07 STAGE A HANDOFF
# DIALOGS / OVERLAYS / FOCUS-MANAGEMENT INTELLIGENCE
# A = K0–K2: REQUEST, SOURCE DISCOVERY, QUALIFICATION ONLY

## Status and authority

**W07 Stage A: AUTHORIZED — CONTROLLED SOURCE QUALIFICATION**

**W07 Stages B and C: BLOCKED / MAINTAINER RELEASE REQUIRED**

**W07 K7: MAINTAINER ONLY**

**Frontend application implementation: BLOCKED**

Authority: explicit human approval to begin the next bounded lane, accepted `FORGE-0006` workload isolation, and governing `AGENTS.md`, `.forge/AUTHORITY.md`, `.forge/SSOT_CURRENT.md`, `.forge/protocols/KNOWLEDGE_ACQUISITION.md`, and `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`.

Role: **KIRION FORGE: SOURCE QUALIFICATION WORKER (STAGE A)**.

Stage A is an evidence-qualification job, not a production/frontend Code Writer job.

## 0. Exact source and branch

Repository:

```text
Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE
```

Canonical accepted source before W07:

```text
main@61987e3de3ff85426e293dd15e596200ad272103
```

Authorized W07 working branch ONLY:

```text
forge/w07-dialogs-overlays-focus-intelligence
```

The stage-A **governance head SHA** is the exact SHA published on the W07 GitHub issue immediately after Maintainer finishes branch setup. The worker MUST read that SHA, independently resolve the live branch, and require equality before any writes. No guessed/future/self-referential SHA may be used.

Verify `main` remains the exact accepted source above, branch is descended from it with 0 behind, no contradictory active handoff exists, and G01/FORGE-0006 policy is merged in `main`.

If one fails: `SOURCE_DRIFT`; STOP; report. No rebasing, resets or repair branches.

## 1. Mandatory read order

1. `AGENTS.md`
2. `.forge/AUTHORITY.md`
3. `.forge/SSOT_CURRENT.md`
4. `.forge/EVIDENCE.md`
5. `.forge/CLASSIFICATION.md`
6. `.forge/DECISIONS.md`
7. `.forge/VALIDATION.md`
8. `.forge/WORK_LEDGER.md`
9. `.forge/ACCEPTANCE.md`
10. `.forge/knowledge/README.md`
11. `.forge/knowledge/SOURCE_TAXONOMY.md`
12. `.forge/knowledge/SOURCE_AUTHORITY.md`
13. `.forge/knowledge/KNOWLEDGE_SCHEMA.md`
14. `.forge/knowledge/LICENSING_AND_PROVENANCE.md`
15. `.forge/knowledge/DESIGN_REFERENCE_POLICY.md`
16. `.forge/protocols/KNOWLEDGE_ACQUISITION.md`
17. `.forge/protocols/SOURCE_EVALUATION.md`
18. `.forge/protocols/KNOWLEDGE_PROMOTION.md`
19. `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`
20. `.forge/templates/KNOWLEDGE_CHECKPOINT_TEMPLATE.md`
21. this exact active W07 Stage A handoff
22. existing `.forge/knowledge/registry/sources.json`.

## 2. Human objective and research question

Teach Lucien how dialogs and layered interactions should preserve comprehensible context and operability, with emphasis on:

- modal vs non-modal dialog;
- native `dialog` / `popover` / ARIA dialog distinctions;
- overlays, popovers, tooltips, disclosure and menu distinctions;
- initial focus, focus containment, focus return, focus order, keyboard dismissal;
- background interaction/inertness and layering;
- accessible names/descriptions; state changes and announcements;
- Escape, outside-click and data-loss tradeoffs;
- destructive confirmation and dialog appropriateness;
- responsive dialog/sheet content and scrolling;
- multiple/nested overlays and uncertainty.

Research question:

> What evidence distinguishes valid dialog, overlay, tooltip, popover, and disclosure mechanisms, and what accessibility, focus, dismissal, and responsive constraints should shape their appropriate use?

**Stage A ONLY:** determine which pre-approved authoritative materials can supply evidence, with exact identities, version/recency, licenses, bounded paths, and limitations. Do not answer this question with findings or synthesize patterns yet.

## 3. Exactly six authorized logical source families

You may inspect relevant sub-pages within each family to qualify identity and evidence capability. Record broken/moved links and source limitations. Do not secretly swap in an independent seventh family. Never equate standards, tutorial advice, design-system conventions, and pinned source implementation.

### S1 — W3C WCAG 2.2

Canonical: `https://www.w3.org/TR/WCAG22/`

Class: `OFFICIAL_STANDARD`, primary normative within actual success criteria.

Relevant qualification anchors may include 1.3.1, 1.4.13, 2.1.1, 2.1.2, 2.4.3, 2.4.7, 2.4.11, 2.5.2 and 4.1.2 where actually applicable.

Reuse qualified registry identity `W02-S1` if exact source identity remains valid. Preserve success-criterion conformance levels and exceptions; WCAG is not a design-system prescription for every overlay.

### S2 — W3C WAI ARIA Authoring Practices Guide (APG)

Official family, non-normative implementation/accessibility guidance:

```text
https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/
https://www.w3.org/WAI/ARIA/apg/patterns/dialog/
https://www.w3.org/WAI/ARIA/apg/patterns/tooltip/
https://www.w3.org/WAI/ARIA/apg/patterns/disclosure/
```

Qualify what is current/accessible. A page missing, renamed, or redirecting MUST be recorded honestly; don't silently invent contents. APG pattern guidance must not be cited as WCAG normative text.

### S3 — WHATWG HTML Living Standard

Official HTML specification, normative only for relevant platform mechanisms:

```text
https://html.spec.whatwg.org/multipage/interactive-elements.html#the-dialog-element
https://html.spec.whatwg.org/multipage/popover.html
https://html.spec.whatwg.org/multipage/interaction.html#inert-subtrees
```

Qualify native `showModal()`, `show()`, `close()`, top layer, `popover`, inertness and light-dismiss references only as far as actually sourced. Living-standard currentness requires retrieval timestamp. **Native HTML API behavior ≠ implementation proof for an arbitrary product.**

### S4 — U.S. Web Design System (USWDS), modal family

Official design-system guidance:

```text
https://designsystem.digital.gov/components/modal/
```

Related official component accessibility/implementation pages if linked may be qualified within the same family. Do not infer a universal law from government-design-system choices.

### S5 — GitHub Primer product design guidance

Official design-system/reference family. Qualify the applicable reachable targets, such as:

```text
https://primer.style/product/components/dialog/
https://primer.style/product/components/tooltip/
https://primer.style/product/components/popover/
https://primer.style/product/components/overlay/
```

Record redirects, unavailable or stale pages. Live Primer docs may differ from the pinned source; do not silently treat them as version-equal.

### S6 — Pinned primer/react implementation

Repository: `primer/react`

**Exact immutable SHA:**

```text
7f5303d803986887187d86dcebaeda22a4dc6823
```

Relevant bounded paths verified to exist at handoff issuance:

```text
packages/react/src/Dialog/Dialog.tsx
packages/react/src/Dialog/Dialog.test.tsx
packages/react/src/Overlay/Overlay.tsx
packages/react/src/Tooltip/Tooltip.tsx
packages/react/src/Popover/Popover.tsx
```

Directly referenced utilities/tests may be included in the qualified bounded implementation surface only if necessary. Do not roam all components or mutate `primer/react`. Record implementation source identity at exact SHA, permitted file paths, copyright/license and limits. Tests read != tests executed.

## 4. Source classification and registry integrity

Stage A must build an **identity-aware source-ID map** from the existing registry:

- reuse `W02-S1` for WCAG 2.2 if identity unchanged;
- inspect existing W02–W06 IDs before deciding whether any other family legitimately reuses an existing entry;
- create new W07 source IDs only if the underlying qualified source target is materially distinct;
- do not duplicate broad Primer repository identities ambiguously; where the pinned component-family scope is distinct, explain why a separate scoped record is necessary;
- registry membership = source qualification only, NEVER knowledge acceptance.

Qualify exactly the six logical families as a controlled requested corpus. A family may be `BLOCKED`/`UNRESOLVED` if its identity, licensing or access cannot be verified. Do not manufacture qualified observations to fill a quota.

Preserve provider, URL, type, authority weight and reason, version/SHA or retrieval date, independent-source limits, license status and storage policy, recency, known caveats, claims supported and not supported. Do not store copied documentation, full source files, screenshots or design-system assets.

## 5. Strict owned output surface (Stage A only)

Create/update under:

```text
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/
  REQUEST.md
  SOURCE_DISCOVERY.md
  SOURCE_QUALIFICATION.md
  SOURCE_ID_MAP.md
  LICENSE_AND_RETRIEVAL.md
  UNRESOLVED.md
  checkpoints/CHECKPOINT_LEDGER.md
```

May modify only if needed for valid Stage A source qualification:

```text
.forge/knowledge/registry/sources.json
.forge/SSOT_CURRENT.md
.forge/WORK_LEDGER.md
```

Do NOT modify this active handoff, AGENTS, decisions, protocols, accepted record schemas, prior W02–W06 run files, README, or other paths. On schema incompatibility: `SCHEMA_BLOCK`; STOP and return to Maintainer. If no schema-compatible registry changes are needed, leave it unchanged.

Keep stages B/C uncreated. Do NOT create observation JSON, candidate JSON, comparison reports, failure-mode analysis, K6 review packet, or acceptance metadata.

## 6. Required Stage A artifacts

### REQUEST.md (K0)
Run ID `W07_DIALOGS_OVERLAYS_FOCUS`; source `main@61987e3de3ff85426e293dd15e596200ad272103`; branch, exact governance input SHA from issue; objective/question; allowed domains (`MODALS`, `OVERLAYS`, `FOCUS_MANAGEMENT`, `KEYBOARD_ACCESS`, `SEMANTIC_HTML`, `ACCESSIBILITY`, `INTERACTION`, `RESPONSIVE_DESIGN`); six-family corpus, constraints, non-goals, proposed later-stage caps, start timestamp, stop conditions.

### SOURCE_DISCOVERY.md (K1)
Canonical URL + actual retrieval/redirect status and scope for each family; do not extract generalized conclusions. Note materially unavailable targets and whether the approved family can still be qualified from other official pages.

### SOURCE_QUALIFICATION.md (K2)
For each family: identity, provider, source type/authority, independent-source contribution, exact claims that could be supported, limitations, normative/reference/implementation boundary, recency/version, license/storage.

### SOURCE_ID_MAP.md
Exact registry IDs reused and appended; ensure no duplicate IDs, duplicate ambiguous source identity, or invalid cross-links; include *unqualified* references separately.

### LICENSE_AND_RETRIEVAL.md
Retrieval dates, access restrictions, version pin, archive/storage/reuse restrictions and unresolved rights. No assumption that public content may be copied.

### UNRESOLVED.md
Open material questions, inaccessible material, likely contradiction surfaces, what Maintainer must decide before Stage B.

### checkpoints/CHECKPOINT_LEDGER.md
Stage A checkpoint per the accepted template, actual changed paths and executed checks. `READY_FOR_REVIEW` only; not `RELEASED` by worker. Output SHA is reported **after commit** in issue/return, never embedded as a fabricated self-reference.

## 7. Later-stage planning only — NOT release

Provisional W07 total observation range for later Stage B planning: target **24–36**, hard maximum **42**, spread across the six families with evidence-driven counts. Default B batch target **5–8** bounded observations per checkpoint. Those are planning limits, not authorization to create observations in Stage A or to fabricate any record.

Later Stage C may propose 0–3 pattern candidates and 0–2 anti-pattern candidates. **Stage C is blocked now** and these planning caps do not permit synthesis.

Possible future failure hypotheses (NOT ACCEPTED, NOT TO BE WRITTEN AS CANDIDATES IN A):

- visual modal without dialog semantics;
- interactive background despite declared modality;
- inconsistent initial/return focus;
- focus escaping modal context;
- tooltip used as sole required instructions;
- popover/tooltip/dialog semantic conflation;
- destructive light-dismiss without recovery;
- nested overlay focus conflict;
- mobile dialog content clipping.

No invented defect is acceptable without K3 evidence and K4 comparison.

## 8. Required Stage A validation

Record executed vs unexecuted honestly:

- live `main`, branch, expected governance SHA: PASS/FAIL with exact SHAs;
- ancestry, worker delta and owned changed paths: PASS/FAIL;
- prior accepted/deferred W02–W06 records: preserved; if practical verify SHA/blobs or compare diff and report exact method;
- source registry JSON parse: PASS/FAIL if changed;
- schema conformance: only PASS if actually validated against the accepted schema; JSON parse alone is insufficient;
- uniqueness of IDs, reuse/append linkage, license and source identity: record how checked;
- source qualification results: SOURCE INSPECTED or BLOCKED, not runtime PASS;
- runtime, browser, screen reader, keyboard, application build/typecheck/tests: NOT RUN / NOT APPLICABLE.

Do not execute or claim UI/runtime tests; qualification only.

## 9. Hard negative gates

Confirm:

```text
NO K3 observations
NO K4 comparisons
NO K5 pattern/anti-pattern candidates
NO K6 final acquisition review
NO K7 promotion
NO W07 Stage B/C execution
NO W08
NO frontend application
NO package.json or dependencies
NO React/Next/router/UI stack selection
NO adoption of Primer/USWDS or other component library
NO external repository mutation
NO seventh source family
NO bulk crawl
NO source/license bypass
NO cloned or conflicting registry source identities
NO prior knowledge modification
NO fabricated schema, test, browser, AT, focus or usability PASS
NO main merge
NO worker self-release
```

## 10. Stop / rework conditions

STOP and report if:
- exact `main` or governance SHA moved;
- gate/handoff conflicts with SSOT or FORGE-0006;
- source identities no longer grounded;
- licensing uncertainty makes intended storage unlawful;
- unapproved source substitution is required;
- registry schema cannot represent valid source;
- prior knowledge changed;
- work spills beyond Stage A;
- context compaction or missing evidence means source IDs/paths cannot be verified.

Prefer a checkpoint of verifiable progress and a bounded continuation report over improvised completion.

## 11. Mandatory worker return — then STOP

```text
KIRION FORGE — LUCIEN
W07 STAGE A / K0–K2 SOURCE QUALIFICATION REPORT

1. LIVE MAIN AND BRANCH VERIFICATION
2. GOVERNANCE INPUT SHA AND ANCESTRY
3. SOURCE FAMILIES S1–S6 AND RETRIEVAL STATE
4. QUALIFICATION / DISQUALIFICATION RESULTS
5. SOURCE IDENTITIES REUSED / ADDED
6. LICENSE / RECENCY / STORAGE BOUNDARIES
7. FILES CREATED
8. FILES MODIFIED
9. CHECKPOINT ARTIFACT
10. OBSERVATIONS CREATED (MUST BE 0)
11. CANDIDATES CREATED (MUST BE 0)
12. PRIOR KNOWLEDGE INTEGRITY
13. VALIDATION ACTUALLY EXECUTED
14. VALIDATION NOT RUN / NOT OBSERVED
15. CONTRADICTIONS AND UNRESOLVED ITEMS
16. COMMITS CREATED
17. EXACT FINAL BRANCH
18. EXACT FINAL SHA
19. WORKER RECOMMENDATION
```

Recommendation **exactly one**:

```text
READY_FOR_STAGE_REVIEW
REWORK_REQUIRED
BLOCKED
SOURCE_DRIFT
```

STOP. Maintainer alone reviews/release Stage A. No continuation to B without new exact-SHA authorization.


---

# HISTORICAL DISPOSITION — STAGE A

**Maintainer accepted and released source qualification only.**

Accepted worker checkpoint: `0e4340649fb71aef1ef00e46caa8433342bf697a`

Release recorded on GitHub issue #17, 2026-10-08.

This handoff is RETIRED / HISTORICAL. No Stage A rerun, K3 observation extraction, K4–K6 synthesis, or K7 promotion is authorized by this historical document.

Stage B1 must be governed separately by its own active handoff and exact-SHA input.
