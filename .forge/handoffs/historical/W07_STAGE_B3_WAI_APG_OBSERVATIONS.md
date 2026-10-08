# KIRION FORGE: MAINTAINER — W07 STAGE B3 / K3 WAI-ARIA APG OBSERVATIONS
# MODAL DIALOG / TOOLTIP (WIP) / DISCLOSURE — GUIDANCE-ONLY BATCH

## Exact authority

**Canonical accepted main:** `main@61987e3de3ff85426e293dd15e596200ad272103`.

**Working branch ONLY:** `forge/w07-dialogs-overlays-focus-intelligence`. No new/repair branch, rebase, main merge.

**Accepted Stage A:** `0e4340649fb71aef1ef00e46caa8433342bf697a`, issue #17.

**Accepted B1:** `53084dd7c8f812732fc556873c3d7753c3aa1c3b`, issue #18.

**Accepted B2:** `791910cb0f623de36edfb301afbe6e7586ced214`, issue #19, independent Maintainer checkpoint release.

**B3 governing exact mutating starting SHA:** the new **B3 governance head** that Maintainer will publish on issues #19 and #20 after committing this handoff and SSOT/ledger. Worker must resolve the live branch and require equality with that exact SHA before writing. B2 accepted worker SHA must be a verified ancestor. Do not substitute B2 checkpoint for the B3 governance HEAD.

**Stage B3:** AUTHORIZED — exactly ONE K3 source-bounded APG batch, up to six records.

**B4 onward:** BLOCKED until independent B3 checkpoint review and a new exact-SHA release.

**Stage C K4–K6:** BLOCKED. **K7:** MAINTAINER ONLY. **Frontend application:** BLOCKED.

Role: `KIRION FORGE: FRONTEND KNOWLEDGE OBSERVATION WORKER — STAGE B3`.

Authority: `FORGE-0006`, `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`, accepted Stage A/B1/B2 release records and this handoff.

## Required reads

Read `AGENTS.md` and all governing Forge files per mandatory order, `.forge/SSOT_CURRENT.md`, knowledge schemas and acquisition/source/promotions protocols, `FORGE-0006`, Stage A qualification/source map, all prior W07 observations, index/checkpoint, issue #17/#18/#19 Maintainer acceptance/release decisions, then this exact B3 handoff. If exact branch SHA, accepted B2 ancestry, source qualification or current SSOT disagree, return `SOURCE_DRIFT` and STOP.

## ONE source family only — S2 WAI ARIA APG

**Registry source ID `W07-S2`**. Source type `ACCESSIBILITY_REFERENCE`; authority `OFFICIAL_REFERENCE`. This is W3C/WAI **ARIA Authoring Practices Guide explanatory design/implementation guidance**, NOT WCAG 2.2 normative success criteria and NOT the WHATWG HTML Living Standard.

Only qualified official APG pages:

```text
https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/
https://www.w3.org/WAI/ARIA/apg/patterns/tooltip/
https://www.w3.org/WAI/ARIA/apg/patterns/disclosure/
```

The previously requested standalone `https://www.w3.org/WAI/ARIA/apg/patterns/dialog/` was 404 at Stage A. DO NOT reconstruct a nonexistent non-modal pattern page, follow unrelated articles, or infer consensus non-modal guidance from that URL. The Tooltip APG page itself explicitly says **work in progress / no task force consensus**; never elevate it to stable consensus or normative law, even if accessible.

Use no WCAG/WHATWG/USWDS/Primer/MDN/other independent family to substantiate B3 records. Reading *already committed* B1/B2 for integrity checks is permitted but not K4 comparison.

Revalidate reachability, documented APG status, original advice and caveats at extraction time. Live pages unpinned: log actual retrieval timestamp and do not invent version SHA. Source storage policy for `W07-S2`: metadata only; store original bounded paraphrases with exact URLs, no page dumps.

## Planned evidence targets — 0 to 6 bounded records

These are research targets, NOT conclusions. Create only supported records.

```text
W07-O13 — APG modal dialog roles, accessible naming, aria-modal and conditions for marking something modal (genuine outside-content inertness, styling).
W07-O14 — APG modal dialog Tab/Shift+Tab containment, focus entry and Escape within pattern's keyboard-interaction guidance.
W07-O15 — APG context-dependent initial focus placement, long semantic content, viewport scrolling and least-destructive action countercontexts.
W07-O16 — APG focus return on close with documented exceptions and close-button recommendation.
W07-O17 — APG Tooltip work-in-progress/no-consensus status, trigger description semantics and non-interactive/focus constraints; explicit low-authority applicability.
W07-O18 — APG Disclosure show/hide mechanism, button aria-expanded/aria-controls guidance and documented keyboard operation.
```

Do not make O13–O16 all repetitions of one sentence; preserve distinct sourced mechanisms/constraints. If any target cannot be grounded, document the gap and omit record. All produced records:

- unique IDs only `W07-O13`…`W07-O18`;
- `source_id: "W07-S2"`;
- `status: "OBSERVED"`;
- `evidence_kind: "DOCUMENTATION_STATEMENT"` (**not** `NORMATIVE_TEXT`);
- selected domain from accepted observation schema (MODALS / FOCUS_MANAGEMENT / OVERLAYS / INTERACTION / KEYBOARD_ACCESS / ACCESSIBILITY);
- bounded observed_behavior descriptive, not a recommendation claimed as Forge law;
- exact official APG evidence URL, page status/limitation, observed_at, source version context and contextual counterexamples;
- tooltip uncertainty visible in both limitations and confidence; avoid HIGH confidence as consensus/verified interaction.

## Owned file scope — no other writes

Create at most six:

```text
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O13.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O14.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O15.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O16.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O17.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O18.json
```

Modify only:
```text
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/OBSERVATION_INDEX.md
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/checkpoints/CHECKPOINT_LEDGER.md
```

Preserve exact existing B1+B2 index content and Stage A+B1+B2 checkpoint content **byte-identically as a prefix**. Append a separate B3 entry and B3 `READY_FOR_REVIEW` checkpoint. No self-referential output SHA inside the same commit; final SHA must be reported after commit.

Do not edit W07-S2 registry source record, Stage A source qualifications, any W07-O01..O12, prior W02–W06 accepted/deferred records, AGENTS, schemas, SSOT, WORK_LEDGER, handoffs, README, or external repositories.

## Validation and boundaries

- Reverify canonical main, exact B3 governance SHA from issues #19/#20, accepted B2 SHA ancestor, stage gate.
- Inspect APG exact pages and WIP/404 status directly; original paraphrases only.
- Parse and structurally validate against accepted `.forge/knowledge/schemas/observation-record.schema.json`; distinguish manual structural checks from a complete Draft 2020-12 validator.
- Verify exact IDs, source `W07-S2`, `OBSERVED`, `DOCUMENTATION_STATEMENT`, unique links/anchors, valid domain, version and limitation fields; source scope only.
- Preserve all earlier index/checkpoint content as prefix and all prior record blob identities.
- Verify exact output diff only B3 allowed paths; no changes to registry, SSOT/ledger, Stage A/B1/B2 or earlier accepted knowledge.
- Do not claim keyboard/browser focus, AT/screen-reader output, runtime/test PASS or WCAG conformance merely from APG explanatory text.
- If conflicting advice, missing source, version drift, schema mismatch, context exhaustion, or inaccessible page blocks reliable extraction: STOP, report `BLOCKED`/`SOURCE_DRIFT`, no invented authority.

**Strict prohibition:** NO B4+, NO K4 cross-source comparison, NO K5 candidate, NO K6 final packet, NO K7, NO new source/independent family, NO frontend app/framework/packages/runtime, NO main merge, NO worker self-release.

## Worker return then STOP

```text
KIRION FORGE — LUCIEN
W07 STAGE B3 / WAI-ARIA APG K3 CHECKPOINT REPORT

1. LIVE MAIN AND BRANCH
2. EXACT B3 GOVERNANCE INPUT SHA / ANCESTRY
3. ACCEPTED STAGE A/B1/B2 RELEASE CHECKPOINTS
4. APG SOURCE ID, AUTHORITY CLASS AND RETRIEVAL LIMITS
5. APG MODAL / TOOLTIP / DISCLOSURE PAGES INSPECTED
6. CREATED OBSERVATION IDS 0–6 AND EXACT SOURCE LINKS
7. APG NON-NORMATIVE/WIP STATUS PRESERVATION
8. OBSERVATION INDEX APPEND/PREFIX CHECK
9. CHECKPOINT LEDGER APPEND/PREFIX CHECK
10. FILES CREATED AND MODIFIED
11. JSON / SCHEMA / SOURCE-ID / UNIQUENESS VALIDATION
12. PRIOR KNOWLEDGE, STAGE A, B1, B2 INTEGRITY
13. VALIDATION ACTUALLY EXECUTED
14. VALIDATION NOT EXECUTED / NOT APPLICABLE
15. SOURCE GAPS / CONTRADICTIONS / OPEN ITEMS
16. COMMITS CREATED
17. FINAL BRANCH
18. EXACT FINAL SHA
19. WORKER RECOMMENDATION
```

Recommendation exactly one: `READY_FOR_STAGE_REVIEW`, `REWORK_REQUIRED`, `BLOCKED`, `SOURCE_DRIFT`.

Then STOP. **No automatic release beyond B3.**
