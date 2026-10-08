# KIRION FORGE: MAINTAINER — W07 STAGE B1 / K3 BOUNDED OBSERVATION HANDOFF

## Authority and exact source

**W07 Stage A K0–K2:** ACCEPTED / checkpoint RELEASED for downstream input by Maintainer on GitHub issue #17.

**Exact accepted Stage A worker checkpoint:** `0e4340649fb71aef1ef00e46caa8433342bf697a`.

**Canonical accepted main:** `main@61987e3de3ff85426e293dd15e596200ad272103`.

**Working branch:** `forge/w07-dialogs-overlays-focus-intelligence` ONLY. Fix forward on this branch; do not create B1/repair branches.

**Stage B1 governance input SHA:** Must equal the SHA published in GitHub issue #17 after the Maintainer completes this handoff and SSOT/ledger updates. This issue SHA, not the historical Stage A checkpoint SHA, is the worker's exact mutating start point. Both SHAs must be independently re-resolved and their ancestry verified before writing.

**Stage B1:** AUTHORIZED — EXACTLY ONE K3 OBSERVATION BATCH.

**Other Stage B batches:** BLOCKED / CHECKPOINT REVIEW REQUIRED.

**Stage C K4–K6 and K7:** BLOCKED / separate Maintainer release; K7 Maintainer-only.

**Frontend application implementation:** BLOCKED.

Role: `KIRION FORGE: FRONTEND KNOWLEDGE OBSERVATION WORKER — STAGE B1`.

Read `AGENTS.md`, `.forge/AUTHORITY.md`, `SSOT_CURRENT.md`, `EVIDENCE.md`, `CLASSIFICATION.md`, `DECISIONS.md`, `VALIDATION.md`, `WORK_LEDGER.md`, `ACCEPTANCE.md`, W01 knowledge control plane, source-record and observation-record schemas, K0–K7 and workload-isolation protocols, completed Stage A files and checkpoint, issue #17 Maintainer Stage A ACCEPT comment, then this active B1 handoff.

## Controlled source scope

B1 uses **only S1, WCAG 2.2, registry ID `W02-S1`**, direct W3C Recommendation:

```text
https://www.w3.org/TR/WCAG22/
```

W07 Stage A qualified all six source families; **only WCAG is released for this first batch**. Do not access APG/WHATWG/USWDS/Primer to support B1 observations. Those remain qualified material for separately released future batches. Do not append sources or mutate the registry.

Exact normative criteria to inspect and attempt to extract (one record each where evidence is supported):

```text
W07-O01 — 2.1.1 Keyboard — Level A
W07-O02 — 2.1.2 No Keyboard Trap — Level A
W07-O03 — 2.4.3 Focus Order — Level A
W07-O04 — 2.4.7 Focus Visible — Level AA
W07-O05 — 2.4.11 Focus Not Obscured (Minimum) — Level AA
W07-O06 — 1.4.13 Content on Hover or Focus — Level AA
```

Verify the exact current W3C wording, anchors, conformance level, exceptions, conditions and version. If a specified observation is unsupported or out of scope, record a gap; do NOT fabricate it to reach six. Never conflate WCAG 2.4.11 with the AAA 2.4.12 Focus Not Obscured (Enhanced) criterion. Do not use `W07-S1` as a synthetic registry source. **One source family, maximum six new observations.**

## Evidence discipline

- Each raw observation represents one precisely anchored normative criterion's actual requirement/condition, not a product recommendation or application test.
- `source_id = W02-S1`; `evidence_kind = NORMATIVE_TEXT`; `status = OBSERVED`; domain from the accepted observation-record schema.
- Preserve relevant exception language and applicability, not blanket `all overlays must X` assertions.
- Capture `source_version_context`, exact source section URL, observation timestamp, bounded limitations and any uncertain wording.
- Normative WCAG text **does not independently prescribe** modal focus-trapping algorithms, initial focus placement, escape dismissal, return focus, `inert`, a drawer design, tooltip appearance, or use of Primer.
- No browser implementation, keyboard execution or accessibility conformance is established by reading the specification.
- Use no unauthorized seventh source, no copied bulk source content, no source images/screenshots.

## Owned files — no other mutation

May create:

```text
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O01.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O02.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O03.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O04.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O05.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O06.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/OBSERVATION_INDEX.md
```

May update ONLY:

```text
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/checkpoints/CHECKPOINT_LEDGER.md
```

Append a B1 checkpoint section. Preserve Stage A history and its accepted input identity without altering past results. Mark **B1 READY_FOR_REVIEW**, not self-RELEASED. Do NOT alter the Stage A snapshot's recorded facts.

Do not modify SSOT or WORK_LEDGER as a worker; Maintainer owns stage state. No modifications to registry, prior accepted knowledge records, `AGENTS.md`, schemas, protocols, source qualification files, old handoffs, or `README.md`.

## Validation required before return

- Reverify canonical main SHA, active branch governance head, exact released Stage A checkpoint as ancestor, and source (W02-S1) registry identity.
- Confirm only authorized B1 paths changed relative to B1 governance input.
- JSON parse new observations and validate individually against accepted `.forge/knowledge/schemas/observation-record.schema.json`; distinguish parse, custom structure checks and dedicated JSON Schema engine if NOT RUN.
- Check all IDs unique, `W07-O01..06` only, `source_id = W02-S1`, all `OBSERVED` and evidence anchors present.
- Independently recheck source-text attribution and WCAG conformance level/exception for every record actually produced.
- Ensure no previous knowledge/registry/qualification files altered by this B1 worker delta.
- Record actual tests and missing tests. No application build, runtime, keyboard, browser, AT, mobile or usability results may be claimed.
- If source drift, wrong criteria, apparent schema incompatibility, access failure, or context exhaustion makes reliable extraction impossible: STOP; persist only trustworthy checkpoint progress, report precise blocker, no improvised source substitution.

## Hard negatives

```text
NO seventh source family
NO W07 Stage B2 onward
NO Stage C (K4 comparisons, K5 candidates, K6 packet)
NO K7 acceptance/promotion
NO source registry change
NO accepted W02–W06 record change
NO Stage A result mutation
NO changes to SSOT/ledger by B1 worker
NO framework/component-library adoption
NO frontend application/dependencies/package.json
NO runtime/browser/AT/test PASS fabrication
NO main merge or additional branch
NO worker self-release
```

## Return contract then STOP

```text
KIRION FORGE — LUCIEN
W07 STAGE B1 / WCAG K3 OBSERVATION CHECKPOINT REPORT

1. LIVE MAIN AND BRANCH HEAD
2. RELEASED STAGE A CHECKPOINT
3. EXACT B1 GOVERNANCE INPUT SHA
4. SOURCE ID / WCAG IDENTITY
5. WCAG CRITERIA INSPECTED AND LEVELS/EXCEPTIONS
6. OBSERVATION IDS CREATED (0–6) AND EVIDENCE ANCHORS
7. OBSERVATION INDEX SUMMARY
8. CHECKPOINT LEDGER UPDATE
9. FILES CREATED AND MODIFIED
10. UNIQUE IDs / SOURCE REFERENCES / SCHEMA CHECKS
11. NORMATIVE SCOPE / OVERGENERALIZATION NEGATIVES
12. PRIOR KNOWLEDGE AND STAGE A INTEGRITY
13. VALIDATION ACTUALLY EXECUTED
14. VALIDATION NOT EXECUTED / NOT APPLICABLE
15. BLOCKERS / UNRESOLVED
16. COMMITS CREATED
17. FINAL BRANCH
18. EXACT FINAL SHA
19. WORKER RECOMMENDATION
```

Worker recommendation exactly one: `READY_FOR_STAGE_REVIEW`, `REWORK_REQUIRED`, `BLOCKED`, `SOURCE_DRIFT`.

Then STOP. Only Maintainer may review/release B1 or issue B2. **No B2 permission is implied by B1 completion.**
