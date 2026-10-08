# KIRION FORGE: MAINTAINER
# LUCIEN W06 — FORMS, VALIDATION & ERROR-RECOVERY INTELLIGENCE
# LABELS / INSTRUCTIONS / GROUPING / VALIDATION / ERROR SUMMARY / RECOVERY

## AUTHORITY CLASS

Bounded KIRION Forge Maintainer handoff.

W06 extends Lucien's accepted interaction, composition, responsive, and navigation knowledge into forms, validation, error communication, and recovery.

This is NOT:

- frontend application implementation;
- form-library selection;
- schema-library selection;
- backend validation design;
- authentication architecture;
- payment/compliance workflow design;
- permission to define one universal form layout;
- permission to validate only on blur, submit, or input as a universal law;
- permission to treat disabled controls as default error handling;
- mass crawling;
- runtime accessibility certification;
- K7 self-promotion.

Worker role:

```text
KIRION FORGE: FRONTEND KNOWLEDGE ACQUISITION WORKER
```

Execute K0–K6 only.

K7 remains Maintainer-only.

---

# 0. EXACT REPOSITORY AUTHORITY

Repository:

```text
Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE
```

Canonical accepted source before W06:

```text
main@d58d7885c664553e12c6901a76d69a5da9cf85d4
```

W06 branch:

```text
forge/w06-forms-validation-error-recovery-intelligence
```

Before any mutation:

1. resolve live `main`;
2. resolve W06 branch head;
3. confirm W06 branch descends from the exact canonical source above;
4. confirm W00–W05 are accepted;
5. confirm no newer active handoff supersedes this lane.

If any exact-source condition fails:

```text
SOURCE_DRIFT
STOP
RETURN TO MAINTAINER
```

Do not silently rebase.

---

# 1. CONTROLLING ACCEPTED KNOWLEDGE

Read and obey all current Forge authority.

Accepted knowledge from W02–W05 remains controlling.

Especially relevant:

```text
W02-P01 — Contextual dominant primary action
W02-A01 — Competing dominant primary controls

W03-P01 — Semantic and visual region alignment
W03-P02 — Purpose-bounded reading width
W03-P03 — Content-first responsive composition

W04-P01 — Recoverable responsive reduction
W04-P02 — Meaningful source and focus order through responsive relocation
W04-A01 — Unrecoverable task-critical control disappearance

W05-P01 — Current-location multi-cue orientation
W05-P02 — Relationship-matched navigation mechanisms
```

Deferred knowledge remains deferred:

```text
W02-P02 — CANDIDATE / DEFERRED
W03-A01 — CANDIDATE / DEFERRED
```

W06 may cite prior knowledge.

W06 may not alter prior status.

---

# 2. HUMAN OBJECTIVE

Lucien must learn how strong frontend systems help users enter, understand, correct, and submit information without avoidable confusion or dead ends.

Lucien must learn the vocabulary behind:

```text
form
field
label
caption
hint
instruction
required
optional
constraint
validation
client-side validation
server-side validation
native validation
error
warning
success
error identification
error suggestion
error summary
inline error
field-level error
form-level error
focus management
error recovery
preserved input
grouping
fieldset
legend
choice group
checkbox group
radio group
autocomplete
input purpose
format guidance
example value
character count
disabled
readonly
submission
confirmation
destructive submission
review step
error prevention
redundant entry
```

The goal is not:

```text
"make a pretty form"
```

The goal is:

```text
help users know what is required,
what went wrong,
where it went wrong,
how to fix it,
and how to continue without losing work.
```

---

# 3. W06 RESEARCH QUESTION

Primary question:

> **How should frontend forms communicate field purpose, instructions, constraints, validation, errors, and recovery so users can successfully complete tasks without ambiguous labels, inaccessible error states, unnecessary re-entry, or lost progress?**

Operational sub-questions:

1. What does WCAG actually require around labels/instructions, error identification, error suggestion, error prevention, redundant entry, name/role/value, and programmatic relationships?
2. How should visible labels differ from placeholders, hints, captions, and examples?
3. When should fields be grouped semantically?
4. How should required/optional status be communicated?
5. What belongs in inline field errors versus an error summary?
6. How should focus move after failed submission, if at all?
7. When should validation occur during entry versus on submit?
8. How should systems preserve user-entered values after errors?
9. When are disabled controls appropriate and when do they create blocked recovery?
10. How should destructive/legal/financial/data submissions add confirmation, review, reversal, or correction?
11. How should responsive layouts preserve labels, errors, instructions, and task-critical actions?
12. Which recurring form failure modes are supported strongly enough to become candidates?

Allowed domains:

```text
FORM_DESIGN
VALIDATION
ERROR_HANDLING
CONTENT_DESIGN
SEMANTIC_HTML
ACCESSIBILITY
FOCUS_MANAGEMENT
INTERACTION
RESPONSIVE_DESIGN
VISUAL_HIERARCHY
COMPONENT_ARCHITECTURE
```

Do not expand into backend validation implementation, data models, auth flows, payment security, or product-specific compliance logic.

---

# 4. CONTROLLED SOURCE CORPUS

Use exactly SIX logical source families.

Directly linked official sub-pages may be inspected within each family.

Do not add a seventh independent source family.

## S1 — W3C WCAG 2.2

Canonical:

```text
https://www.w3.org/TR/WCAG22/
```

Reuse existing qualified source identity where appropriate.

Candidate authority:

```text
OFFICIAL_STANDARD
PRIMARY_NORMATIVE
```

Relevant success criteria may include:

```text
1.3.1 Info and Relationships
1.3.5 Identify Input Purpose
2.4.3 Focus Order
2.4.6 Headings and Labels
3.2.1 On Focus
3.2.2 On Input
3.3.1 Error Identification
3.3.2 Labels or Instructions
3.3.3 Error Suggestion
3.3.4 Error Prevention (Legal, Financial, Data)
3.3.7 Redundant Entry
4.1.2 Name, Role, Value
```

Rules:

- preserve conformance level and scope;
- preserve exceptions;
- do not turn WCAG into a universal validation-timing prescription;
- do not claim every form needs an error summary;
- do not claim every change requires confirmation.

## S2 — W3C WAI Forms Tutorials

Canonical family may include:

```text
https://www.w3.org/WAI/tutorials/forms/
https://www.w3.org/WAI/tutorials/forms/labels/
https://www.w3.org/WAI/tutorials/forms/instructions/
https://www.w3.org/WAI/tutorials/forms/grouping/
https://www.w3.org/WAI/tutorials/forms/validation/
https://www.w3.org/WAI/tutorials/forms/notifications/
```

Candidate authority:

```text
ACCESSIBILITY_REFERENCE
OFFICIAL_REFERENCE
```

Investigate:

- labels;
- instructions;
- grouping;
- fieldsets/legends;
- validation;
- error text;
- notification patterns;
- accessible associations.

Do NOT relabel tutorial guidance as new normative WCAG criteria.

## S3 — GOV.UK Forms / Validation Family

Canonical family may include:

```text
https://design-system.service.gov.uk/components/text-input/
https://design-system.service.gov.uk/components/error-message/
https://design-system.service.gov.uk/components/error-summary/
https://design-system.service.gov.uk/patterns/validation/
https://design-system.service.gov.uk/patterns/question-pages/
https://design-system.service.gov.uk/components/fieldset/
https://design-system.service.gov.uk/components/radios/
https://design-system.service.gov.uk/components/checkboxes/
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- visible labels;
- hint text;
- one-question-per-page/service-flow conventions;
- error-message wording;
- error summary behavior;
- linking summary items to fields;
- preserving answers;
- grouping choices;
- validation timing;
- optional/required signaling.

Do not universalize GOV.UK service-flow conventions.

## S4 — U.S. Web Design System Forms Family

Canonical family may include:

```text
https://designsystem.digital.gov/components/form/
https://designsystem.digital.gov/components/validation/
https://designsystem.digital.gov/components/text-input/
https://designsystem.digital.gov/components/error-message/
https://designsystem.digital.gov/components/fieldset/
https://designsystem.digital.gov/components/radio-buttons/
https://designsystem.digital.gov/components/checkbox/
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- labels/instructions;
- grouping;
- validation messaging;
- error states;
- required/optional conventions;
- accessibility guidance;
- user-research caveats;
- field width/format where documented.

Do not turn USWDS component conventions into universal form law.

## S5 — GitHub Primer Forms Guidance

Canonical family may include:

```text
https://primer.style/product/components/form-control/
https://primer.style/product/components/text-input/
https://primer.style/product/components/select/
https://primer.style/product/components/checkbox/
https://primer.style/product/components/radio/
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- label/caption/validation relationships;
- required/disabled behavior;
- validation states;
- character limits;
- loading/status indicators where relevant;
- choice groups;
- accessibility guidance;
- visual versus programmatic error state.

Do not assume current docs equal the pinned implementation snapshot.

## S6 — Primer React Forms Implementation

Repository:

```text
primer/react
```

Exact source SHA:

```text
7f5303d803986887187d86dcebaeda22a4dc6823
```

Candidate authority:

```text
COMPONENT_LIBRARY
PRIMARY_IMPLEMENTATION
```

Inspect only directly relevant forms implementation, including where useful:

```text
packages/react/src/FormControl/FormControl.tsx
packages/react/src/FormControl/_FormControlContext.tsx
packages/react/src/FormControl/_FormControlContextProvider.tsx
packages/react/src/FormControl/_FormControlValidation.tsx
packages/react/src/FormControl/FormControlLabel.tsx
packages/react/src/FormControl/FormControlCaption.tsx
packages/react/src/FormControl/FormControl.test.tsx

packages/react/src/TextInput/TextInput.tsx
packages/react/src/TextInput/TextInput.test.tsx

packages/react/src/Select/Select.tsx
packages/react/src/Select/Select.test.tsx

packages/react/src/Checkbox/Checkbox.tsx
packages/react/src/Checkbox/Checkbox.test.tsx

packages/react/src/Radio/Radio.tsx
packages/react/src/Radio/Radio.test.tsx
```

Directly referenced group/context utilities may be inspected only as required to understand labels, validation, grouping, or ARIA wiring.

Do not roam unrelated components.

Do not substitute newer `main`.

Do not mutate `primer/react`.

Tests read != tests executed.

---

# 5. SOURCE LIMIT

Independent source families:

```text
EXACTLY 6
```

Do NOT add during W06:

- Material;
- Apple HIG;
- Shopify Polaris;
- Carbon forms;
- Atlassian;
- Nielsen Norman Group;
- Baymard;
- React Hook Form;
- Formik;
- Zod;
- Yup;
- random blogs;
- Reddit;
- Stack Overflow.

Those may be separately qualified in later lanes.

---

# 6. W06 OUTPUT SURFACE

W06 may create only:

```text
.forge/knowledge/runs/W06_FORMS_VALIDATION_ERROR_RECOVERY/
├── REQUEST.md
├── SOURCE_QUALIFICATION.md
├── VOCABULARY.md
├── OBSERVATION_INDEX.md
├── CROSS_SOURCE_COMPARISON.md
├── FORM_MODEL_ANALYSIS.md
├── VALIDATION_ERROR_RECOVERY_ANALYSIS.md
├── FAILURE_MODE_ANALYSIS.md
├── UNRESOLVED.md
├── review/
│   └── MAINTAINER_REVIEW_PACKET.md
├── observations/
│   └── *.json
└── candidates/
    ├── patterns/
    │   └── *.json
    └── anti-patterns/
        └── *.json
```

W06 may modify:

```text
.forge/knowledge/registry/sources.json
.forge/SSOT_CURRENT.md
.forge/WORK_LEDGER.md
README.md
```

only as required for accurate W06 state.

Do NOT modify accepted W01 schemas/protocols.

If the accepted schema cannot represent valid W06 knowledge:

```text
SCHEMA_BLOCK
STOP
RETURN TO MAINTAINER
```

---

# 7. K0 — REQUEST RECORD

`REQUEST.md` must record:

- run ID;
- canonical Lucien source SHA;
- branch;
- human objective;
- research question;
- allowed domains;
- six source families;
- observation/candidate caps;
- non-goals;
- authority;
- start timestamp;
- stop conditions.

---

# 8. K1 / K2 — SOURCE DISCOVERY & QUALIFICATION

For each source family:

- verify canonical identity;
- preserve date/version/SHA where possible;
- preserve source type and authority weight;
- preserve license/reuse status;
- preserve retrieval limitations;
- reuse existing source IDs only when identity is materially the same;
- create a W06-specific source record when the forms target is materially distinct from prior acquisitions.

No ambiguous duplicate records.

Source qualification != accepted form practice.

---

# 9. VOCABULARY REQUIREMENT

Create:

```text
VOCABULARY.md
```

Define evidence-linked working terms including at minimum:

```text
form
form control
field
label
accessible name
caption
hint
instruction
example
placeholder
required
optional
constraint
validation
client-side validation
server-side validation
native validation
validation state
error identification
error suggestion
inline error
field-level error
form-level error
error summary
warning
success
focus management
error recovery
preserved input
fieldset
legend
choice group
radio group
checkbox group
input purpose
autocomplete
format guidance
character limit
character count
disabled
readonly
submission
confirmation
review step
error prevention
redundant entry
```

Rules:

- distinguish label from placeholder/hint;
- distinguish accessible name from visual label;
- distinguish validation from error communication;
- distinguish disabled from readonly;
- distinguish warning from validation error;
- distinguish field error from form-level summary;
- distinguish client-side feedback from authoritative server validation;
- preserve source-specific terminology.

---

# 10. OBSERVATION EXTRACTION

Target:

```text
30–42 observations
```

Hard maximum:

```text
50
```

Suggested distribution:

```text
S1 WCAG: 7–10
S2 WAI: 5–8
S3 GOV.UK: 6–9
S4 USWDS: 5–8
S5 Primer docs: 4–7
S6 Primer implementation: 4–8
```

Each observation must:

- remain `OBSERVED`;
- identify exact source/evidence location;
- preserve normative/reference/implementation class;
- identify context;
- identify confidence;
- identify limitations;
- preserve version context;
- avoid recommendation language in raw observations.

---

# 11. K4 — CROSS-SOURCE COMPARISON

`CROSS_SOURCE_COMPARISON.md` must compare at least:

## A. Labels versus placeholder/hint

Separate:

```text
visible label
accessible name
hint/caption
placeholder
example value
format instruction
```

Do not accept placeholder-only identification as a default form-label strategy without evidence.

## B. Required versus optional

Compare how sources communicate:

- required status;
- optional status;
- programmatic required state;
- instructions at form/field level.

Do not force one punctuation convention universally.

## C. Grouping

Compare:

- fieldset/legend;
- checkbox/radio groups;
- related questions;
- visual grouping versus semantic grouping.

## D. Validation timing

Distinguish:

```text
on input
on blur
on submit
server response
native browser constraint validation
```

No universal timing law unless evidence supports a bounded context.

## E. Error communication

Compare:

- inline error;
- field state;
- error summary;
- announcement;
- linking errors to controls;
- preserving field values;
- actionable wording.

## F. Focus after failure

Ask:

- when should focus remain on field?
- when should focus move to summary?
- when should summary be focusable?
- what is direct source guidance vs system convention?

Do not claim one universal focus destination.

## G. Error prevention

Distinguish WCAG 3.3.4's actual scope from broader product preference.

## H. Redundant entry

Preserve WCAG 3.3.7 scope and exceptions.

## I. Disabled / readonly / blocked submission

Analyze:

- when disabled controls are appropriate;
- when disabled submission hides why progress is blocked;
- whether recoverable guidance exists;
- source support.

Do not manufacture an anti-disabled-button law without evidence.

## J. Responsive form integrity

Apply W04/W05 knowledge:

- required labels/errors/actions remain reachable;
- error summaries do not destroy task orientation;
- responsive movement preserves meaningful order.

---

# 12. FORM_MODEL_ANALYSIS.md

This file must answer, with evidence boundaries:

1. What makes a field identifiable?
2. What belongs in a label?
3. What belongs in hint/instruction text?
4. When are examples useful?
5. When should related controls be grouped?
6. How should required/optional state be conveyed?
7. How should choice groups expose labels/instructions?
8. How should character limits be communicated?
9. How should disabled and readonly states differ?
10. How should responsive composition preserve form relationships?
11. What can visual styling communicate, and what requires programmatic semantics?
12. What must not rely on color alone?

No universal component library or CSS pattern.

---

# 13. VALIDATION_ERROR_RECOVERY_ANALYSIS.md

Answer:

1. How are errors identified?
2. What makes an error actionable?
3. When is an inline error sufficient?
4. When does an error summary add value?
5. How should summary links relate to invalid fields?
6. How should focus behave after failed submission?
7. How should entered data be preserved?
8. How should errors be announced programmatically?
9. When should validation happen?
10. How should server-side failures differ from field-constraint failures?
11. When does error prevention require review, confirmation, reversal, or correction?
12. How should redundant data entry be avoided?
13. What should happen when progress is blocked?
14. What should not be generalized from design-system-specific behavior?

Unresolved answers are valid.

---

# 14. FAILURE_MODE_ANALYSIS.md

Investigate hypotheses such as:

```text
PLACEHOLDER_AS_ONLY_LABEL
ERROR_BY_COLOR_ONLY
UNLINKED_ERROR_MESSAGE
ERROR_SUMMARY_WITHOUT_FIELD_ROUTE
ERROR_TEXT_WITHOUT_CORRECTION_GUIDANCE
LOST_USER_INPUT_AFTER_VALIDATION_FAILURE
FORM_GROUP_WITHOUT_GROUP_LABEL
REQUIRED_STATE_VISUAL_ONLY
DISABLED_SUBMIT_WITHOUT_RECOVERY_GUIDANCE
VALIDATION_TOO_EARLY_FOR_TASK_CONTEXT
VALIDATION_TOO_LATE_FOR_TASK_CONTEXT
SERVER_ERROR_PRESENTED_AS_FIELD_ERROR
DESTRUCTIVE_SUBMISSION_WITHOUT_RECOVERY
REDUNDANT_REENTRY_WITHOUT_NECESSITY
```

These are hypotheses only.

For each:

1. observable structure;
2. claimed harm;
3. direct source support;
4. inferred evidence;
5. legitimate counter-context;
6. counterexample;
7. candidate justification.

Do not create:

```text
"bad form UX"
```

as an anti-pattern without a specific mechanism.

---

# 15. K5 — CANDIDATE SYNTHESIS

Hard caps:

```text
pattern candidates: 0–3
anti-pattern candidates: 0–2
```

Zero is valid.

Possible pattern hypotheses MAY include:

```text
PERSISTENT_FIELD_IDENTIFICATION
ACTIONABLE_ERROR_LINKAGE
RECOVERABLE_VALIDATION_FAILURE
SEMANTIC_CHOICE_GROUPING
PRESERVED_INPUT_ERROR_RECOVERY
```

Possible anti-pattern hypotheses MAY include:

```text
PLACEHOLDER_ONLY_FIELD_IDENTIFICATION
ERROR_STATE_WITHOUT_TEXTUAL_IDENTIFICATION
UNRECOVERABLE_FORM_FAILURE
DISABLED_PROGRESS_WITHOUT_EXPLANATION
UNLABELED_CHOICE_GROUP
```

These are only hypothesis names.

Every candidate must:

- link non-empty source IDs;
- link non-empty observation IDs;
- state applicability;
- state non-applicability;
- include counterexamples;
- state evidence strength;
- distinguish direct from inferred evidence;
- include accessibility/responsive implications;
- remain `CANDIDATE`;
- contain no acceptance metadata.

---

# 16. PRIOR KNOWLEDGE INTEGRITY

W06 must prove all prior W02–W05 knowledge records remain unchanged.

At minimum verify:

```text
W02-P01 / W02-A01 / W02-P02
W03-P01 / W03-P02 / W03-P03 / W03-A01
W04-P01 / W04-P02 / W04-P03 / W04-A01 / W04-A02
W05-P01 / W05-P02 / W05-P03 / W05-A01 / W05-A02
```

If W06 evidence conflicts with prior accepted knowledge:

```text
REPORT CONTRADICTION
DO NOT MODIFY PRIOR RECORD
RETURN TO MAINTAINER
```

---

# 17. PINNED PRIMER IMPLEMENTATION BOUNDARY

Use exactly:

```text
primer/react@7f5303d803986887187d86dcebaeda22a4dc6823
```

Implementation evidence may establish:

- generated IDs and label associations;
- `aria-describedby` wiring;
- `aria-invalid` behavior;
- required/disabled prop propagation;
- validation message relationships;
- character counter implementation;
- choice-group implementation;
- native input/select semantics;
- test intent.

Implementation evidence does NOT establish:

- test PASS;
- browser behavior;
- assistive-technology output;
- correct use by callers;
- usability;
- universal validation architecture;
- current Primer main behavior.

---

# 18. K6 — MAINTAINER REVIEW PACKET

`review/MAINTAINER_REVIEW_PACKET.md` must include:

```text
RUN ID
EXACT LUCIEN SOURCE
SOURCE SET
QUALIFICATION SUMMARY
VOCABULARY SUMMARY
OBSERVATION COUNT

NORMATIVE FORM REQUIREMENTS
WAI EXPLANATORY GUIDANCE
DESIGN-SYSTEM FORM GUIDANCE
PINNED IMPLEMENTATION FINDINGS

LABEL / INSTRUCTION FINDINGS
REQUIRED / OPTIONAL FINDINGS
GROUPING FINDINGS
VALIDATION-TIMING FINDINGS
ERROR-COMMUNICATION FINDINGS
ERROR-SUMMARY FINDINGS
FOCUS / ANNOUNCEMENT FINDINGS
ERROR-PREVENTION FINDINGS
REDUNDANT-ENTRY FINDINGS
DISABLED / READONLY FINDINGS
RESPONSIVE FORM FINDINGS

FAILURE-MODE HYPOTHESES
SUPPORTED
WEAK / INSUFFICIENT
REJECTED / MISFRAMED

CONTRADICTIONS
COUNTEREXAMPLES
VERSION LIMITS
LICENSE / STORAGE LIMITS

PATTERN CANDIDATES
ANTI-PATTERN CANDIDATES

WHAT MUST NOT BE GENERALIZED

PRIOR KNOWLEDGE INTEGRITY

UNRESOLVED QUESTIONS
WORKER RECOMMENDATION
```

No K7 promotion.

---

# 19. K7 — PROHIBITED

The worker MUST NOT:

- mark any W06 candidate ACCEPTED;
- modify accepted/deferred W02–W05 records;
- promote W02-P02;
- promote W03-A01;
- select React Hook Form/Formik/Zod/Yup or any form/schema library;
- declare universal validation timing;
- declare universal error-summary requirement;
- declare universal disabled-button prohibition;
- create backend validation architecture;
- begin W07.

---

# 20. REGISTRY MUTATION

`.forge/knowledge/registry/sources.json` may add only qualified W06 source records.

Expected behavior:

- WCAG identity likely reused;
- WAI forms family likely new/materially distinct;
- GOV.UK forms family materially distinct from earlier navigation/layout acquisitions;
- USWDS forms family materially distinct;
- Primer forms docs materially distinct;
- pinned Primer repository identity may be reused only if existing exact-SHA record is broad enough; otherwise create a clearly scoped record without ambiguous duplication.

Explain every reuse or append decision.

Registry membership means qualified source only.

---

# 21. LICENSE / STORAGE LAW

Store only:

- metadata;
- canonical URLs;
- bounded summaries;
- observations;
- exact SHAs;
- source paths.

Do not store:

- complete external docs;
- screenshots;
- design assets;
- large source dumps;
- proprietary templates.

Unknown license remains reference-only.

---

# 22. NEGATIVE CHECKS

Before return, confirm:

```text
NO frontend application created
NO package.json created
NO dependency installed
NO form/schema library selected
NO backend validation architecture created
NO universal validation-timing law created
NO universal error-summary law created
NO universal disabled-button law created
NO seventh source family added
NO mass crawl performed
NO external repository mutated
NO Primer SHA substituted
NO test PASS fabricated
NO runtime/browser result fabricated
NO screen-reader/AT result fabricated
NO user-study result fabricated
NO W06 candidate marked ACCEPTED
NO W02-P02 promotion
NO W03-A01 promotion
NO accepted W02–W05 record modified
NO W07 execution
NO main merge
```

---

# 23. VALIDATION

Worker SHOULD validate:

- exact ancestry;
- canonical main unchanged;
- worker delta scope;
- JSON parsing;
- source-record structural conformance;
- observation structural conformance;
- candidate structural conformance;
- source-ID linkage;
- observation-ID linkage;
- duplicate IDs;
- registry scope;
- all W06 candidates remain CANDIDATE;
- all prior accepted/deferred knowledge remains byte-for-byte unchanged.

Expected application evidence:

```text
APPLICATION BUILD: NOT RUN / NOT APPLICABLE
APPLICATION TYPECHECK: NOT RUN / NOT APPLICABLE
APPLICATION TESTS: NOT RUN / NOT APPLICABLE
FRONTEND RUNTIME: NOT RUN / NOT APPLICABLE
BROWSER FORM TESTING: NOT RUN
KEYBOARD FORM TESTING: NOT RUN
SCREEN-READER / AT TESTING: NOT RUN
USER FORM USABILITY TESTING: NOT RUN
SERVER VALIDATION INTEGRATION TESTING: NOT RUN
```

Tests read != tests executed.

Do not install dependencies merely to inflate validation.

---

# 24. REQUIRED REPORT

Return exactly:

```text
KIRION FORGE — LUCIEN
W06 FORMS, VALIDATION & ERROR-RECOVERY INTELLIGENCE REPORT

1. LIVE SOURCE VERIFICATION
2. RESEARCH QUESTION
3. FILES CREATED
4. FILES MODIFIED

5. SOURCE CORPUS
S1
S2
S3
S4
S5
S6

6. SOURCE QUALIFICATION RESULTS
7. LICENSE / STORAGE RESULTS

8. VOCABULARY RESULTS
9. OBSERVATION COUNT
10. OBSERVATION SUMMARY BY SOURCE

11. NORMATIVE FORM REQUIREMENTS
12. LABEL / INSTRUCTION FINDINGS
13. REQUIRED / OPTIONAL FINDINGS
14. GROUPING FINDINGS
15. VALIDATION-TIMING FINDINGS
16. ERROR-COMMUNICATION FINDINGS
17. ERROR-SUMMARY FINDINGS
18. FOCUS / ANNOUNCEMENT FINDINGS
19. ERROR-PREVENTION FINDINGS
20. REDUNDANT-ENTRY FINDINGS
21. DISABLED / READONLY FINDINGS
22. RESPONSIVE FORM FINDINGS

23. FAILURE-MODE ANALYSIS
24. CONTRADICTIONS / COUNTEREXAMPLES

25. PATTERN CANDIDATES
26. ANTI-PATTERN CANDIDATES

27. PRIOR KNOWLEDGE INTEGRITY
28. REGISTRY MUTATION
29. NEGATIVE CHECKS

30. VALIDATION ACTUALLY EXECUTED
31. VALIDATION NOT EXECUTED / NOT APPLICABLE

32. UNRESOLVED ITEMS
33. COMMITS CREATED
34. FINAL BRANCH
35. EXACT FINAL SHA

36. DISPOSITION RECOMMENDATION
```

Disposition exactly one:

```text
READY_FOR_MAINTAINER_REVIEW
REWORK_REQUIRED
BLOCKED
SOURCE_DRIFT
```

Then STOP.

Do not begin W07.
Do not promote candidates.
Do not merge to main.
Do not self-accept.

Return control to KIRION Forge Maintainer.


---

# HISTORICAL STATUS

```text
COMPLETED
MAINTAINER DISPOSITION: ACCEPT
REVIEWED WORKER CANDIDATE: 6b3fcde1bc12ecd6904dc4bbb1f2f91ff29ed54d
ACCEPTANCE ISSUE: #13

K7:
W06-P01 — ACCEPTED
W06-P02 — ACCEPTED
W06-P03 — ACCEPTED
W06-A01 — ACCEPTED
W06-A02 — ACCEPTED
```

This handoff is historical execution evidence.

It is no longer active authority and MUST NOT be executed again.
