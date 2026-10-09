# W07 C1 — CONTRADICTIONS AND CONTEXT (K4 ONLY)

**READY_FOR_REVIEW, not accepted knowledge.** This is a cross-source dispute register derived solely from 36 accepted K3 observation records. Categories are analytical metadata, not record-schema enums or proof of application defects. Full [source/ID coverage matrix](CROSS_SOURCE_COMPARISON.md).

DIRECT_CONFLICT requires incompatible claims about the **same version, task and conditions**; **confirmed DIRECT_CONFLICT: 0** (not proof of global conflict absence). CONTEXTUAL_TRADEOFF reflects legitimate differing use contexts. SOURCE_AUTHORITY_SPLIT reflects normative vs guidance vs implementation. VERSION_MISMATCH flags unaligned documentation and pinned code/test edition. EVIDENCE_GAP flags missing runtime/context/dependency. NOT_COMPARABLE flags different mechanics or test populations.

**20 entries:** DIRECT_CONFLICT 0; CONTEXTUAL_TRADEOFF 4; SOURCE_AUTHORITY_SPLIT 4; VERSION_MISMATCH 4; EVIDENCE_GAP 4; NOT_COMPARABLE 4. A primary label does not suppress a secondary caveat.

### C01 — WCAG keyboard exit versus APG focus loop

**Classification:** CONTEXTUAL_TRADEOFF. **Accepted observation references:** O02,O14.

**Comparison:** Modal Tab cycling with an available keyboard-only exit is not inherently a no-trap violation.

**Remaining limit or countercontext:** Actual keyboard exit and instructions not tested.

### C02 — APG Escape and USWDS forced action

**Classification:** CONTEXTUAL_TRADEOFF. **Accepted observation references:** O02,O14,O20.

**Comparison:** Typical modal close pattern differs from bounded acknowledgment gate; no universal close policy.

**Remaining limit or countercontext:** Keyboard rejection/continue/leave pathway and task requirement unknown.

### C03 — Native modal versus visual/ARIA modal

**Classification:** NOT_COMPARABLE. **Accepted observation references:** O07,O08,O13,O19,O25.

**Comparison:** showModal and native inertness are algorithms, not implied by component name or CSS.

**Remaining limit or countercontext:** Deployed underlying primitive absent.

### C04 — Native inertness versus ARIA/code

**Classification:** SOURCE_AUTHORITY_SPLIT. **Accepted observation references:** O08,O12,O13,O31,O34.

**Comparison:** HTML platform algorithm, APG aria-modal guidance, pinned role none answer different questions.

**Remaining limit or countercontext:** No outside-inert behavior or AT tested.

### C05 — Primer docs versus pinned description markup

**Classification:** VERSION_MISMATCH. **Accepted observation references:** O13,O21,O26,O31.

**Comparison:** Pinned unconditional aria-describedby and conditional subtitle target may differ from unpinned docs.

**Remaining limit or countercontext:** Absent subtitle rendered DOM outcome unobserved.

### C06 — Initial focus

**Classification:** CONTEXTUAL_TRADEOFF. **Accepted observation references:** O09,O15,O26,O32.

**Comparison:** HTML autofocus algorithm, APG content/consequence advice, Primer refs/hooks have different conditions.

**Remaining limit or countercontext:** No rendered initial focus/scroll measurement.

### C07 — Return focus when opener is gone

**Classification:** EVIDENCE_GAP. **Accepted observation references:** O09,O16,O26,O32.

**Comparison:** APG logical exception and native conditions cannot prove Primer delegated focus-hook result.

**Remaining limit or countercontext:** Missing invoker/hook behavior uninspected.

### C08 — Native close request and custom callback

**Classification:** SOURCE_AUTHORITY_SPLIT. **Accepted observation references:** O10,O20,O32.

**Comparison:** requestClose cancel/closedby differs from USWDS data-force-action and Primer guarded onClose.

**Remaining limit or countercontext:** No mapping from callback to app state or native lifecycle.

### C09 — Native popover versus Primer controlled Popover

**Classification:** NOT_COMPARABLE. **Accepted observation references:** O11,O29,O36.

**Comparison:** HTML auto/manual/hint light dismiss differs from Primer open/callback props.

**Remaining limit or countercontext:** Imported hook/caller-controlled state not inspected.

### C10 — Normative hover content versus tooltip guidance

**Classification:** SOURCE_AUTHORITY_SPLIT. **Accepted observation references:** O06,O17,O27,O28.

**Comparison:** WCAG applicability/exceptions, APG provisional pattern and Primer warning have different weight.

**Remaining limit or countercontext:** Hover, persistence, Escape and AT checks not run.

### C11 — Current tooltip versus deprecated pinned v1

**Classification:** VERSION_MISMATCH. **Accepted observation references:** O17,O28,O35.

**Comparison:** Deprecated marker applies only to pinned Tooltip v1, not current Product or APG consensus.

**Remaining limit or countercontext:** Live Product version/trigger association unverified.

### C12 — Disclosure versus popover

**Classification:** NOT_COMPARABLE. **Accepted observation references:** O18,O11,O29.

**Comparison:** Disclosure Enter/Space, aria-expanded is not native popover or Primer outside-click semantics.

**Remaining limit or countercontext:** No product-specific controlled region.

### C13 — Responsive and source/visual order

**Classification:** EVIDENCE_GAP. **Accepted observation references:** O03,O05,O15,O22,O23,O25,O28,O34.

**Comparison:** Guidance plus WCAG criteria does not establish screen overlap, order, zoom or Portal top layer.

**Remaining limit or countercontext:** No browser/mobile/AT measurement.

### C14 — Publisher tests versus authored test assertions

**Classification:** NOT_COMPARABLE. **Accepted observation references:** O24,O33.

**Comparison:** USWDS reports tests; pinned Primer merely authors tests; no shared executed suite.

**Remaining limit or countercontext:** No Kirion PASS, WCAG 2.2 validation or app test.

### C15 — WCAG versus WAI APG provenance

**Classification:** SOURCE_AUTHORITY_SPLIT. **Accepted observation references:** O01–O06,O13–O18.

**Comparison:** W3C origin is shared but APG explanatory/WIP does not reproduce normative WCAG.

**Remaining limit or countercontext:** Do not count as two independent normative votes.

### C16 — Long modal versus dedicated page

**Classification:** CONTEXTUAL_TRADEOFF. **Accepted observation references:** O19,O23,O25.

**Comparison:** USWDS and Primer both describe full-page alternative under different product/size contexts.

**Remaining limit or countercontext:** No empirically established threshold.

### C17 — Overlay Product versus pinned React

**Classification:** VERSION_MISMATCH. **Accepted observation references:** O30,O34.

**Comparison:** Same publisher with private API intent and pinned role/hook/Portal branches, but no release parity.

**Remaining limit or countercontext:** Actual runtime and live Product correspondence unverified.

### C18 — Tooltip timing, obscuration and focus

**Classification:** EVIDENCE_GAP. **Accepted observation references:** O05,O06,O17,O28.

**Comparison:** WCAG threshold/conditions cannot be verified from product placement/delay/API descriptions.

**Remaining limit or countercontext:** No pointer/keyboard/zoom/AT trial.

### C19 — WCAG 2.1 publisher edition versus WCAG 2.2

**Classification:** VERSION_MISMATCH. **Accepted observation references:** O01–O06,O24.

**Comparison:** USWDS test-last v3.8.2 and separate v3.13.0 banner do not prove new tests or WCAG 2.2.

**Remaining limit or countercontext:** No same-release executed result.

### C20 — Pinned conditional subtitle and ARIA reference

**Classification:** EVIDENCE_GAP. **Accepted observation references:** O13,O21,O26,O31.

**Comparison:** Source could leave dangling ID but not a proven browser accessible-name defect.

**Remaining limit or countercontext:** Missing/filled/custom header DOM and screen-reader needed.


## Review-only resolutions and reserved decisions

No universal modal dismissal, forced-action, initial focus, tooltip semantics, API, browser behavior or package choice follows. In particular, WCAG and APG share W3C lineage but different normative status; Primer Product and pinned code share publisher without proof of version equivalence; APG tooltip is WIP; pinned Tooltip v1 deprecation does not extend to current product; HTML native popover is not Primer Popover. USWDS component reports 13 passed/1 conditional WCAG 2.1 AA tests, distinct from authored unexecuted Primer tests and Kirion tests NOT RUN. No code-level potential dangling aria-describedby target can be labeled an actual AT failure without execution.

No K5/K6/K7 artifacts, no frontend app, PR or main integration. C2 requires independent Maintainer C1 acceptance and new exact-SHA handoff. All observation evidence pointers are retained in the comparison matrix, not freshly retrieved.
