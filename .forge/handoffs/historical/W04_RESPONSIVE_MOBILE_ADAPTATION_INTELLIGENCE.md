# KIRION FORGE: MAINTAINER
# LUCIEN W04 — RESPONSIVE LAYOUT & MOBILE ADAPTATION INTELLIGENCE
# REFLOW / CONTENT PRIORITY / VIEWPORT ADAPTATION / SAFE REDUCTION

## AUTHORITY CLASS

Bounded KIRION Forge Maintainer handoff.

W04 deepens Lucien's accepted W03 composition knowledge into responsive-layout and mobile-adaptation intelligence.

This is NOT:

- frontend application implementation;
- framework selection;
- breakpoint standardization;
- permission to adopt a design system;
- permission to assume "mobile = phone";
- permission to hide content merely because a viewport is narrow;
- mass web crawling;
- runtime conformance testing;
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

Canonical accepted source before W04:

```text
main@c9acd923b11d8695ab5ba41569599fc9165f5b97
```

W04 branch:

```text
forge/w04-responsive-mobile-adaptation-intelligence
```

Before any mutation:

1. resolve live `main`;
2. resolve W04 branch head;
3. confirm the W04 branch descends from the exact canonical source above;
4. confirm W00, W01, W02, and W03 are accepted;
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

Read and obey all current Forge authority plus:

```text
W02-P01 — Contextual dominant primary action
ACCEPTED / MEDIUM

W02-A01 — Competing dominant primary controls
ACCEPTED / MEDIUM

W03-P01 — Semantic and visual region alignment
ACCEPTED / MEDIUM

W03-P02 — Purpose-bounded reading width
ACCEPTED / MEDIUM

W03-P03 — Content-first responsive composition
ACCEPTED / MEDIUM
```

Deferred candidates remain deferred:

```text
W02-P02 — Focus-preserving asynchronous button feedback
CANDIDATE / DEFERRED

W03-A01 — Undifferentiated content priority
CANDIDATE / DEFERRED
```

W04 may cite these records.

W04 may not change their status.

---

# 2. HUMAN OBJECTIVE

Lucien must learn how strong frontend systems adapt to constrained viewports and mobile contexts without:

- preserving desktop geometry blindly;
- hiding critical tasks;
- breaking semantic order;
- causing unnecessary horizontal scrolling;
- overfitting to named device models;
- replacing information architecture with arbitrary collapse;
- making dense professional interfaces unusably sparse;
- treating every narrow screen as a simplified consumer app.

Lucien must learn the vocabulary behind:

```text
responsive layout
adaptive layout
fluid layout
reflow
viewport
breakpoint
content priority
source order
visual order
stacking
wrapping
collapsing
disclosure
overflow
horizontal scrolling
intrinsically two-dimensional content
responsive typography
touch target
orientation
navigation adaptation
pane movement
safe hiding
density reduction
responsive region order
```

The goal is not:

```text
"make it mobile friendly"
```

The goal is:

```text
identify what must remain available,
what may move,
what may collapse,
what may reflow,
what may scroll,
and what must preserve semantic/task order,
with evidence and context.
```

---

# 3. W04 RESEARCH QUESTION

Primary question:

> **How should frontend layouts adapt across narrow and wide viewports while preserving task priority, semantic relationships, critical controls, readability, and legitimate high-density workflows?**

Operational sub-questions:

1. What does WCAG actually require around orientation, reflow, zoom-related layout adaptation, target size, and information relationships?
2. How do official design systems decide when to stack, wrap, move, collapse, or retain side-by-side regions?
3. When is horizontal scrolling acceptable because content is intrinsically two-dimensional?
4. When does hiding or collapsing secondary content become harmful?
5. How should source/semantic order relate to visual reordering?
6. What should breakpoints represent: named devices, content constraints, or system-defined viewport ranges?
7. How should responsive typography and reading width change without becoming arbitrary?
8. How should action hierarchy survive narrow screens?
9. How should dense professional/workbench interfaces adapt without being falsely "simplified"?
10. Which recurring mobile/responsive failure modes can be supported strongly enough to become candidates?

Allowed domains:

```text
RESPONSIVE_DESIGN
LAYOUT
INFORMATION_ARCHITECTURE
SEMANTIC_HTML
ACCESSIBILITY
TYPOGRAPHY
SPACING
INTERACTION
NAVIGATION
COMPONENT_ARCHITECTURE
VISUAL_HIERARCHY
```

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

Relevant areas may include:

```text
1.3.1 Info and Relationships
1.3.2 Meaningful Sequence
1.3.4 Orientation
1.4.4 Resize Text
1.4.10 Reflow
1.4.12 Text Spacing
2.4.3 Focus Order
2.5.8 Target Size (Minimum)
```

Rules:

- use normative WCAG wording only for actual success criteria;
- preserve exceptions;
- do not infer framework, breakpoint, or mobile-navigation prescriptions.

## S2 — W3C WAI Mobile Accessibility / Responsive Guidance

Canonical family may include:

```text
https://www.w3.org/WAI/standards-guidelines/mobile/
https://www.w3.org/WAI/tips/designing/
```

Candidate authority:

```text
OFFICIAL_REFERENCE
```

Investigate:

- application of accessibility guidance to mobile contexts;
- viewport adaptation;
- touch/mobile considerations;
- interaction independence from specific device assumptions;
- explanatory relationship to WCAG.

Do NOT relabel explanatory WAI guidance as new normative WCAG criteria.

## S3 — GOV.UK Design System Layout / Grid / Responsive Guidance

Canonical family:

```text
https://design-system.service.gov.uk/styles/layout/
https://design-system.service.gov.uk/styles/type-scale/
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- small-screen-first design;
- single-column starting point;
- grid adaptation;
- reading width;
- wider-content exceptions;
- responsive type scale;
- device-independent screen-size reasoning.

Do not universalize GOV.UK service patterns.

## S4 — IBM Carbon 2x Grid / Responsive Layout Guidance

Canonical family:

```text
https://www.carbondesignsystem.com/building-blocks/foundations/2x-grid/overview
https://www.carbondesignsystem.com/building-blocks/foundations/2x-grid/guidelines
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- responsive grid behavior;
- style models;
- density;
- full-width/high-density interfaces;
- breakpoint or column logic where documented;
- fit-for-purpose layout choices.

If direct retrieval remains limited, preserve that limitation and lower confidence.

## S5 — GitHub Primer Responsive Foundations / PageLayout

Canonical family may include:

```text
https://primer.style/product/getting-started/foundations/layout/
https://primer.style/product/components/page-layout/
https://primer.style/product/components/page-layout/accessibility/
https://primer.style/product/getting-started/foundations/typography/
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- viewport ranges vs breakpoints;
- simplifying multi-column layouts;
- region movement;
- responsive type/layout;
- page/pane behavior;
- hiding/collapsing guidance;
- accessibility expectations.

Do not assume live docs equal the pinned implementation snapshot.

## S6 — Primer React Responsive/PageLayout implementation

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

Inspect only directly relevant responsive-layout implementation, including where useful:

```text
packages/react/src/PageLayout/PageLayout.tsx
packages/react/src/PageLayout/PageLayout.module.css
packages/react/src/PageLayout/PageLayout.test.tsx
packages/react/src/PageLayout/PageLayout.responsive.stories.tsx
packages/react/src/PageLayout/usePaneWidth.ts
packages/react/src/PageLayout/DragHandle.tsx
packages/react/src/hooks/useResponsiveValue.ts
packages/react/src/internal/utils/getResponsiveAttributes.ts
```

You may inspect directly referenced responsive viewport utilities needed to understand these files.

Do not roam unrelated components.

Do not substitute newer main.

Do not mutate `primer/react`.

Tests/stories read != tests executed.

---

# 5. SOURCE LIMIT

Independent source families:

```text
EXACTLY 6
```

Do NOT add during W04:

- Material;
- Apple HIG;
- Bootstrap;
- Tailwind;
- Foundation;
- Chakra;
- Radix;
- Shopify Polaris;
- USWDS;
- random blogs;
- Stack Overflow;
- Reddit;
- Dribbble;
- Behance;
- Mobbin;
- device-market-share articles.

Those may be separate future lanes.

---

# 6. W04 OUTPUT SURFACE

W04 may create only:

```text
.forge/knowledge/runs/W04_RESPONSIVE_MOBILE_ADAPTATION/
├── REQUEST.md
├── SOURCE_QUALIFICATION.md
├── VOCABULARY.md
├── OBSERVATION_INDEX.md
├── CROSS_SOURCE_COMPARISON.md
├── MOBILE_ADAPTATION_ANALYSIS.md
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

W04 may modify:

```text
.forge/knowledge/registry/sources.json
.forge/SSOT_CURRENT.md
.forge/WORK_LEDGER.md
README.md
```

only as required for accurate W04 state.

Do NOT modify accepted W01 schemas/protocols.

If the accepted schema cannot represent valid W04 knowledge:

```text
SCHEMA_BLOCK
STOP
RETURN TO MAINTAINER
```

---

# 7. K0 — REQUEST RECORD

`REQUEST.md` must record:

- run ID;
- canonical Lucien source;
- branch;
- research question;
- human objective;
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
- preserve version/date/SHA;
- preserve authority class;
- preserve license/reuse status;
- preserve retrieval limitations;
- reuse existing W02/W03 source IDs where the source identity is materially the same;
- create a new source record only where scope/target is materially distinct.

No ambiguous duplicate source records.

Source qualification != accepted claim.

---

# 9. VOCABULARY REQUIREMENT

Create:

```text
VOCABULARY.md
```

Define evidence-linked working terms including at minimum:

```text
responsive design
adaptive design
fluid layout
viewport
breakpoint
viewport range
reflow
stacking
wrapping
collapse
disclosure
overflow
horizontal scroll
intrinsically two-dimensional content
source order
visual order
focus order
content priority
responsive region order
responsive typography
responsive density
safe hiding
critical content
critical control
touch target
orientation
pane relocation
progressive reduction
```

Rules:

- distinguish terms that sources actually define from working analytical definitions;
- do not claim universal breakpoint values;
- do not equate breakpoint with device model;
- do not claim "mobile-first" means "mobile-only";
- preserve source-specific terminology.

---

# 10. OBSERVATION EXTRACTION

Target:

```text
24–36 observations
```

Hard maximum:

```text
42
```

Suggested distribution:

```text
S1 WCAG: 5–8
S2 WAI: 3–5
S3 GOV.UK: 4–6
S4 Carbon: 3–5
S5 Primer docs: 5–7
S6 Primer implementation: 4–7
```

Each record must:

- remain status `OBSERVED`;
- identify exact source/evidence location;
- separate normative requirement from design advice;
- identify context;
- identify limitations;
- preserve version context;
- avoid recommendation language in raw observations.

---

# 11. K4 — CROSS-SOURCE COMPARISON

`CROSS_SOURCE_COMPARISON.md` must compare at least:

## A. Reflow vs responsive preference

Separate:

```text
WCAG-required reflow constraints
!=
system-specific responsive layout recommendations
```

## B. Content priority

Compare how sources treat:

- main content;
- navigation;
- secondary panes;
- supporting metadata;
- actions;
- task-critical controls.

## C. Source order vs visual order

Analyze evidence around:

- semantic/source sequence;
- focus order;
- visual rearrangement;
- responsive region movement.

Do NOT assert that any CSS visual reorder is automatically inaccessible.

## D. Hide / collapse / move

Ask:

- when is hiding allowed?
- when should content move rather than disappear?
- when should disclosure be used?
- what must stay recoverable?
- which sources actually support the conclusion?

## E. Breakpoints

Distinguish:

```text
device-name breakpoint
system breakpoint
content-driven threshold
viewport range
implementation constant
```

No universal breakpoint table.

## F. Density

Compare how responsive systems treat:

- dense professional interfaces;
- readable document/service pages;
- multi-panel workbenches;
- data that genuinely requires two dimensions.

## G. Touch / target considerations

Keep target-size requirements and touch usability guidance distinct.

## H. Orientation

Separate WCAG orientation requirement from product preference.

---

# 12. MOBILE_ADAPTATION_ANALYSIS.md

This file must answer, with evidence boundaries:

1. What must remain available on narrow screens?
2. What may move?
3. What may stack?
4. What may wrap?
5. What may collapse behind disclosure?
6. What may scroll horizontally?
7. What may be hidden?
8. When is preserving desktop geometry harmful?
9. When is aggressive simplification harmful?
10. What happens to action hierarchy on narrow screens?
11. How should reading width/type scale adapt?
12. How should panes/sidebars change?
13. What must be checked when visual order changes?

The answer may contain unresolved cases.

Do not force universal rules.

---

# 13. FAILURE_MODE_ANALYSIS.md

Investigate hypotheses such as:

```text
DESKTOP_GEOMETRY_PRESERVATION
MOBILE_AS_TRUNCATED_DESKTOP
CRITICAL_CONTROL_DISAPPEARANCE
VISUAL_ORDER_SEMANTIC_ORDER_DIVERGENCE
DEVICE_NAME_BREAKPOINT_OVERFITTING
HORIZONTAL_OVERFLOW_WITHOUT_TASK_JUSTIFICATION
OVER_COLLAPSED_INFORMATION_ARCHITECTURE
DENSITY_DESTRUCTION_IN_PROFESSIONAL_TOOLS
TOUCH_TARGET_COMPRESSION
RESPONSIVE_HIERARCHY_LOSS
```

These are hypotheses only.

For each:

1. observable structure;
2. claimed harm;
3. source support;
4. legitimate counter-context;
5. direct vs inferred evidence;
6. counterexample;
7. whether candidate synthesis is justified.

Do not create "mobile slop" as a blanket anti-pattern.

---

# 14. K5 — CANDIDATE SYNTHESIS

Hard caps:

```text
pattern candidates: 0–3
anti-pattern candidates: 0–2
```

Zero is valid.

Possible pattern hypotheses MAY include:

```text
CONTENT_PRIORITY_PRESERVING_REFLOW
RECOVERABLE_RESPONSIVE_REDUCTION
SOURCE_ORDER_AWARE_VISUAL_REORDERING
TASK_JUSTIFIED_HORIZONTAL_OVERFLOW
VIEWPORT_RANGE_OVER_DEVICE_MODEL
```

Possible anti-pattern hypotheses MAY include:

```text
CRITICAL_CONTROL_DISAPPEARANCE
DESKTOP_GEOMETRY_PRESERVATION
OVER_COLLAPSED_INFORMATION_ARCHITECTURE
UNJUSTIFIED_HORIZONTAL_OVERFLOW
```

These are not accepted merely because listed here.

Every candidate must:

- link source IDs;
- link observation IDs;
- state applicability;
- state non-applicability;
- preserve counterexamples;
- state confidence;
- distinguish direct from inferred evidence;
- include accessibility implications;
- remain `CANDIDATE`;
- contain no Maintainer acceptance metadata.

---

# 15. PRIOR KNOWLEDGE INTEGRITY

W04 must prove the following records remain unchanged:

```text
W02-P01 — ACCEPTED
W02-A01 — ACCEPTED
W02-P02 — CANDIDATE

W03-P01 — ACCEPTED
W03-P02 — ACCEPTED
W03-P03 — ACCEPTED
W03-A01 — CANDIDATE
```

If a W04 finding appears to contradict accepted prior knowledge:

```text
REPORT CONTRADICTION
DO NOT MODIFY PRIOR RECORD
RETURN THE CONFLICT TO MAINTAINER
```

---

# 16. PINNED PRIMER IMPLEMENTATION BOUNDARY

Use exactly:

```text
primer/react@7f5303d803986887187d86dcebaeda22a4dc6823
```

Implementation evidence may establish:

- responsive attribute encoding;
- viewport range definitions;
- region order mechanics;
- hiding behavior;
- pane width constraints;
- breakpoint constants;
- test/story intent;
- resize mechanics.

Implementation evidence does NOT establish:

- runtime correctness;
- accessibility conformance;
- usability;
- current Primer main behavior;
- universal breakpoint values.

---

# 17. K6 — MAINTAINER REVIEW PACKET

`review/MAINTAINER_REVIEW_PACKET.md` must include:

```text
RUN ID
EXACT LUCIEN SOURCE
SOURCE SET
QUALIFICATION SUMMARY
VOCABULARY SUMMARY
OBSERVATION COUNT

NORMATIVE RESPONSIVE REQUIREMENTS
DESIGN-SYSTEM RESPONSIVE GUIDANCE
PINNED IMPLEMENTATION FINDINGS

REFLOW FINDINGS
CONTENT-PRIORITY FINDINGS
SOURCE/VISUAL/FOCUS ORDER FINDINGS
HIDE/COLLAPSE/MOVE FINDINGS
BREAKPOINT FINDINGS
DENSITY FINDINGS
TOUCH/TARGET FINDINGS
ORIENTATION FINDINGS

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

# 18. K7 — PROHIBITED

The worker MUST NOT:

- mark any W04 candidate ACCEPTED;
- modify accepted W02/W03 records;
- promote W02-P02;
- promote W03-A01;
- declare universal breakpoint values;
- declare universal mobile layouts;
- select a framework;
- begin W05.

---

# 19. REGISTRY MUTATION

The registry may add only qualified W04 source records.

Reuse existing source IDs where identity is materially unchanged.

Do not clone WCAG/GOV.UK/Carbon/Primer records merely because W04 studies a new question.

If a new sub-source is materially distinct, explain why it requires a new record.

Registry membership means qualified source only.

---

# 20. LICENSE / STORAGE LAW

Store:

- metadata;
- URLs;
- bounded summaries;
- observations;
- SHAs;
- source paths.

Do not store:

- full external docs;
- copied design systems;
- screenshots;
- templates;
- large source dumps.

Unknown license remains reference-only.

---

# 21. NEGATIVE CHECKS

Before return, confirm:

```text
NO frontend application created
NO package.json created
NO dependency installed
NO framework selected
NO styling stack selected
NO component library adopted
NO universal breakpoint table created
NO device-name breakpoint law created
NO mass crawl performed
NO seventh source family added
NO external repository mutated
NO Primer SHA substituted
NO runtime/browser result fabricated
NO accessibility conformance fabricated
NO W04 candidate marked ACCEPTED
NO W02-P02 promotion
NO W03-A01 promotion
NO accepted W02/W03 knowledge modified
NO W05 execution
NO main merge
```

---

# 22. VALIDATION

Worker SHOULD validate:

- exact ancestry;
- canonical main unchanged;
- worker delta scope;
- JSON parsing;
- source record structural conformance;
- observation structural conformance;
- candidate structural conformance;
- source-ID integrity;
- observation-ID integrity;
- duplicate IDs;
- registry scope;
- all W04 candidates remain CANDIDATE;
- all accepted W02/W03 records byte-for-byte unchanged;
- deferred prior candidates remain CANDIDATE.

Expected application evidence:

```text
APPLICATION BUILD: NOT RUN / NOT APPLICABLE
APPLICATION TYPECHECK: NOT RUN / NOT APPLICABLE
APPLICATION TESTS: NOT RUN / NOT APPLICABLE
FRONTEND RUNTIME: NOT RUN / NOT APPLICABLE
BROWSER RESPONSIVE TESTING: NOT RUN
DEVICE TESTING: NOT RUN
SCREEN-READER / AT TESTING: NOT RUN
```

Do not install dependencies merely to inflate validation.

---

# 23. REQUIRED REPORT

Return exactly:

```text
KIRION FORGE — LUCIEN
W04 RESPONSIVE LAYOUT & MOBILE ADAPTATION INTELLIGENCE REPORT

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

11. NORMATIVE RESPONSIVE REQUIREMENTS
12. REFLOW FINDINGS
13. CONTENT-PRIORITY FINDINGS
14. SOURCE / VISUAL / FOCUS ORDER FINDINGS
15. HIDE / COLLAPSE / MOVE FINDINGS
16. BREAKPOINT FINDINGS
17. DENSITY FINDINGS
18. TOUCH / TARGET FINDINGS
19. ORIENTATION FINDINGS

20. FAILURE-MODE ANALYSIS
21. CONTRADICTIONS / COUNTEREXAMPLES

22. PATTERN CANDIDATES
23. ANTI-PATTERN CANDIDATES

24. PRIOR KNOWLEDGE INTEGRITY
25. REGISTRY MUTATION
26. NEGATIVE CHECKS

27. VALIDATION ACTUALLY EXECUTED
28. VALIDATION NOT EXECUTED / NOT APPLICABLE

29. UNRESOLVED ITEMS
30. COMMITS CREATED
31. FINAL BRANCH
32. EXACT FINAL SHA

33. DISPOSITION RECOMMENDATION
```

Disposition exactly one:

```text
READY_FOR_MAINTAINER_REVIEW
REWORK_REQUIRED
BLOCKED
SOURCE_DRIFT
```

Then STOP.

Do not begin W05.
Do not promote candidates.
Do not merge to main.
Do not self-accept.

Return control to KIRION Forge Maintainer.


---

# HISTORICAL STATUS

```text
COMPLETED
MAINTAINER DISPOSITION: ACCEPT
REVIEWED WORKER CANDIDATE: 9aef7979d2c247f555e6b89d481270a4de19d4a1
ACCEPTANCE ISSUE: #9

K7:
W04-P01 — ACCEPTED
W04-P02 — ACCEPTED
W04-P03 — ACCEPTED
W04-A01 — ACCEPTED
W04-A02 — ACCEPTED
```

This handoff is historical execution evidence.

It is no longer active authority and MUST NOT be executed again.
