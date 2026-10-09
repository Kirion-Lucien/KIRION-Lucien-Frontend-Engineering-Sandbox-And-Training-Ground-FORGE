# KIRION FORGE — LUCIEN COMPARISON WORKER / STAGE C1

## W07 C1 — K4 CROSS-SOURCE COMPARISON ONLY

**STATUS: AUTHORIZED BY MAINTAINER FOR EXACTLY ONE K4 COMPARISON CHECKPOINT; NO K5/K6/K7.**
**Run:** `W07_DIALOGS_OVERLAYS_FOCUS`.
**Canonical main:** `61987e3de3ff85426e293dd15e596200ad272103`, must stay unchanged.
**Existing worker branch ONLY:** `forge/w07-dialogs-overlays-focus-intelligence`.
**Stage B accepted & formally CLOSED at exact B6 worker SHA:** `be19e287e14e31483392fb467ede90ba6f0a04b8`; issue #23 independent Maintainer acceptance+Stage B closure comment `6076211658`.
**EXACT C1 governance mutating START SHA:** obtain from C1 tracking issue #24 after this governance commit; do not infer from B6 SHA.
**Governing:** FORGE-0006 K0–K7, source registry, current SSOT/ledger, observation schema, accepted qualification materials, K4-only handoff.

### Preflight STOP conditions
Before writing, verify the exact live `main` and existing branch equal the respective pinned values above and new SHA in issue #24, Stage B close issue #23 CLOSED/completed, all 36 committed `W07-O01..O36.json` present/unchanged, all six source IDs valid, this is sole active executable handoff. Re-read the accepted Stage A qualification and limitations. If drift/contradiction exists, STOP, report SOURCE_DRIFT or BLOCKED. No alternate/validation branches.

### Authorized source set — locked, no new extraction
Use **only** the 36 accepted K3 observations, `OBSERVATION_INDEX.md`, `SOURCE_QUALIFICATION.md`, `SOURCE_ID_MAP.md`, `UNRESOLVED.md` and the accepted registry. No new K3 observations, source registry changes, external source reads or copying source docs/code. Logical source families:
1. WCAG 2.2 `W02-S1`, O01–O06: normative accessibility criteria with their actual conditions/exceptions, not general dialog design prescription.
2. WHATWG HTML `W07-S3`, O07–O12: native HTML dialog, popover, inert and algorithms, living/unpinned; normative HTML platform scope, **not** proof of tested browsers.
3. WAI-ARIA APG `W07-S2`, O13–O18: informative W3C examples, standalone non-modal URL 404, tooltip WIP/no consensus.
4. USWDS Modal `W07-S4`, O19–O24: reference design-system guidance; publisher component accessibility checklist conditional; **not Kirion-executed tests**.
5. Primer PRODUCT docs `W07-S5`, O25–O30: unpinned living Primer design guidance/props with unknown documentation reuse rights.
6. Primer React pinned `W07-S6`, O31–O36: primary implementation, fixed commit `7f5303d803986887187d86dcebaeda22a4dc6823`, authored test-intent `OTHER` not `TEST_RESULT`; deprecated Tooltip v1 only for this pin.

**Source independence caveats:** WCAG and WAI APG share W3C provenance but distinct normative authority; Primer product and pinned Primer React are same publisher and NOT two independent correctness votes; USWDS is separate design-system guidance, not a standard; WHATWG HTML normative scope and WCAG conformance normative scope are distinct. No unverified equivalence between pinned Primer code and live docs.

### K4 analysis scope (all observation IDs must appear in a traceable coverage map)
Prepare a source-by-source, context-bounded matrix and narrative across:
A. Modal vs nonmodal dialogs, native dialog vs design-system dialog, and ordinary page/alert/disclosure alternatives.
B. Modality, top layer, inertness, focus containment, starting focus, return-focus, accessible name and optional description; distinguish spec intent, guidance, library implementation, and tested behavior.
C. Escape/backdrop/outside-click/light-dismiss versus forced-action/acknowledgment, reversible choice vs consequential action; avoid universal close/dismiss laws.
D. Tooltip vs popover vs disclosure: roles, discoverability, hover/focus, keyboard, conditional content and risks; preserve APG tooltip WIP and pinned Tooltip v1 deprecation without conflating versions.
E. Mobile/responsive/scrolling/complex content, nested overlays, anchor positioning, viewport and visual/DOM ordering.
F. Source authority, source recency/rights, positive and negative evidence, counterexamples, meaningful limits, and **unknown runtime/browser/AT**.
G. Authored test assertions vs publisher-reported test results vs Kirion tests NOT RUN; no accidental PASS or conformance claims.
H. Include an explicit O01–O36 *coverage matrix*, source ID, supported comparison dimension, and whether statements truly agree, diverge, or cannot be compared due to scope/version; cite exact record IDs, avoid invented links.

Disagreement categories: `DIRECT_CONFLICT` (same context + genuinely incompatible claims), `CONTEXTUAL_TRADEOFF`, `SOURCE_AUTHORITY_SPLIT`, `VERSION_MISMATCH`, `EVIDENCE_GAP`, `NOT_COMPARABLE`. These are analysis labels, not new JSON schema enum values. Preserve competing evidence; do not silently resolve. Never infer W3C WCAG requires a specific component, infer measured focus from `useFocusTrap` import, call test intent passed, or assume live Primer and pinned source identical.

### Outputs authorized THIS C1 worker pass ONLY
Create:
```
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/CROSS_SOURCE_COMPARISON.md
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/CONTRADICTIONS_AND_CONTEXT.md
```
Append only:
```
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/UNRESOLVED.md
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/checkpoints/CHECKPOINT_LEDGER.md
```
The new comparison must include **all 36 IDs**, accurate source identity, contextual alternatives, unresolved disputes, and cross-source evidence; the contradiction register must explicitly distinguish real conflict versus difference of scope. Preserve prior `UNRESOLVED.md` and checkpoint as byte-exact prefixes.

**Forbidden this stage:** modifying O01–O36/OBSERVATION_INDEX, Stage A artifacts, registry, schemas, previous W02–W06 knowledge, SSOT/ledger/handoffs, W07 candidates/patterns/anti-patterns or review packet; adding new K3 observations; external repos writes, framework or frontend app code/packages; K5 candidate generation, K6 packet, K7 promotion, PR/main merge or assigning test PASS to unexecuted tests. Candidate budget of later C2 only: provisional **0–3 patterns and 0–2 anti-patterns**, evidence-gated and not a quota; C1 cannot create any.

### C1 checkpoint requirements
Record input branch SHA from #24, exact observed branch output commit SHA after write (no in-commit self-reference), changed paths and diff check, 36-record mapping, all source/citation links/versions/rights caveats, contradictions and unresolved points, exact prior-prefix comparisons, protected blob invariance, actual validation vs NOT RUN, and why 0 candidates were created in C1. Return `READY_FOR_STAGE_REVIEW`, `REWORK_REQUIRED`, `BLOCKED`, or `SOURCE_DRIFT`; **STOP for independent Maintainer C1 review**. C2 K5–K6 requires its own exact SHA handoff and tracking issue; not automatically authorized.

**No frontend implementation or main promotion authorized.**
