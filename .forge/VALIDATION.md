# VALIDATION LAW

## Allowed evidence statuses

Use only these labels:

- `PASS`
- `FAIL`
- `SOURCE INSPECTED`
- `RUNTIME OBSERVED`
- `NOT RUN`
- `NOT OBSERVED`
- `UNKNOWN`
- `BLOCKED`

Do not report `PASS` when only source was inspected.

## Every candidate must prove

### Source integrity

- source branch resolved;
- exact source SHA resolved;
- candidate ancestry matches the handoff;
- unrelated protected branches were not mutated.

### Scope integrity

- changed files are listed;
- each changed file belongs to the authorized lane;
- prohibited scope is explicitly confirmed untouched.

### Functional evidence

Only requirements that can actually be executed must be marked PASS/FAIL.

If no runtime exists, state `NOT RUN`, not PASS.

### Architecture evidence

Any new architecture decision must have an accepted decision identifier before workers enforce it.

## Bootstrap W00 acceptance gates

- exact source is `90411ea873cb380ed6b688a4dfdc0f09f67067da`;
- evidence snapshot matches live Git;
- no frontend framework is selected;
- no package is introduced;
- unknowns remain explicit;
- AGENTS blocks implementation while W00 is under review;
- Maintainer records ACCEPT or specific REWORK.

## Future validation

Testing commands, browser matrices, linting, typechecking, builds, accessibility checks, and CI requirements are architecture-dependent and remain undecided until the relevant stack is accepted.
