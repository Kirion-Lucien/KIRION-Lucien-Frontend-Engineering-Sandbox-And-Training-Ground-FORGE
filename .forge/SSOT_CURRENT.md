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

**Exact accepted baseline:** `main@61987e3de3ff85426e293dd15e596200ad272103`

**Working branch:** `forge/w07-dialogs-overlays-focus-intelligence`

**Stage A (K0–K2):** `AUTHORIZED — SOURCE DISCOVERY & QUALIFICATION ONLY`

**Stage B (K3 observation batches):** `BLOCKED — MAINTAINER STAGE A CHECKPOINT RELEASE REQUIRED`

**Stage C (K4–K6 comparison/synthesis):** `BLOCKED — MAINTAINER STAGE B RELEASE REQUIRED`

**K7 knowledge acceptance/promotion:** `MAINTAINER ONLY`

**Active handoff:** `.forge/handoffs/active/W07_STAGE_A_SOURCE_QUALIFICATION.md`

**Binding workload protocol:** `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md` (`FORGE-0006`).

The Stage A worker may qualify only the six pre-approved source families and write the explicitly bounded Stage A artifacts/checkpoint. The full W07 run, its observation batches, candidate synthesis, and further stage releases are not authorized by this gate.

A worker must verify the exact governance head from the W07 issue and live Git before mutation. Completion does not self-release Stage B.

## Prior accepted knowledge

W00–W06 remain accepted; W02-P02 and W03-A01 remain CANDIDATE / DEFERRED. No prior knowledge record may be changed by W07 Stage A.

## Application implementation authority

`BLOCKED`

No frontend application Code Writer lane exists; no framework, router, component library, dependencies, frontend runtime, or application tests are authorized.
