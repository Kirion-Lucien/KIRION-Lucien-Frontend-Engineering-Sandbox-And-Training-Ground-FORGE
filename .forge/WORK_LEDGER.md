# WORK LEDGER

## W00 — Forge authority bootstrap

**State:** ACCEPTED

**Source:** `main@90411ea873cb380ed6b688a4dfdc0f09f67067da`

**Accepted candidate:** `7ac1f5683360166552414ed15ee5641cbc4d5389`

**Promoted main:** `e944dcbd490651498faead104315edd4c649b4ae`

**Acceptance:** GitHub issue #1

## W01 — Frontend knowledge acquisition model

**State:** ACCEPTED

**Source:** `main@e944dcbd490651498faead104315edd4c649b4ae`

**Reviewed candidate:** `forge/w01-frontend-knowledge-acquisition-model@b8bf1c5221f3a2fbb43231000450d7d8d8fe7a44`

**Acceptance:** GitHub issue #3

## W02 — Controlled pilot acquisition: action controls

**State:** ACCEPTED

**Source:** `main@9b4d291b15322afd46ee83ccb9a6dc40e31d3b06`

**Reviewed worker candidate:** `forge/w02-controlled-pilot-action-controls@ac7b38da1e0e09bad195a5a216dc0dfa7efbfae3`

**Acceptance:** GitHub issue #5

**K7:**

```text
W02-P01 — ACCEPTED / MEDIUM
W02-A01 — ACCEPTED / MEDIUM
W02-P02 — CANDIDATE / DEFERRED
```

## W03 — Visual hierarchy & composition intelligence

**State:** ACCEPTED

**Source:** `main@20a2bb44461a1066b44aa242c6bad18fac673025`

**Reviewed worker candidate:** `forge/w03-visual-hierarchy-composition-intelligence@b268b5663e5d65c6b38f5557c021b449a9e2b03b`

**Acceptance:** GitHub issue #7

**K7:**

```text
W03-P01 — ACCEPTED / MEDIUM
W03-P02 — ACCEPTED / MEDIUM
W03-P03 — ACCEPTED / MEDIUM
W03-A01 — CANDIDATE / DEFERRED / LOW
```

## W04 — Responsive layout & mobile adaptation intelligence

**State:** ACCEPTED

**Source:** `main@c9acd923b11d8695ab5ba41569599fc9165f5b97`

**Reviewed worker candidate:** `forge/w04-responsive-mobile-adaptation-intelligence@9aef7979d2c247f555e6b89d481270a4de19d4a1`

**Acceptance:** GitHub issue #9

**Historical handoff:** `.forge/handoffs/historical/W04_RESPONSIVE_MOBILE_ADAPTATION_INTELLIGENCE.md`

**K7:**

```text
W04-P01 — ACCEPTED / MEDIUM
W04-P02 — ACCEPTED / MEDIUM
W04-P03 — ACCEPTED / MEDIUM
W04-A01 — ACCEPTED / MEDIUM
W04-A02 — ACCEPTED / MEDIUM
```

## W05 — Navigation & information architecture intelligence

**State:** ACCEPTED

**Source:** `main@5746b9412aa10333e7bc86ea54897f8be6b63267`

**Reviewed worker candidate:** `forge/w05-navigation-information-architecture-intelligence@cebe0abd78e8806deef8af7f3f94ed0a17c44416`

**Acceptance:** GitHub issue #11

**Historical handoff:** `.forge/handoffs/historical/W05_NAVIGATION_INFORMATION_ARCHITECTURE_INTELLIGENCE.md`

**Accepted run result:**

- six logical source families;
- one reused WCAG identity plus five new qualified W05 source records;
- 40 evidence-linked working vocabulary terms;
- 40 bounded OBSERVED records;
- navigation/action, global/local/contextual, orientation, hierarchy, breadcrumbs, tabs, menu semantics, labeling, responsive-navigation and multiple-ways analysis;
- no router/framework selection;
- no application implementation;
- no fabricated browser/keyboard/AT/usability evidence;
- all 12 prior W02–W04 knowledge records preserved byte-for-byte before K7;
- all pre-existing registry source records preserved unchanged.

**K7 promotion result:**

```text
W05-P01 — Current-location multi-cue orientation
ACCEPTED / MEDIUM CONFIDENCE

W05-P02 — Relationship-matched navigation mechanisms
ACCEPTED / MEDIUM CONFIDENCE

W05-P03 — URL-backed related-view navigation with semantic separation
ACCEPTED / MEDIUM CONFIDENCE

W05-A01 — Breadcrumb relationship confusion
ACCEPTED / MEDIUM CONFIDENCE

W05-A02 — Ordinary site navigation miscast as application menubar
ACCEPTED / MEDIUM CONFIDENCE
```

Deferred prior candidates remain unpromoted.

## W06 — Forms, validation & error-recovery intelligence

**State:** ACCEPTED

**Source:** `main@d58d7885c664553e12c6901a76d69a5da9cf85d4`

**Reviewed worker candidate:** `forge/w06-forms-validation-error-recovery-intelligence@6b3fcde1bc12ecd6904dc4bbb1f2f91ff29ed54d`

**Acceptance:** GitHub issue #13

**Historical handoff:** `.forge/handoffs/historical/W06_FORMS_VALIDATION_ERROR_RECOVERY_INTELLIGENCE.md`

**Accepted run result:**

- six logical source families;
- one reused WCAG identity plus five new qualified W06 source records;
- 42 bounded OBSERVED records;
- forms/validation/error-recovery vocabulary;
- form-model and recovery analysis;
- no form/schema library selection;
- no backend validation architecture;
- no fabricated browser/AT/server/usability evidence;
- all 17 prior W02–W05 knowledge records preserved before K7;
- all pre-existing registry records preserved before append.

**K7 promotion result:**

```text
W06-P01 — Persistent field identity with semantic instruction relationships
ACCEPTED / MEDIUM

W06-P02 — Actionable, source-linked error communication
ACCEPTED / MEDIUM

W06-P03 — Recoverable validation failure with preserved answers
ACCEPTED / MEDIUM

W06-A01 — Placeholder-only field identification
ACCEPTED / MEDIUM

W06-A02 — Detected field error signaled only by color
ACCEPTED / HIGH
```

## W07 — Next knowledge lane

**State:** INPUT REQUIRED / REVIEW

W07 is undefined.

No acquisition or implementation authority exists until a new exact Maintainer handoff is issued.


## G01 — Knowledge workload isolation governance

**State:** ACCEPTED POLICY / effective upon promotion to canonical `main`.

**Human authorization:** 2026-10-08.

**Source:** `main@68330d52b88c0e4a0d14efa48fe9db26d64f82c1`.

**Decision:** FORGE-0006.

**Governance:** `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`.

**Contract:** exact-source K0–K2 qualification, 5–8 observation target batches in K3, Git-backed stage/checkpoint ledger, Maintainer release A→B and B→C, independent K6/K7 review. Small runs can use one session only if allowed by a bounded handoff without skipping gates.

**Out of scope:** W07 acquisition/implementation, new framework/stack, altered accepted source and pattern records, new dependencies, automated CI.

## W07 — Dialogs / overlays / focus-management knowledge proposal

**State:** INPUT REQUIRED / REVIEW.

The topic is a proposal from previous planning, not an activated run. W07 requires its own accepted source scope, branch/SHA and stage handoffs under FORGE-0006.

## Application implementation authority

**State:** BLOCKED.
