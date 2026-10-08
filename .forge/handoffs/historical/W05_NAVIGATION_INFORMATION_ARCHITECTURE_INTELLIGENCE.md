# KIRION FORGE: MAINTAINER
# LUCIEN W05 — NAVIGATION & INFORMATION ARCHITECTURE INTELLIGENCE
# ORIENTATION / HIERARCHY / LOCATION / GLOBAL-LOCAL NAVIGATION / DISCOVERY PATHS

## AUTHORITY CLASS

Bounded KIRION Forge Maintainer handoff.

W05 extends Lucien's accepted composition and responsive knowledge into navigation and information-architecture intelligence.

This is NOT:

- frontend application implementation;
- router/framework selection;
- permission to adopt a navigation library;
- permission to define one universal site map;
- permission to treat tabs, breadcrumbs, menus, sidebars, and links as interchangeable;
- permission to treat organization charts as user information architecture;
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

Canonical accepted source before W05:

```text
main@5746b9412aa10333e7bc86ea54897f8be6b63267
```

W05 branch:

```text
forge/w05-navigation-information-architecture-intelligence
```

Before any mutation:

1. resolve live `main`;
2. resolve W05 branch head;
3. confirm W05 branch descends from the exact canonical source above;
4. confirm W00–W04 are accepted;
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

Read and obey all current Forge authority plus accepted knowledge:

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

W04-P01 — Recoverable responsive reduction
ACCEPTED / MEDIUM

W04-P02 — Meaningful source and focus order through responsive relocation
ACCEPTED / MEDIUM

W04-P03 — Task-justified horizontal overflow
ACCEPTED / MEDIUM

W04-A01 — Unrecoverable task-critical control disappearance
ACCEPTED / MEDIUM

W04-A02 — Unjustified horizontal overflow for ordinary content
ACCEPTED / MEDIUM
```

Deferred knowledge remains deferred:

```text
W02-P02 — CANDIDATE / DEFERRED
W03-A01 — CANDIDATE / DEFERRED
```

W05 may cite these records.

W05 may not alter their status.

---

# 2. HUMAN OBJECTIVE

Lucien must learn how users understand:

- where they are;
- where they can go;
- what belongs together;
- what level of a hierarchy they are viewing;
- which navigation is global versus local;
- which controls navigate versus act;
- how current location is communicated;
- how deep hierarchies are represented;
- when breadcrumbs, side navigation, tabs, headers, menus, and links are appropriate;
- how navigation adapts responsively without destroying orientation;
- how users can locate content through more than one valid path when required.

Lucien must learn the vocabulary behind:

```text
information architecture
navigation architecture
global navigation
primary navigation
secondary navigation
local navigation
contextual navigation
utility navigation
hierarchy
taxonomy
parent
child
sibling
ancestor
current location
active/current state
breadcrumb
side navigation
header navigation
tabbed navigation
navigation landmark
skip navigation
menu
application menu
site navigation
navigation depth
navigation breadth
wayfinding
orientation
discovery path
multiple ways
labeling
route
URL-backed view
hierarchical relationship
linear process
task flow
```

The goal is not:

```text
"put a navbar here"
```

The goal is:

```text
choose a navigation mechanism because the information relationship,
task relationship, hierarchy, and user orientation needs justify it.
```

---

# 3. W05 RESEARCH QUESTION

Primary question:

> **How should frontend navigation and information architecture help users understand location, hierarchy, available destinations, and task context without creating confusing depth, redundant navigation, semantic misuse, or hidden paths?**

Operational sub-questions:

1. What does WCAG actually require around bypassing blocks, page titles, link purpose, multiple ways, headings/labels, focus order, consistent navigation, and consistent identification?
2. How should global, local, contextual, and utility navigation differ?
3. What is the difference between site navigation and application-menu semantics?
4. When are breadcrumbs useful, and when are they misleading or redundant?
5. When should tabs/UnderlineNav represent URL-backed related views versus in-place tab panels or stepped flows?
6. When is side navigation appropriate for hierarchy?
7. How should current location and active state be communicated visually and programmatically?
8. How should navigation labels relate to user tasks and content rather than internal organization?
9. How deep or broad can navigation become before the mechanism should change?
10. How should responsive reduction preserve orientation and access?
11. When does duplicate navigation help and when does it create confusion?
12. Which recurring IA/navigation failure modes are supported strongly enough to become candidates?

Allowed domains:

```text
INFORMATION_ARCHITECTURE
NAVIGATION
SEMANTIC_HTML
ACCESSIBILITY
FOCUS_MANAGEMENT
INTERACTION
CONTENT_DESIGN
RESPONSIVE_DESIGN
VISUAL_HIERARCHY
COMPONENT_ARCHITECTURE
```

Do not expand into search-ranking algorithms, backend routing, authorization, analytics, or product-domain taxonomy beyond what evidence supports.

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

Reuse existing qualified WCAG identity where appropriate.

Candidate authority:

```text
OFFICIAL_STANDARD
PRIMARY_NORMATIVE
```

Relevant success criteria may include:

```text
2.4.1 Bypass Blocks
2.4.2 Page Titled
2.4.3 Focus Order
2.4.4 Link Purpose (In Context)
2.4.5 Multiple Ways
2.4.6 Headings and Labels
2.4.8 Location
3.2.3 Consistent Navigation
3.2.4 Consistent Identification
4.1.2 Name, Role, Value
```

Rules:

- preserve conformance level and exceptions;
- distinguish AA from AAA;
- do not turn WCAG into a prescriptive sitemap;
- do not claim breadcrumbs, tabs, or side nav are universally required by WCAG.

## S2 — W3C WAI Menus / Page Structure Guidance

Canonical family may include:

```text
https://www.w3.org/WAI/tutorials/menus/
https://www.w3.org/WAI/tutorials/menus/structure/
https://www.w3.org/WAI/tutorials/menus/application-menus/
https://www.w3.org/WAI/tutorials/page-structure/regions/
https://www.w3.org/WAI/tutorials/page-structure/headings/
```

Candidate authority:

```text
ACCESSIBILITY_REFERENCE
OFFICIAL_REFERENCE
```

Investigate:

- semantic navigation structure;
- list-based navigation;
- navigation landmarks/labels;
- site navigation versus application menus;
- keyboard implications;
- page-region orientation.

Do NOT relabel tutorial guidance as normative WCAG success criteria.

## S3 — GOV.UK Navigation / Service Navigation Family

Canonical family may include:

```text
https://design-system.service.gov.uk/patterns/navigate-a-service/
https://design-system.service.gov.uk/components/service-navigation/
https://design-system.service.gov.uk/components/govuk-header/
https://design-system.service.gov.uk/components/breadcrumbs/
https://design-system.service.gov.uk/components/back-link/
https://design-system.service.gov.uk/components/tabs/
https://design-system.service.gov.uk/components/skip-link/
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- service-level navigation;
- page-specific versus service-wide navigation;
- breadcrumbs;
- back links;
- tabs;
- skip links;
- placement/order of navigation elements;
- responsive behavior where documented.

Do not universalize GOV.UK public-service conventions.

## S4 — U.S. Web Design System Navigation Family

Canonical family may include:

```text
https://designsystem.digital.gov/components/header/
https://designsystem.digital.gov/components/headers/basic/
https://designsystem.digital.gov/components/header/extended/
https://designsystem.digital.gov/components/side-navigation/
https://designsystem.digital.gov/components/breadcrumb/
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- primary navigation;
- basic versus extended header choices;
- side navigation and hierarchy;
- current-location state;
- breadcrumb orientation;
- navigation labels;
- user-task versus organization-structure guidance;
- user research caveats.

Do not treat USWDS component choices as universal product law.

## S5 — GitHub Primer Navigation Guidance

Canonical family may include:

```text
https://primer.style/product/ui-patterns/navigation/
https://primer.style/product/components/nav-list/
https://primer.style/product/components/breadcrumbs/
https://primer.style/product/components/breadcrumbs/guidelines/
https://primer.style/product/components/breadcrumbs/accessibility/
https://primer.style/product/components/underline-nav/
https://primer.style/product/components/underline-nav/guidelines/
https://primer.style/product/components/underline-nav/accessibility/
```

Candidate authority:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- NavList parent/detail navigation;
- current context;
- breadcrumbs for hierarchy;
- UnderlineNav for URL-backed related views;
- distinction from tab panels;
- navigation depth limits where documented;
- overflow;
- accessibility;
- `aria-current`;
- landmark naming;
- responsive behavior where documented.

Do not treat current live docs as identical to the pinned implementation snapshot.

## S6 — Primer React Navigation Implementation

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

Inspect only directly relevant navigation implementation, including where useful:

```text
packages/react/src/NavList/NavList.tsx
packages/react/src/NavList/NavList.module.css
packages/react/src/NavList/NavList.test.tsx

packages/react/src/UnderlineNav/UnderlineNav.tsx
packages/react/src/UnderlineNav/UnderlineNav.module.css
packages/react/src/UnderlineNav/UnderlineNav.test.tsx
packages/react/src/UnderlineNav/UnderlineNavItem.tsx

packages/react/src/Breadcrumbs/Breadcrumbs.tsx
packages/react/src/Breadcrumbs/Breadcrumbs.module.css
packages/react/src/Breadcrumbs/Breadcrumbs.test.tsx
```

Directly referenced utilities/components may be inspected only when needed to understand semantics, current-state handling, overflow, or keyboard behavior.

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

Do NOT add during W05:

- Material;
- Apple HIG;
- Carbon navigation;
- Shopify Polaris;
- Atlassian;
- Nielsen Norman Group;
- Baymard;
- random UX blogs;
- Reddit;
- Stack Overflow;
- Dribbble;
- Behance;
- Mobbin.

Those may be separately qualified in future lanes.

---

# 6. W05 OUTPUT SURFACE

W05 may create only:

```text
.forge/knowledge/runs/W05_NAVIGATION_INFORMATION_ARCHITECTURE/
├── REQUEST.md
├── SOURCE_QUALIFICATION.md
├── VOCABULARY.md
├── OBSERVATION_INDEX.md
├── CROSS_SOURCE_COMPARISON.md
├── NAVIGATION_MODEL_ANALYSIS.md
├── IA_HIERARCHY_ANALYSIS.md
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

W05 may modify:

```text
.forge/knowledge/registry/sources.json
.forge/SSOT_CURRENT.md
.forge/WORK_LEDGER.md
README.md
```

only as required for accurate W05 state.

Do NOT modify accepted W01 schemas/protocols.

If the accepted schema cannot represent valid W05 knowledge:

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
- preserve version/date/SHA where possible;
- preserve source type and authority weight;
- preserve license/reuse status;
- preserve retrieval limitations;
- reuse existing source IDs only where the underlying source identity is materially the same;
- create new records where the navigation target is materially distinct from earlier layout/button sources.

No ambiguous duplicate source records.

Source qualification != accepted navigation law.

---

# 9. VOCABULARY REQUIREMENT

Create:

```text
VOCABULARY.md
```

Define evidence-linked working terms including at minimum:

```text
information architecture
navigation architecture
global navigation
primary navigation
secondary navigation
local navigation
contextual navigation
utility navigation
navigation landmark
skip navigation
hierarchy
taxonomy
parent
child
sibling
ancestor
current location
current page
active state
breadcrumb
side navigation
header navigation
tabbed navigation
URL-backed view
tab panel
menu
site navigation
application menu
menubar
navigation depth
navigation breadth
wayfinding
orientation
discovery path
multiple ways
label
route
linear process
hierarchical relationship
task flow
```

Rules:

- distinguish source-defined terms from Lucien working definitions;
- distinguish navigation from action controls;
- distinguish hierarchical navigation from linear task progression;
- distinguish URL-backed navigation tabs from in-place tab panels;
- do not define every expandable list as a menu;
- preserve system-specific terminology.

---

# 10. OBSERVATION EXTRACTION

Target:

```text
28–40 observations
```

Hard maximum:

```text
48
```

Suggested distribution:

```text
S1 WCAG: 6–9
S2 WAI: 4–7
S3 GOV.UK: 5–8
S4 USWDS: 5–8
S5 Primer docs: 5–8
S6 Primer implementation: 4–8
```

Each observation must:

- remain `OBSERVED`;
- identify exact source/evidence location;
- identify context;
- identify confidence;
- identify limitation;
- preserve version context;
- separate normative criteria from system guidance;
- avoid recommendation language in raw observations.

---

# 11. K4 — CROSS-SOURCE COMPARISON

`CROSS_SOURCE_COMPARISON.md` must compare at least:

## A. Navigation versus action

Separate:

```text
go somewhere
change view / URL
perform action
expand local disclosure
run application command
```

Do not collapse buttons, links, tabs, navigation menus, and application menus into one category.

## B. Global versus local navigation

Compare:

- site-wide/global navigation;
- section/service navigation;
- local side navigation;
- contextual navigation;
- utility links.

Ask what relationship each mechanism communicates.

## C. Location awareness

Compare:

- active/current states;
- `aria-current`;
- breadcrumbs;
- page titles;
- headings;
- current section indication;
- navigation landmarks.

Do not claim one mechanism alone always provides sufficient orientation.

## D. Hierarchy

Compare:

- parent/child;
- sibling views;
- deep ancestry;
- side navigation depth;
- breadcrumbs;
- tab hierarchy;
- megamenu/header hierarchy.

Ask when the mechanism should change rather than adding more levels.

## E. Multiple ways / discoverability

Distinguish WCAG 2.4.5's actual scope and exceptions from broader UX preference.

Do not claim every page needs breadcrumbs + search + side nav.

## F. Breadcrumbs

Distinguish:

```text
hierarchical ancestry
!=
browser/history trail
!=
linear task steps
```

Compare GOV.UK, USWDS, and Primer usage.

## G. Tabs / UnderlineNav

Distinguish:

```text
URL-backed navigation between related views
!=
in-place tab panels
!=
stepper/wizard progression
```

Preserve system-specific differences.

## H. Menu semantics

Distinguish:

```text
ordinary site navigation
!=
ARIA/application menu behavior
```

Do not recommend application-menu roles merely because a nav has dropdowns.

## I. Labels

Compare:

- clear labels;
- task/user language;
- short navigation labels;
- relation to headings/page titles;
- jargon avoidance.

## J. Responsive navigation

Apply W04 accepted knowledge:

- preserve required routes;
- maintain orientation;
- do not hide the only path;
- assess source/focus order when navigation relocates.

---

# 12. NAVIGATION_MODEL_ANALYSIS.md

This file must answer, with evidence boundaries:

1. What should global navigation communicate?
2. What should local navigation communicate?
3. When should side navigation be used?
4. When should breadcrumbs be used?
5. When should breadcrumbs be omitted?
6. When should URL-backed tabs/UnderlineNav be used?
7. When should in-place tab panels be used instead?
8. When should a back link represent task flow rather than hierarchy?
9. When is a header/basic nav sufficient?
10. When does hierarchy warrant extended navigation/megamenu/side navigation?
11. How should current location be communicated?
12. What should happen when navigation exceeds available width?
13. How should responsive navigation preserve task-critical access?
14. What distinguishes navigation menus from application command menus?
15. How should multiple navigation landmarks be named?
16. What should not be inferred from visual highlighting alone?

The analysis may preserve unresolved cases.

No universal component prescription.

---

# 13. IA_HIERARCHY_ANALYSIS.md

Analyze:

- breadth versus depth;
- user-task language versus organizational structure;
- parent/child/sibling relationships;
- ancestry;
- current section;
- cross-links;
- hierarchical versus sequential relationships;
- navigation duplication;
- discoverability;
- service/site boundaries;
- URL-backed information structure.

Critical law:

Do NOT infer that one site's preferred depth count is a universal maximum.

If a design system says "1–3 levels" or similar, classify it as system guidance, not web law.

---

# 14. FAILURE_MODE_ANALYSIS.md

Investigate hypotheses such as:

```text
CURRENT_LOCATION_AMBIGUITY
NAVIGATION_ACTION_SEMANTIC_COLLAPSE
BREADCRUMB_AS_HISTORY_TRAIL
BREADCRUMB_AS_STEPPER
TAB_NAVIGATION_AS_LINEAR_WORKFLOW
DEEP_NAVIGATION_WITHOUT_ORIENTATION
DUPLICATIVE_NAVIGATION_WITHOUT_ROLE_DISTINCTION
ORGANIZATION_CHART_AS_USER_NAVIGATION
HIDDEN_PRIMARY_ROUTE_ON_RESPONSIVE_REDUCTION
APPLICATION_MENU_ROLE_OVERUSE
UNLABELED_MULTIPLE_NAV_LANDMARKS
ACTIVE_STATE_ONLY_BY_COLOR
```

These are hypotheses only.

For each:

1. observable structure;
2. claimed harm;
3. direct source support;
4. inferential support;
5. legitimate counter-context;
6. counterexample;
7. candidate justification.

Do not create:

```text
"bad IA"
```

as an anti-pattern without a concrete mechanism.

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
CURRENT_LOCATION_MULTI_CUE_ORIENTATION
HIERARCHY_MATCHED_NAVIGATION_MECHANISM
URL_BACKED_RELATED_VIEW_NAVIGATION
ROLE_DISTINCT_NAVIGATION_LANDMARKS
TASK_LANGUAGE_NAVIGATION_LABELING
```

Possible anti-pattern hypotheses MAY include:

```text
BREADCRUMB_RELATIONSHIP_CONFUSION
NAVIGATION_ACTION_SEMANTIC_COLLAPSE
UNRECOVERABLE_RESPONSIVE_NAVIGATION_LOSS
DEEP_HIERARCHY_WITHOUT_LOCATION_CUES
ORGANIZATION_STRUCTURE_NAVIGATION
```

These are hypothesis names only.

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

W05 must prove these prior records remain unchanged:

```text
W02-P01 — ACCEPTED
W02-A01 — ACCEPTED
W02-P02 — CANDIDATE

W03-P01 — ACCEPTED
W03-P02 — ACCEPTED
W03-P03 — ACCEPTED
W03-A01 — CANDIDATE

W04-P01 — ACCEPTED
W04-P02 — ACCEPTED
W04-P03 — ACCEPTED
W04-A01 — ACCEPTED
W04-A02 — ACCEPTED
```

If W05 finds a conflict:

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

- use of `nav` landmarks;
- accessible labels/labelled-by relationships;
- current-item semantics;
- heading hierarchy in NavList;
- URL/link-based UnderlineNav behavior;
- overflow handling;
- breadcrumb ordered-list structure;
- responsive overflow mechanics;
- test intent.

Implementation evidence does NOT establish:

- current live Primer behavior;
- test PASS;
- usability;
- accessibility conformance;
- universal IA quality;
- correct use by every caller.

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

NORMATIVE NAVIGATION REQUIREMENTS
WAI EXPLANATORY GUIDANCE
DESIGN-SYSTEM NAVIGATION GUIDANCE
PINNED IMPLEMENTATION FINDINGS

GLOBAL / LOCAL / CONTEXTUAL NAVIGATION FINDINGS
LOCATION / ORIENTATION FINDINGS
HIERARCHY FINDINGS
BREADCRUMB FINDINGS
TABS / UNDERLINE NAV FINDINGS
MENU SEMANTICS FINDINGS
LABELING FINDINGS
RESPONSIVE NAVIGATION FINDINGS
MULTIPLE-WAYS FINDINGS

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

- mark any W05 candidate ACCEPTED;
- modify accepted W02/W03/W04 records;
- promote W02-P02;
- promote W03-A01;
- select a router/framework;
- declare a universal hierarchy depth;
- declare every site needs breadcrumbs;
- declare every tab must change URL;
- treat application-menu ARIA roles as ordinary website navigation defaults;
- begin W06.

---

# 20. REGISTRY MUTATION

`.forge/knowledge/registry/sources.json` may add only qualified W05 source records.

Expected behavior:

- WCAG source likely reused;
- WAI navigation/tutorial target may require a materially distinct record from prior WAI page-structure/mobile references;
- GOV.UK navigation target likely materially distinct from prior layout/type source;
- USWDS navigation family is new;
- Primer navigation docs likely materially distinct from prior Button/Layout references;
- pinned Primer repository identity may be reused if the existing source record represents the same exact repository snapshot broadly enough; otherwise create a clearly scoped source record without duplicating ambiguous identity.

Explain every reuse or append decision.

Registry membership means qualified source only.

---

# 21. LICENSE / STORAGE LAW

Store only:

- source metadata;
- canonical URLs;
- bounded summaries;
- observations;
- exact SHAs;
- source paths.

Do not copy:

- whole external documentation;
- large source files;
- design assets;
- screenshots;
- templates.

Unknown license remains reference-only.

---

# 22. NEGATIVE CHECKS

Before return, confirm:

```text
NO frontend application created
NO package.json created
NO dependency installed
NO router/framework selected
NO component library adopted
NO universal site map created
NO universal hierarchy-depth law created
NO seventh source family added
NO mass crawl performed
NO external repository mutated
NO Primer SHA substituted
NO test PASS fabricated
NO runtime accessibility fabricated
NO W05 candidate marked ACCEPTED
NO W02-P02 promotion
NO W03-A01 promotion
NO accepted W02/W03/W04 record modified
NO breadcrumb/history conflation accepted
NO tabs/stepper conflation accepted
NO ordinary navigation/application-menu semantic conflation accepted
NO W06 execution
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
- all W05 candidates remain CANDIDATE;
- all prior accepted/deferred knowledge remains byte-for-byte unchanged.

Expected application evidence:

```text
APPLICATION BUILD: NOT RUN / NOT APPLICABLE
APPLICATION TYPECHECK: NOT RUN / NOT APPLICABLE
APPLICATION TESTS: NOT RUN / NOT APPLICABLE
FRONTEND RUNTIME: NOT RUN / NOT APPLICABLE
BROWSER NAVIGATION TESTING: NOT RUN
KEYBOARD NAVIGATION TESTING: NOT RUN
SCREEN-READER / AT TESTING: NOT RUN
USER IA / TREE-TESTING: NOT RUN
USABILITY TESTING: NOT RUN
```

Tests read != tests executed.

Do not install dependencies merely to inflate validation.

---

# 24. REQUIRED REPORT

Return exactly:

```text
KIRION FORGE — LUCIEN
W05 NAVIGATION & INFORMATION ARCHITECTURE INTELLIGENCE REPORT

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

11. NORMATIVE NAVIGATION REQUIREMENTS
12. GLOBAL / LOCAL / CONTEXTUAL NAVIGATION FINDINGS
13. LOCATION / ORIENTATION FINDINGS
14. HIERARCHY FINDINGS
15. BREADCRUMB FINDINGS
16. TABS / UNDERLINE NAV FINDINGS
17. MENU SEMANTICS FINDINGS
18. LABELING FINDINGS
19. RESPONSIVE NAVIGATION FINDINGS
20. MULTIPLE-WAYS FINDINGS

21. FAILURE-MODE ANALYSIS
22. CONTRADICTIONS / COUNTEREXAMPLES

23. PATTERN CANDIDATES
24. ANTI-PATTERN CANDIDATES

25. PRIOR KNOWLEDGE INTEGRITY
26. REGISTRY MUTATION
27. NEGATIVE CHECKS

28. VALIDATION ACTUALLY EXECUTED
29. VALIDATION NOT EXECUTED / NOT APPLICABLE

30. UNRESOLVED ITEMS
31. COMMITS CREATED
32. FINAL BRANCH
33. EXACT FINAL SHA

34. DISPOSITION RECOMMENDATION
```

Disposition exactly one:

```text
READY_FOR_MAINTAINER_REVIEW
REWORK_REQUIRED
BLOCKED
SOURCE_DRIFT
```

Then STOP.

Do not begin W06.
Do not promote candidates.
Do not merge to main.
Do not self-accept.

Return control to KIRION Forge Maintainer.


---

# HISTORICAL STATUS

```text
COMPLETED
MAINTAINER DISPOSITION: ACCEPT
REVIEWED WORKER CANDIDATE: cebe0abd78e8806deef8af7f3f94ed0a17c44416
ACCEPTANCE ISSUE: #11

K7:
W05-P01 — ACCEPTED
W05-P02 — ACCEPTED
W05-P03 — ACCEPTED
W05-A01 — ACCEPTED
W05-A02 — ACCEPTED
```

This handoff is historical execution evidence.

It is no longer active authority and MUST NOT be executed again.
