# SSOT CURRENT

## Repository

`Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE`

## Program

`W06 — FORMS, VALIDATION & ERROR-RECOVERY INTELLIGENCE`

## Status

`ACCEPTED / FORMS & ERROR-RECOVERY KNOWLEDGE ACTIVE`

W00 through W05 remain accepted and active as governing prior authority.

W06 Maintainer acceptance is recorded in GitHub issue #13 and `.forge/ACCEPTANCE.md`.

## Canonical source before W06

`main@d58d7885c664553e12c6901a76d69a5da9cf85d4`

## Exact reviewed W06 worker candidate

`forge/w06-forms-validation-error-recovery-intelligence@6b3fcde1bc12ecd6904dc4bbb1f2f91ff29ed54d`

## Accepted W06 corpus

Six logical source families:

1. W3C WCAG 2.2
2. W3C WAI Forms tutorials
3. GOV.UK Forms / Validation family
4. U.S. Web Design System Forms family
5. GitHub Primer Forms guidance
6. `primer/react@7f5303d803986887187d86dcebaeda22a4dc6823` forms implementation

WCAG reused `W02-S1`. W06 added `W06-S2` through `W06-S6`.

## Accepted bounded patterns

### W06-P01 — Persistent field identity with semantic instruction relationships

`ACCEPTED / MEDIUM CONFIDENCE`

Fields remain intelligibly identified with appropriate persistent identification and relevant programmatic relationships.

### W06-P02 — Actionable, source-linked error communication

`ACCEPTED / MEDIUM CONFIDENCE`

Detected errors identify the affected item in text and provide known safe correction guidance with appropriate linkage where useful.

### W06-P03 — Recoverable validation failure with preserved answers

`ACCEPTED / MEDIUM CONFIDENCE`

Recoverable failures preserve safely retainable answers and provide a route to correct and continue, subject to security/privacy/task exceptions.

## Accepted bounded anti-patterns

### W06-A01 — Placeholder-only field identification

`ACCEPTED / MEDIUM CONFIDENCE`

Placeholder text must not be the sole field-identification mechanism without a reliable persistent/programmatic equivalent.

### W06-A02 — Detected field error signaled only by color

`ACCEPTED / HIGH CONFIDENCE`

Automatically detected input errors must not be represented only through color/styling without textual error identification within applicable WCAG 3.3.1 scope.

## Form knowledge boundaries

No universal:

- validation timing;
- error-summary requirement;
- post-error focus destination;
- disabled-submit prohibition;
- backend validation architecture;
- form/schema library;
- data-retention policy.

## Prior deferred knowledge preserved

```text
W02-P02 — CANDIDATE / DEFERRED
W03-A01 — CANDIDATE / DEFERRED
```

## Application implementation authority

`BLOCKED`

No frontend application Code Writer lane exists.

## Current work gate

`W07 — DIALOGS, OVERLAYS & FOCUS-MANAGEMENT INTELLIGENCE`

**Canonical accepted main:** `61987e3de3ff85426e293dd15e596200ad272103`.

**Working branch:** `forge/w07-dialogs-overlays-focus-intelligence`.

**Stage A K0–K2:** `ACCEPTED / RELEASED` — exact checkpoint `0e4340649fb71aef1ef00e46caa8433342bf697a`, issue #17.

**Stage B1 WCAG K3:** `ACCEPTED / RELEASED` — exact checkpoint `53084dd7c8f812732fc556873c3d7753c3aa1c3b`, issue #18.

**Stage B2 WHATWG K3:** `ACCEPTED / RELEASED` — exact checkpoint `791910cb0f623de36edfb301afbe6e7586ced214`, issue #19.

**Stage B3 WAI ARIA APG K3:** `ACCEPTED / RELEASED` — exact worker checkpoint `e1ee045c6ff16a89771272abefd4223ad2a2d4b6`, issue #20 Maintainer review comment 6065798465. Six explanatory `OBSERVED` records `W07-O13..O18`, including tooltip WIP/no consensus.

**Stage B4 USWDS Modal K3:** `ACCEPTED / RELEASED` — worker `cf6d6ccc1a197efd3f24250821f3a0b7e55b00df`, issue #21 Maintainer acceptance comment `6066480383`. Six `OBSERVED` records O19..O24 from `W07-S4`; documentation only, no application tests.

**Stage B5 Primer PRODUCT K3:** `AUTHORIZED — ONE SOURCE-BOUNDED BATCH ONLY`, 0–6 observations `W07-O25..O30` from `W07-S5`; exact governance worker start SHA to be issued in GitHub #22 after commit. B4 acceptance is binding.

**Stage B6 onward:** `BLOCKED — INDEPENDENT B5 CHECKPOINT REVIEW/RELEASE REQUIRED`.

**Stage C K4–K6:** `BLOCKED — COMPLETED STAGE B RELEASE REQUIRED`.

**K7:** `MAINTAINER ONLY`.

**Active handoff:** `.forge/handoffs/active/W07_STAGE_B5_PRIMER_PRODUCT_OBSERVATIONS.md`.

**Historical handoffs:** `.forge/handoffs/historical/W07_STAGE_A_SOURCE_QUALIFICATION.md`, `.forge/handoffs/historical/W07_STAGE_B1_WCAG_OBSERVATIONS.md`, `.forge/handoffs/historical/W07_STAGE_B2_WHATWG_OBSERVATIONS.md`, `.forge/handoffs/historical/W07_STAGE_B3_WAI_APG_OBSERVATIONS.md`, `.forge/handoffs/historical/W07_STAGE_B4_USWDS_MODAL_OBSERVATIONS.md`.

**Binding workload protocol:** `FORGE-0006`, `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`.

B5 worker MUST verify exact B5 governance head in issue #22, accepted B4 checkpoint as ancestor, and unchanged main. This batch uses only Primer product documentation `W07-S5` (DESIGN_SYSTEM / OFFICIAL_REFERENCE), not pinned Primer React source `W07-S6`. Live docs are unpinned; no browser/runtime tests are claimed. No B6, synthesis, promotion, or app implementation authority.

## Prior accepted knowledge

W00–W06 remain ACCEPTED; W02-P02 and W03-A01 remain CANDIDATE / DEFERRED. All previously committed prior knowledge and W07 B1/B2 records remain immutable.

## Application implementation authority

`BLOCKED`

No frontend application Code Writer lane, framework, packages, component-library adoption, runtime or application test authorization exists.
