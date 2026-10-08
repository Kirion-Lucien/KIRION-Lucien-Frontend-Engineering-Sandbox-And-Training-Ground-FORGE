# SSOT CURRENT

## Repository

`Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE`

## Program

`W06 — FORMS, VALIDATION & ERROR-RECOVERY INTELLIGENCE`

## Status

`CANDIDATE COMPLETE — MAINTAINER REVIEW REQUIRED`

W00 through W05 remain accepted and active as governing prior authority.

## Canonical accepted source before W06

`main@d58d7885c664553e12c6901a76d69a5da9cf85d4`

## Current W06 branch

`forge/w06-forms-validation-error-recovery-intelligence`

## Human objective

Teach Lucien how strong frontend systems communicate field purpose, instructions, constraints, validation, errors, and recovery so users can complete tasks without ambiguous labels, inaccessible error states, unnecessary re-entry, or lost progress.

## W06 research question

How should frontend forms communicate field purpose, instructions, constraints, validation, errors, and recovery so users can successfully complete tasks without ambiguous labels, inaccessible error states, unnecessary re-entry, or lost progress?

## Authorized source families

Exactly six logical source families:

1. W3C WCAG 2.2
2. W3C WAI Forms tutorials
3. GOV.UK Forms / Validation family
4. U.S. Web Design System Forms family
5. GitHub Primer Forms guidance
6. `primer/react@7f5303d803986887187d86dcebaeda22a4dc6823` forms implementation

## Prior knowledge preservation

All accepted/deferred W02–W05 knowledge remains immutable during worker execution.

Deferred records remain:

```text
W02-P02 — CANDIDATE / DEFERRED
W03-A01 — CANDIDATE / DEFERRED
```

## Active handoff

`.forge/handoffs/active/W06_FORMS_VALIDATION_ERROR_RECOVERY_INTELLIGENCE.md`

## W06 may

- qualify/reuse only the six authorized source families;
- build forms/validation/error-recovery vocabulary;
- create 30–42 observations, hard maximum 50;
- analyze labels/instructions, required/optional state, grouping, validation timing, error communication, error summaries, focus/announcements, error prevention, redundant entry, disabled/readonly semantics, and responsive form integrity;
- create at most 3 pattern candidates;
- create at most 2 anti-pattern candidates;
- return a Maintainer review packet.

## W06 may not

- create frontend application code;
- select a form/schema library;
- define backend validation architecture;
- create universal validation-timing law;
- create universal error-summary requirement;
- create universal disabled-button prohibition;
- add a seventh source family;
- mutate external repositories;
- fabricate runtime/browser/AT/usability evidence;
- promote candidates;
- alter prior knowledge;
- begin W07.

## Application implementation authority

`BLOCKED`

## Promotion authority

`MAINTAINER ONLY`

## W06 submitted worker candidate

K0–K6 run in `.forge/knowledge/runs/W06_FORMS_VALIDATION_ERROR_RECOVERY/`: 6 qualified source families (1 existing identity, 5 W06-specific additions); 46 working vocabulary definitions; 42 OBSERVED records; 14 challenged failure hypotheses; 3 pattern and 2 anti-pattern CANDIDATES; K6 review packet. USWDS Validation deprecation/known issues preserved.

**W06 is NOT ACCEPTED.** W02–W05 knowledge remains unchanged. K7 is Maintainer-only. Application implementation and W07 remain BLOCKED.

## Next gate

Worker returns an exact W06 candidate with one of:

`READY_FOR_MAINTAINER_REVIEW`
`REWORK_REQUIRED`
`BLOCKED`
`SOURCE_DRIFT`

No W07 or frontend implementation begins before Maintainer disposition.
