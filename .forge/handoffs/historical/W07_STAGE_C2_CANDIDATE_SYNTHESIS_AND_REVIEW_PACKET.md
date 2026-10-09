# KIRION FORGE — LUCIEN / W07 STAGE C2
## K5 evidence-bounded candidate synthesis + K6 independent-review packet preparation ONLY

**STATUS: MAINTAINER-AUTHORIZED FOR ONE C2 K5–K6 WORKER CHECKPOINT, NOT K7.**
**Run ID:** `W07_DIALOGS_OVERLAYS_FOCUS`.
**Branch:** `forge/w07-dialogs-overlays-focus-intelligence`, no alternate/new branch.
**Canonical accepted `main`:** `61987e3de3ff85426e293dd15e596200ad272103`, immutable; do not merge.
**Accepted C1 K4 exact checkpoint:** `977a6ebfd1b7e6a54ad04f142f1a18b287887cad` — independent Maintainer acceptance and issue #24 CLOSED/completed, comment `6076535555`.
**EXACT C2 GOVERNANCE START SHA:** recorded in C2 tracking issue #25 after governance commit; worker MUST check branch equality before mutating.
**Authority:** Kirch human Technical Authority; KIRION FORGE Maintainer stage-gate authority; FORGE-0006, W01 K0–K7 and record schemas. AI-assisted worker may propose but never self-accept/promote.

### Task objective and source boundary
Convert accepted K4 comparisons into **reviewable, context-specific** possible reusable frontend knowledge concerning dialogs, overlays, popovers, tooltips, disclosure, focus and dismiss controls, **only where evidence is sufficient**. Do not create arbitrary guidelines to satisfy a count. Allowed inputs limited to:
- immutable accepted 36 W07 K3 `observations/W07-O01..O36.json` and `OBSERVATION_INDEX.md`;
- independently accepted K4 `CROSS_SOURCE_COMPARISON.md`, `CONTRADICTIONS_AND_CONTEXT.md`, `UNRESOLVED.md`;
- original Stage A `SOURCE_ID_MAP.md`, `SOURCE_QUALIFICATION.md`, accepted source registry and license/rights metadata;
- W01 schema/lifecycle policies, `.forge/knowledge/schemas/pattern-record.schema.json`, `anti-pattern-record.schema.json`, FORGE-0006 and W02–W06 accepted-knowledge precedent **read-only**.
**No new internet browsing, independent fresh source extraction, imported hooks, source registry writes or external code**. The C1 contradiction categories are analytic labels, not a replacement for records or the candidate schema.

### Correct authority / provenance / tests
- WCAG 2.2 normative *only within relevant criteria and exact conditions/exceptions*; not blanket mandate to use a modal.
- WHATWG native HTML spec is normative to platform algorithm, but living/unpinned and not proof of target browser.
- WAI APG informative; tooltip explicitly work-in-progress/non-consensus and standalone nonmodal dialog page unqualified (404). W3C APG/WCAG are not independent normative votes.
- USWDS/Primer Product are contextual design-system references, unpinned; docs reuse rights UNKNOWN -> metadata/source-linked paraphrase only.
- Primer Product + pinned `primer/react@7f5303d803986887187d86dcebaeda22a4dc6823` are NOT independent publishers. Pinned Tooltip v1 `@deprecated` cannot imply new/current product Tooltip deprecated; pinned source does not demonstrate runtime.
- USWDS 14 publisher tests 13 passed/1 conditional under older WCAG 2.1 AA are neither Kirion tests nor WCAG 2.2 conformance. Primer pinned `W07-O33` is `OTHER` / authored TEST_INTENT, **not** `TEST_RESULT`. No app, keyboard, AT, browser, zoom or mobile tests RUN.
- K4 `DIRECT_CONFLICT=0` only *confirmed within this corpus*, not evidence for universal harmony.

### Candidate selection (hard caps, NOT quotas)
May create **ZERO to THREE** `W07-P01.json`…`W07-P03.json` contextual pattern candidates under `candidates/patterns/`, and **ZERO to TWO** `W07-A01.json`…`W07-A02.json` contextual anti-pattern candidates under `candidates/anti-patterns/`. No skipped/duplicate IDs in created subset; 0 is valid when evidence insufficient. Every created record:
1. Validates against its exact repository Draft 2020-12 JSON schema: required/allowed keys, enums/types/conditionals, arrays/uniqueness, status `CANDIDATE`, never `ACCEPTED`.
2. Names a concrete recurring problem/structure/mechanism and user/task context; states limited, falsifiable rationale and evidence quality without universal design-system prescriptions or project-specific assumptions.
3. Carries valid registered source IDs, **actual W07 observation IDs** (not just general citations), cross-source K4 comparison references in explanatory text, confidence and recency. Confidence reflects evidence strength, not tests passed.
4. Explicitly describes tradeoffs, applicability and **non-applicability**; grounded counterexamples (for anti-patterns, legitimate contexts and usability/accessibility/performance/maintainability consequences).
5. Prevents claiming measured mobile/AT/focus conformance or guaranteeing particular native/React implementation; no UX experiment or target app tested.
6. Does not cite a single version-bound vendor implementation as a universally reusable design law. Candidate can use multiple authority types where the narrower hypothesis is justified; different source types are not equally authoritative.
7. Does not silently resolve forced-action Escape conflicts, tooltip WIP, missing subtitle aria-describedby target, imported focus hooks, source-version mismatches or rights gaps.
8. Existing prior W02–W06 accepted/candidate knowledge immutable, including deferred W02-P02/W03-A01.

Suggested **hypothesis areas only (never mandatory)**:
- Modal vs inline/persistent-page chooser with interruption and task complexity boundaries.
- Keyboard-operable dialog lifecycle with truthful naming/focus/dismiss/return-focus under *applicable* standards, alternatives and forced-action exceptions.
- Tooltip vs disclosure/popover selection with discoverability and version caveats.
- Harm mechanism of visually modal surfaces incorrectly claiming modality or losing keyboard exit.
- Harm mechanism of critical information hidden in unsupported tooltip-only interactions.
These are possibilities to *challenge* against C1; do not manufacture candidate if independent evidence and counterexamples are weak.

### K6 review packet — mandatory even with zero candidates
Create `.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/review/MAINTAINER_REVIEW_PACKET.md` for **independent future K7 Maintainer**, containing:
- immutable Stage A/B/C1 lineage + exact C2 input, branch and canonical main;
- 36-observation/source-family registry mapping, C1 20 comparison categories, 0 confirmed same-context conflicts and material unresolved disputes;
- exact generated candidate IDs, status `CANDIDATE`, evidence linkage, provenance/rights, recency and model fit;
- candidate-by-candidate review matrix: problem, mechanism, applicability, exceptions, concrete evidence IDs, confidence, counterevidence and reasons to accept/rework/reject/defer; **not** a self-approval;
- explicitly call out where the evidence cannot justify a candidate, and provide grounded *no-candidate* disposition if necessary;
- safeguards for legacy W02–W06 knowledge/deferred candidates, version pinning, test-intent vs publisher tests, actual NOT RUN;
- independent reviewer acceptance criteria and specific questions for K7; no fabricated K7 sign-off.

### C2 allowed writes ONLY (same repository / branch)
New bounded candidate JSON files (at most 5 total) in:
```
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/candidates/patterns/W07-P01.json..W07-P03.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/candidates/anti-patterns/W07-A01.json..W07-A02.json
```
and create `.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/review/MAINTAINER_REVIEW_PACKET.md`.
Optionally append **only** well-grounded residual questions to `UNRESOLVED.md`; append C2 checkpoint to `checkpoints/CHECKPOINT_LEDGER.md`, preserving old contents as exact prefixes. Do not create a generic or extra candidate index unless separately authorized.
**No writes to** 36 observations, observation index, C1 comparison/contradiction files, Stage A files, registries, schemas, source code/assets, earlier W02–W06 knowledge, SSOT, work ledger, handoffs, third-party repositories or `main`. No package/framework adoption, app/backend, PR or tests-executed fiction.

### Worker checkpoints and return
1. Verify live branch exactly equals C2 SHA in issue #25, issue #24 independently CLOSED/completed, main unchanged, sole active handoff.
2. Validate owned changed paths and Git ancestry, all candidate IDs/status/schema and linked observation/source records, candidate K4 evidence/counterexamples, copy/right boundaries.
3. Verify all prior source/observation/index/C1 evidence, previous W02–W06 and governance blobs identical, UNRESOLVED and checkpoint historical text exact prefixes.
4. Report explicit `RUN` vs `NOT RUN`; no external Draft 2020-12 validator PASS unless really executed. No browser/application tests authorized.
5. Commit to same branch using non-force SHA-safe expected-head conditions; no tracked SHA self-reference. Report exact final worker commit and `READY_FOR_STAGE_REVIEW`, `REWORK_REQUIRED` or `BLOCKED`, **STOP**.

**Independent C2 review of the exact worker checkpoint is REQUIRED before K7 consideration. K7 ACCEPT/REJECT/DEFER/PROMOTE remains MAINTAINER ONLY.** No automatic Stage C closure or main merge.
