# KIRION FORGE: MAINTAINER
# LUCIEN W03 — VISUAL HIERARCHY & COMPOSITION INTELLIGENCE
# STRUCTURE / GROUPING / DENSITY / ANTI-SLOP VOCABULARY

## AUTHORITY CLASS

Bounded KIRION Forge Maintainer handoff.

W03 is a controlled frontend-knowledge acquisition lane.

This is NOT:

- frontend application implementation;
- framework selection;
- design-system adoption;
- mass web crawling;
- template collection;
- aesthetic preference voting;
- permission to label interfaces "AI slop" without evidence;
- permission to promote candidates without Maintainer review.

Worker role:

```text
KIRION FORGE: FRONTEND KNOWLEDGE ACQUISITION WORKER
```

The worker executes K0–K6 and STOPS before K7 promotion.

---

# 0. EXACT REPOSITORY AUTHORITY

Repository:

```text
Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE
```

Canonical accepted source before W03:

```text
main@20a2bb44461a1066b44aa242c6bad18fac673025
```

W03 branch:

```text
forge/w03-visual-hierarchy-composition-intelligence
```

Before mutation:

1. resolve live `main`;
2. resolve W03 branch head;
3. confirm W03 descends from the exact canonical source above;
4. confirm W00, W01, and W02 are accepted;
5. confirm no other active handoff supersedes this lane.

If any exact-source condition fails:

```text
SOURCE_DRIFT
STOP
RETURN TO MAINTAINER
```

Do not silently rebase or reinterpret authority.

---

# 1. CONTROLLING AUTHORITY

Read and obey:

```text
AGENTS.md
.forge/AUTHORITY.md
.forge/SSOT_CURRENT.md
.forge/EVIDENCE.md
.forge/CLASSIFICATION.md
.forge/DECISIONS.md
.forge/VALIDATION.md
.forge/WORK_LEDGER.md
.forge/ACCEPTANCE.md

.forge/knowledge/README.md
.forge/knowledge/SOURCE_TAXONOMY.md
.forge/knowledge/SOURCE_AUTHORITY.md
.forge/knowledge/KNOWLEDGE_SCHEMA.md
.forge/knowledge/PATTERN_LIFECYCLE.md
.forge/knowledge/ANTI_PATTERN_LIFECYCLE.md
.forge/knowledge/DESIGN_REFERENCE_POLICY.md
.forge/knowledge/LICENSING_AND_PROVENANCE.md

.forge/protocols/KNOWLEDGE_ACQUISITION.md
.forge/protocols/SOURCE_EVALUATION.md
.forge/protocols/KNOWLEDGE_PROMOTION.md
```

Accepted W02 knowledge remains binding:

```text
W02-P01 — Contextual dominant primary action
ACCEPTED / MEDIUM

W02-A01 — Competing dominant primary controls
ACCEPTED / MEDIUM
```

Deferred W02-P02 remains CANDIDATE and must not be silently promoted in W03.

---

# 2. HUMAN OBJECTIVE

Lucien must learn the engineering/design vocabulary behind interfaces that feel:

- structured;
- scannable;
- intentional;
- domain-specific;
- calm enough to understand;
- dense where density is useful;
- sparse where space has structural purpose;
- responsive without losing hierarchy.

Lucien must also learn to identify evidence-backed failure modes behind what humans often loosely call "AI slop."

W03 must translate vague visual criticism into observable frontend concepts.

The target is not:

```text
"this looks bad"
```

The target is:

```text
"this composition has weak grouping,
uniform visual weight,
excessive surface boundaries,
or repeated containers without information-hierarchy value,
and here is the evidence and context."
```

---

# 3. W03 RESEARCH QUESTION

Primary question:

> **What evidence makes a frontend composition visually structured, scannable, and purposeful, and what observable composition failures create clutter, weak hierarchy, unnecessary containerization, or generic template-like presentation?**

Operational sub-questions:

1. How do headings, semantic regions, spacing, proximity, typography, and width establish information hierarchy?
2. When does a grid or region structure improve comprehension and responsive behavior?
3. What makes whitespace structural rather than merely empty?
4. When are cards/tiles/containers useful grouping devices, and when can repeated surfaces obscure hierarchy?
5. How should dense interfaces distinguish primary content, secondary content, metadata, navigation, and actions?
6. How do mature systems reduce composition complexity on smaller viewports?
7. Which visual conventions are system-specific versus broadly recurring?
8. Which anti-pattern names can be proposed from observable mechanisms rather than "AI-generated" appearance?

Allowed domains:

```text
INFORMATION_ARCHITECTURE
LAYOUT
RESPONSIVE_DESIGN
TYPOGRAPHY
SPACING
VISUAL_HIERARCHY
CONTENT_DESIGN
COMPONENT_ARCHITECTURE
DESIGN_SYSTEMS
ACCESSIBILITY
SEMANTIC_HTML
```

Do not expand into unrelated state-management, backend, API, or product-domain architecture.

---

# 4. CONTROLLED SOURCE CORPUS

Use exactly these seven source families.

Directly linked official pages/files may be used where required, but do not add an eighth independent source family.

## S1 — W3C WCAG 2.2

Canonical:

```text
https://www.w3.org/TR/WCAG22/
```

Candidate classification:

```text
OFFICIAL_STANDARD
PRIMARY_NORMATIVE
```

Relevant areas may include:

```text
1.3.1 Info and Relationships
1.4.3 Contrast (Minimum)
1.4.10 Reflow
1.4.11 Non-text Contrast
2.4.6 Headings and Labels
```

Use WCAG only for actual normative requirements.

Do NOT infer:

- card count;
- ideal spacing scale;
- ideal page width;
- one-column preference;
- visual style trends.

## S2 — W3C WAI Designing for Web Accessibility / Page Structure guidance

Candidate pages:

```text
https://www.w3.org/WAI/tips/designing/
https://www.w3.org/WAI/tutorials/page-structure/headings/
https://www.w3.org/WAI/tutorials/page-structure/regions/
```

Candidate classification:

```text
OFFICIAL_REFERENCE
OFFICIAL_REFERENCE
```

Purpose:

Capture explanatory guidance around:

- headings;
- whitespace/proximity;
- grouping;
- page regions;
- viewport adaptation;
- scannability.

CRITICAL:

WAI tips/tutorials are explanatory guidance, not themselves WCAG success criteria.

Keep S1 normative claims separate from S2 explanatory guidance.

## S3 — GOV.UK Design System Layout + Type Scale

Canonical pages:

```text
https://design-system.service.gov.uk/styles/layout/
https://design-system.service.gov.uk/styles/type-scale/
```

Candidate classification:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- mobile-first/small-screen-first structure;
- common content widths;
- two-thirds patterns;
- line-length rationale;
- grid use;
- typography scale;
- vertical rhythm;
- system constraints and context limits.

Do not universalize GOV.UK service conventions.

## S4 — IBM Carbon 2x Grid

Canonical pages:

```text
https://www.carbondesignsystem.com/building-blocks/foundations/2x-grid/overview
https://www.carbondesignsystem.com/building-blocks/foundations/2x-grid/guidelines
```

Candidate classification:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- spacing rhythm;
- grid geometry;
- layout purpose;
- content/user-goal alignment;
- visual consistency;
- responsive composition.

Do not treat Carbon's 8px/2x system as universal law.

## S5 — GitHub Primer Layout / Typography guidance

Canonical pages:

```text
https://primer.style/product/getting-started/foundations/layout/
https://primer.style/product/getting-started/foundations/typography/
https://primer.style/product/components/page-layout/
https://primer.style/product/components/page-layout/accessibility/
```

Candidate classification:

```text
DESIGN_SYSTEM
OFFICIAL_REFERENCE
```

Investigate:

- focused content;
- layout regions;
- page types;
- maximum widths;
- pane/content roles;
- responsive reduction;
- typography hierarchy;
- semantic heading order;
- density/cognitive-load guidance.

Do not treat GitHub product conventions as universal requirements.

## S6 — Primer React PageLayout implementation

Repository:

```text
primer/react
```

Exact source SHA:

```text
7f5303d803986887187d86dcebaeda22a4dc6823
```

Candidate classification:

```text
COMPONENT_LIBRARY
PRIMARY_IMPLEMENTATION
```

Inspect only directly relevant PageLayout files, including where useful:

```text
packages/react/src/PageLayout/PageLayout.tsx
packages/react/src/PageLayout/PageLayout.module.css
packages/react/src/PageLayout/PageLayout.test.tsx
packages/react/src/PageLayout/usePaneWidth.ts
packages/react/src/PageLayout/DragHandle.tsx
```

Do not substitute newer `main`.

Do not mutate `primer/react`.

Tests may be inspected but are NOT TESTED unless actually executed.

## S7 — Landbook visual inspiration

Canonical category:

```text
https://land-book.com/design/website/landing-page
```

Candidate classification:

```text
DESIGN_INSPIRATION
INSPIRATION_ONLY
```

Inspect at most THREE public examples available at acquisition time.

Purpose:

- test visual-observation discipline;
- inspect apparent grouping, sectioning, emphasis, spacing, container use, and composition;
- compare visual convention against stronger engineering sources without upgrading inspiration into proof.

Do NOT claim from screenshots alone:

- semantics;
- accessibility;
- DOM structure;
- responsive behavior beyond observed screenshots/views;
- performance;
- production correctness;
- implementation architecture.

Do not copy screenshots or assets into Git.

---

# 5. SOURCE LIMIT

Independent source families:

```text
EXACTLY 7
```

Do not add:

- Nielsen Norman Group;
- Material;
- Apple HIG;
- Tailwind UI;
- Dribbble;
- Behance;
- Mobbin;
- random articles;
- Reddit;
- AI-generated frontend advice;

during W03.

A future lane may qualify them separately.

---

# 6. W03 OUTPUT SURFACE

W03 may create only:

```text
.forge/knowledge/runs/W03_VISUAL_HIERARCHY_COMPOSITION/
├── REQUEST.md
├── SOURCE_QUALIFICATION.md
├── VOCABULARY.md
├── OBSERVATION_INDEX.md
├── CROSS_SOURCE_COMPARISON.md
├── ANTI_SLOP_ANALYSIS.md
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

W03 may modify:

```text
.forge/knowledge/registry/sources.json
.forge/SSOT_CURRENT.md
.forge/WORK_LEDGER.md
README.md
```

only as needed for accurate state.

Do NOT modify accepted W01 schemas/protocols.

If W01 schema blocks valid W03 representation:

```text
SCHEMA_BLOCK
STOP
RETURN TO MAINTAINER
```

---

# 7. K0 — REQUEST RECORD

`REQUEST.md` must record:

- W03 run ID;
- exact Lucien canonical source;
- exact branch;
- human objective;
- research question;
- allowed domains;
- seven source families;
- observation/candidate caps;
- non-goals;
- authority;
- start timestamp;
- stop conditions.

---

# 8. K1 — SOURCE DISCOVERY

The source set is pre-bounded.

For each source family:

- resolve current canonical identity;
- verify accessibility;
- note relevant sub-pages/files;
- record version/date/SHA when available;
- do not replace unavailable sources silently.

If one source becomes inaccessible:

```text
SOURCE_BLOCKED
```

and continue only if the remaining corpus still supports a meaningful comparison.

Do not invent replacement sources.

---

# 9. K2 — SOURCE QUALIFICATION

Create/update source records under the accepted source schema.

For each source capture:

```text
id
title
provider
source_type
authority_weight
authority_reason
canonical_url
repository/path if applicable
version/tag/SHA if applicable
retrieved_at
published_at if available
license
license_status
content_storage_policy
status
recency_status
limitations
```

Expected authority distinctions:

```text
S1 WCAG:
PRIMARY_NORMATIVE within actual success-criterion scope

S2 WAI:
OFFICIAL_REFERENCE explanatory guidance

S3 GOV.UK:
OFFICIAL_REFERENCE for GOV.UK system conventions

S4 Carbon:
OFFICIAL_REFERENCE for Carbon conventions

S5 Primer docs:
OFFICIAL_REFERENCE for Primer/GitHub product conventions

S6 Primer implementation:
PRIMARY_IMPLEMENTATION for exact pinned snapshot

S7 Landbook:
INSPIRATION_ONLY
```

Verify rather than blindly copy these hypotheses.

---

# 10. K3 — VOCABULARY EXTRACTION

W03 must produce:

```text
VOCABULARY.md
```

This is important.

Lucien must establish clear working definitions, backed by observations, for terms such as:

```text
visual hierarchy
information hierarchy
grouping
proximity
spacing rhythm
vertical rhythm
content width
line length
layout region
primary content
secondary content
supporting metadata
surface
container
card
tile
pane
sidebar
section
grid
responsive composition
density
visual weight
scanability / scannability
progressive emphasis
semantic heading hierarchy
whitespace
```

Rules:

- do not invent authoritative definitions when sources disagree;
- note system-specific terminology;
- distinguish synonyms from materially different concepts;
- preserve unresolved terms;
- link vocabulary terms to source observations.

W03 may add terms discovered from the corpus.

---

# 11. OBSERVATION EXTRACTION

All observations must conform to the accepted observation schema.

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
S1 WCAG: 4–6
S2 WAI: 3–5
S3 GOV.UK: 4–6
S4 Carbon: 4–6
S5 Primer docs: 5–8
S6 Primer implementation: 3–6
S7 Landbook: 1–3
```

These are guidance, not quotas.

Each observation must identify:

- source;
- domain;
- exact evidence location;
- observed behavior/guidance;
- context;
- confidence;
- limitation;
- version context;
- status.

Raw observation must not silently become recommendation.

---

# 12. K4 — CROSS-SOURCE COMPARISON

`CROSS_SOURCE_COMPARISON.md` must compare at least:

## A. Hierarchy mechanisms

Compare evidence for:

```text
heading scale
font weight
content width
spacing
proximity
alignment
regions
grid
surface/container boundaries
action emphasis
```

## B. Grouping

Ask:

- what makes content belong together?
- when is proximity sufficient?
- when is a visible boundary useful?
- when do headings/regions carry structure without another card/container?

## C. Density

Ask:

- what evidence supports dense vs sparse presentation?
- when is reduced width/readability useful?
- when does whitespace establish hierarchy?
- when does extra whitespace merely consume space?

Do not invent universal density numbers.

## D. Responsive composition

Compare:

- stacking;
- region reduction;
- column changes;
- preservation of task priority;
- content order;
- width changes;
- semantic continuity.

## E. Semantics vs appearance

Explicitly distinguish:

```text
visual heading != semantic heading automatically
visual card != semantic region automatically
visual divider != information relationship automatically
visual inspiration != implementation evidence
```

## F. Contradictions

Classify disagreements as:

```text
CONTEXTUAL_TRADEOFF
SYSTEM_CONVENTION
SCOPE_NARROWING
VERSION_SPLIT
UNRESOLVED
```

Do not majority-vote them away.

---

# 13. ANTI-SLOP ANALYSIS

Create:

```text
ANTI_SLOP_ANALYSIS.md
```

This document must explicitly reject:

```text
"AI-looking = bad"
```

Instead evaluate whether evidence supports candidate failure mechanisms such as:

```text
DECORATIVE_CARD_OVERLOAD
CONTAINER_NESTING_WITHOUT_INFORMATION_VALUE
UNIFORM_VISUAL_WEIGHT
WEAK_INFORMATION_HIERARCHY
EXCESSIVE_SECTION_FRAGMENTATION
MEANINGLESS_METRIC_SURFACES
WHITESPACE_WITHOUT_STRUCTURAL_PURPOSE
DECORATIVE_ICON_SATURATION
GENERIC_HERO_COMPOSITION
FAKE_DASHBOARD_DENSITY
```

These names are hypothesis vocabulary ONLY.

W03 may:

- rename them;
- merge them;
- reject them;
- leave them unresolved;
- produce no candidate if evidence is insufficient.

For every explored anti-pattern hypothesis ask:

1. What observable structure exists?
2. What user/comprehension/maintenance harm is claimed?
3. Which source actually supports that harm?
4. What legitimate context makes the same structure reasonable?
5. Is the evidence direct, inferred, system-specific, or inspiration-only?
6. Is there a counterexample?

No "it looks generic" as standalone evidence.

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
STRUCTURAL_GROUPING_BY_PROXIMITY
BOUNDED_CONTENT_WIDTH_FOR_READING
REGION_BASED_PAGE_COMPOSITION
RESPONSIVE_COMPLEXITY_REDUCTION
CONSISTENT_SPACING_RHYTHM
SEMANTIC_AND_VISUAL_HEADING_ALIGNMENT
```

Possible anti-pattern hypotheses MAY include:

```text
DECORATIVE_CARD_OVERLOAD
UNIFORM_VISUAL_WEIGHT
CONTAINER_NESTING_WITHOUT_INFORMATION_VALUE
EXCESSIVE_SECTION_FRAGMENTATION
```

These are not accepted claims.

Every candidate must:

- link non-empty source IDs;
- link non-empty observation IDs;
- identify applicability;
- identify non-applicability;
- preserve counterexamples;
- describe evidence strength;
- distinguish direct evidence from inference;
- include accessibility/responsive implications where relevant;
- remain `CANDIDATE`;
- contain no acceptance authority.

Do not force a candidate for "AI slop" itself.

---

# 15. LANDOOK / LANDBOOK VISUAL BOUNDARY

Correct provider:

```text
Landbook
```

Inspect at most THREE public examples.

Record only what is visibly observable in the inspected presentation, such as:

- section boundaries;
- apparent primary/secondary emphasis;
- apparent card/surface count;
- spacing;
- text scale;
- grouping;
- repeated visual motifs;
- density.

Do not infer DOM, semantics, accessibility, source architecture, responsive behavior, or performance from still visuals.

No screenshots or assets stored in Git.

---

# 16. PRIMER IMPLEMENTATION BOUNDARY

Use exactly:

```text
primer/react@7f5303d803986887187d86dcebaeda22a4dc6823
```

Inspect only directly relevant PageLayout code/tests.

Do not roam the repository for unrelated examples.

Implementation evidence may prove:

- component regions;
- responsive values;
- CSS layout mechanics;
- spacing mechanisms;
- region ordering;
- pane/sidebar behavior;
- test intent.

It does NOT prove:

- tests pass;
- usability;
- accessibility conformance;
- visual superiority;
- current Primer main behavior.

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

HIGH-CONFIDENCE FINDINGS
LOWER-CONFIDENCE FINDINGS

HIERARCHY FINDINGS
GROUPING FINDINGS
DENSITY FINDINGS
RESPONSIVE-COMPOSITION FINDINGS

NORMATIVE VS REFERENCE VS IMPLEMENTATION VS INSPIRATION

ANTI-SLOP HYPOTHESES
SUPPORTED
WEAK / INSUFFICIENT
REJECTED / MISFRAMED

CONTRADICTIONS
COUNTEREXAMPLES
VERSION LIMITS
LICENSE / STORAGE LIMITS

PATTERN CANDIDATES
ANTI-PATTERN CANDIDATES

WHAT SHOULD NOT BE GENERALIZED

UNRESOLVED QUESTIONS
WORKER RECOMMENDATION
```

No candidate self-promotion.

---

# 18. K7 — PROHIBITED

The worker MUST NOT:

- mark any W03 candidate ACCEPTED;
- alter accepted W02 dispositions;
- promote W02-P02;
- create global "AI slop" law;
- declare universal frontend best practices;
- select a frontend stack.

K7 is Maintainer-only.

---

# 19. REGISTRY MUTATION

`.forge/knowledge/registry/sources.json` may add only qualified W03 source records.

If a W03 source duplicates an already-qualified provider/source from W02:

- do not create ambiguous duplicate IDs;
- preserve historical W02 identity;
- create a new record only when the source target/version/scope is materially distinct;
- otherwise reference the existing source record and document reuse.

Registry membership means:

```text
QUALIFIED SOURCE
```

not:

```text
ACCEPTED CLAIM
```

---

# 20. LICENSE / STORAGE LAW

Preserve provenance for every source.

Default storage:

- metadata;
- URLs;
- bounded summaries;
- observations;
- hashes/SHAs;
- source paths.

Do not copy:

- entire design-system pages;
- proprietary design packs;
- screenshots;
- templates/themes;
- large code bodies.

Unknown license:

```text
REFERENCE ONLY
```

until resolved.

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
NO vector database created
NO mass crawl performed
NO eighth independent source family added
NO external repository mutated
NO Primer SHA substituted
NO Landbook screenshot stored
NO third-party design pack copied
NO "AI-looking = bad" claim accepted
NO candidate marked ACCEPTED
NO W02-P02 silently promoted
NO WCAG requirement invented
NO design-system convention mislabeled normative
NO inspiration mislabeled implementation evidence
NO runtime/build/test PASS fabricated
NO W04 execution
```

---

# 22. VALIDATION

Worker SHOULD validate:

- exact branch ancestry;
- canonical main unchanged;
- changed-file scope;
- JSON parsing;
- source record structural conformance;
- observation structural conformance;
- candidate structural conformance;
- source ID integrity;
- observation ID integrity;
- candidate linkage;
- duplicate IDs;
- registry scope;
- all W03 candidates remain CANDIDATE;
- W02 accepted records remain unchanged;
- W02-P02 remains CANDIDATE.

Do not install a validator dependency merely to claim schema validation.

Label manual/structural validation accurately.

Expected application evidence:

```text
APPLICATION BUILD: NOT RUN / NOT APPLICABLE
APPLICATION TYPECHECK: NOT RUN / NOT APPLICABLE
APPLICATION TESTS: NOT RUN / NOT APPLICABLE
FRONTEND RUNTIME: NOT RUN / NOT APPLICABLE
```

---

# 23. REQUIRED REPORT

Return exactly:

```text
KIRION FORGE — LUCIEN
W03 VISUAL HIERARCHY & COMPOSITION INTELLIGENCE REPORT

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
S7

6. SOURCE QUALIFICATION RESULTS
7. LICENSE / STORAGE RESULTS

8. VOCABULARY RESULTS
9. OBSERVATION COUNT
10. OBSERVATION SUMMARY BY SOURCE

11. HIERARCHY FINDINGS
12. GROUPING FINDINGS
13. DENSITY FINDINGS
14. RESPONSIVE-COMPOSITION FINDINGS

15. NORMATIVE VS REFERENCE VS IMPLEMENTATION VS INSPIRATION DISTINCTION

16. ANTI-SLOP ANALYSIS
17. CONTRADICTIONS / COUNTEREXAMPLES

18. PATTERN CANDIDATES
19. ANTI-PATTERN CANDIDATES

20. REGISTRY MUTATION
21. NEGATIVE CHECKS

22. VALIDATION ACTUALLY EXECUTED
23. VALIDATION NOT EXECUTED / NOT APPLICABLE

24. UNRESOLVED ITEMS
25. COMMITS CREATED
26. FINAL BRANCH
27. EXACT FINAL SHA

28. DISPOSITION RECOMMENDATION
```

Disposition exactly one:

```text
READY_FOR_MAINTAINER_REVIEW
REWORK_REQUIRED
BLOCKED
SOURCE_DRIFT
```

Then STOP.

Do not begin W04.
Do not promote candidates.
Do not select a frontend stack.
Do not merge to main.
Do not self-accept.

Return control to KIRION Forge Maintainer.
