# KIRION FORGE: MAINTAINER
# LUCIEN W02 — CONTROLLED PILOT ACQUISITION
# ACTION CONTROLS / BUTTON HIERARCHY / ACCESSIBILITY

## AUTHORITY CLASS

Bounded KIRION Forge Maintainer handoff.

W02 is the first real knowledge-acquisition run under the accepted W01 knowledge-control plane.

This is NOT:

- a frontend application implementation lane;
- a framework-selection lane;
- a design-system adoption lane;
- a bulk crawler;
- a vector-database lane;
- permission to convert source popularity into authority;
- permission to promote candidates without Maintainer review.

The worker role is:

```text
KIRION FORGE: FRONTEND KNOWLEDGE ACQUISITION WORKER
```

The worker MUST execute the accepted W01 K0-K7 lifecycle and stop before K7 promotion.

---

# 0. EXACT REPOSITORY AUTHORITY

Repository:

```text
Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE
```

Canonical accepted source before W02:

```text
main@9b4d291b15322afd46ee83ccb9a6dc40e31d3b06
```

W02 branch:

```text
forge/w02-controlled-pilot-action-controls
```

Before any mutation:

1. resolve live `main`;
2. resolve W02 branch head;
3. confirm the W02 branch descends from the exact canonical source above;
4. confirm W01 is accepted and the knowledge-control plane is active.

If any exact-source condition fails:

```text
SOURCE_DRIFT
STOP
RETURN TO MAINTAINER
```

Do not silently rebase.

---

# 1. CONTROLLING ACCEPTED AUTHORITY

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

.forge/templates/SOURCE_INTAKE_TEMPLATE.md
.forge/templates/PATTERN_CANDIDATE_TEMPLATE.md
.forge/templates/ANTI_PATTERN_CANDIDATE_TEMPLATE.md
```

W01 authority remains binding.

W02 may exercise the model.

W02 may not rewrite W01 policy simply because a source is inconvenient.

---

# 2. PILOT RESEARCH QUESTION

Bound the run to:

> **How should action controls communicate purpose, hierarchy, destructive risk, focus/keyboard accessibility, and interactive state without confusing users?**

Operational sub-questions:

1. What evidence supports using actual action controls for actions and navigation controls for navigation?
2. What evidence exists for primary / secondary / destructive action hierarchy?
3. What normative accessibility requirements constrain focus, keyboard operation, target size, accessible naming, role, and state?
4. How do mature design systems expose loading, disabled, destructive, and priority states?
5. Which claims are normative, which are system-specific conventions, which are implementation evidence, and which are only visual inspiration?
6. What common failure modes can be proposed as candidates without overgeneralizing?

The pilot domain may touch:

```text
INTERACTION
COMPONENT_ARCHITECTURE
VISUAL_HIERARCHY
SEMANTIC_HTML
KEYBOARD_ACCESS
FOCUS_MANAGEMENT
ACCESSIBILITY
CONTENT_DESIGN
```

Do not expand into unrelated frontend domains.

---

# 3. CONTROLLED SOURCE CORPUS

The pilot corpus is intentionally small.

The worker must qualify only the following five source targets, plus directly linked sub-pages/files required to understand them.

Do not add a sixth independent source without Maintainer reauthorization.

## S1 — W3C WCAG 2.2

Candidate identity:

```text
provider: W3C / WAI
canonical URL: https://www.w3.org/TR/WCAG22/
candidate source type: OFFICIAL_STANDARD
candidate authority weight: PRIMARY_NORMATIVE
```

Relevant pilot areas may include, where applicable:

```text
2.1.1 Keyboard
2.4.7 Focus Visible
2.4.11 Focus Not Obscured (Minimum)
2.5.8 Target Size (Minimum)
4.1.2 Name, Role, Value
```

Rules:

- verify the current Recommendation/version context;
- distinguish normative success criteria from explanatory WAI material;
- do not convert WCAG into visual hierarchy guidance it does not state;
- capture exact section anchors/evidence locations.

## S2 — GOV.UK Design System Button

Candidate identity:

```text
provider: GOV.UK Design System
canonical URL: https://design-system.service.gov.uk/components/button/
candidate source type: DESIGN_SYSTEM
candidate authority weight: OFFICIAL_REFERENCE
```

The worker may use directly linked official GOV.UK pages required to interpret the component, including focus-state guidance, but must keep provenance explicit.

Investigate:

- action-oriented button text;
- default / secondary / warning button roles;
- destructive-action guidance;
- visible hierarchy;
- focus-state guidance;
- relevant accessibility references;
- documented research/context limits;
- version/change-history evidence where available.

Do not treat GOV.UK conventions as universal law.

## S3 — Primer Product Button documentation

Candidate identity:

```text
provider: GitHub Primer
canonical URL: https://primer.style/product/components/button/
candidate source type: DESIGN_SYSTEM
candidate authority weight: OFFICIAL_REFERENCE
```

Investigate:

- primary/default/invisible/danger hierarchy;
- loading state;
- disabled/inactive guidance;
- labeling;
- icon/visual use;
- accessibility guidance;
- target-size or keyboard considerations where documented.

Do not infer GitHub-wide product behavior beyond the documented scope.

## S4 — Primer React implementation

Candidate identity:

```text
repository: primer/react
exact pilot SHA: 7f5303d803986887187d86dcebaeda22a4dc6823
candidate source type: COMPONENT_LIBRARY
candidate authority weight: PRIMARY_IMPLEMENTATION
```

Use GitHub source inspection at this exact SHA.

Do NOT substitute a newer `main` silently.

If the exact SHA cannot be read:

```text
SOURCE_BLOCKED
```

for this source and continue only if the remaining run still has enough evidence to be meaningful; otherwise return BLOCKED.

Inspect only files directly relevant to Button behavior, types, loading/disabled/accessibility semantics, and tests/docs.

Do not perform broad repository archaeology.

Do not mutate `primer/react`.

Record exact paths inspected.

## S5 — Landbook landing-page gallery

Candidate identity:

```text
provider: Landbook
canonical URL: https://land-book.com/design/website/landing-page
candidate source type: DESIGN_INSPIRATION
candidate authority weight: INSPIRATION_ONLY
```

Purpose:

Test whether Lucien correctly handles a visually curated source without upgrading it into engineering authority.

The worker may inspect up to THREE publicly visible examples available from that category at acquisition time.

Storage rules:

- metadata and links only;
- no screenshot harvesting into Git;
- no copied design pack/template assets;
- no claims about accessibility, semantics, performance, responsive behavior, implementation architecture, or production readiness unless separately evidenced by a qualified source capable of supporting them.

Landbook may contribute visual observations only.

It MUST NOT be used as normative or implementation evidence.

---

# 4. SOURCE COUNT / SCOPE LIMIT

Maximum qualified independent source records:

```text
5
```

Directly linked sub-pages under the same provider may be referenced as evidence locations or separate records only if the accepted schema requires separate identity.

If separate source records are created for linked official sub-pages, the total logical source families must remain exactly the five above and the review packet must explain the expansion.

Do not turn W02 into a general web crawl.

---

# 5. W02 REQUIRED OUTPUT SURFACE

W02 may create:

```text
.forge/knowledge/runs/W02_ACTION_CONTROLS_PILOT/
├── REQUEST.md
├── SOURCE_QUALIFICATION.md
├── OBSERVATION_INDEX.md
├── CROSS_SOURCE_COMPARISON.md
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

W02 may modify:

```text
.forge/knowledge/registry/sources.json
.forge/SSOT_CURRENT.md
.forge/WORK_LEDGER.md
README.md
```

only as required for accurate W02 state.

Do not modify W01 schemas/protocols unless a schema defect makes W02 impossible.

If a W01 schema defect is discovered:

```text
STOP
REPORT SCHEMA_BLOCK
```

Do not repair W01 policy inside W02 without Maintainer authority.

---

# 6. K0 — REQUEST RECORD

`REQUEST.md` must record:

- W02 run ID;
- exact repository source SHA;
- exact branch;
- research question;
- domains;
- five source families;
- non-goals;
- requesting authority;
- worker role;
- start timestamp;
- stop conditions.

---

# 7. K1 — SOURCE DISCOVERY

K1 is already bounded by this handoff.

The worker is NOT being asked to discover the whole web.

For each named source:

- resolve canonical identity;
- verify it exists;
- note relevant sub-pages/files;
- do not extract conclusions yet.

If a named public source is unavailable, report it.

Do not replace it with a similar source without Maintainer authority.

---

# 8. K2 — SOURCE QUALIFICATION

For each source, produce qualification evidence covering:

```text
source_id
title
provider
source_type
authority_weight
authority_reason
canonical_url
repository/path where applicable
version/tag/SHA where applicable
retrieved_at
published_at where available
license
license_status
content_storage_policy
status
recency_status
limitations
```

Use the accepted source schema.

Important expected distinctions:

```text
WCAG 2.2:
normative for accessibility success criteria within its scope

GOV.UK / Primer documentation:
official references for their own systems

Primer React exact SHA:
primary implementation evidence for that code snapshot

Landbook:
inspiration only
```

These are expected starting hypotheses.

The worker must still verify them.

---

# 9. LICENSE / STORAGE REQUIREMENTS

For every source:

- verify license/reuse status where practical;
- preserve attribution;
- store links and metadata;
- use only bounded quotations when necessary;
- default to summaries and observations.

For `primer/react`, record repository license evidence.

For Landbook:

```text
NO copied screenshots
NO copied templates
NO downloaded design packs
NO reproduction of paywalled assets
```

Unknown license remains:

```text
REFERENCE ONLY
```

---

# 10. K3 — OBSERVATION EXTRACTION

Create individual observation records conforming to:

```text
.forge/knowledge/schemas/observation-record.schema.json
```

Each observation must identify:

- exact source;
- exact evidence location;
- bounded observed behavior;
- domain;
- context;
- confidence;
- limitations;
- source version context;
- status.

No recommendation language in raw observations.

Bad:

```text
Every interface should have one primary button.
```

Valid observation:

```text
The GOV.UK Button guidance advises avoiding multiple default buttons on a page because competing main calls to action can make the next action harder to identify.
```

---

# 11. OBSERVATION CAP

Target:

```text
12 to 24 total observations
```

Hard maximum:

```text
30
```

Do not create hundreds of micro-observations.

Prefer meaningful evidence units.

Suggested distribution:

```text
WCAG: 4–7
GOV.UK: 3–6
Primer docs: 3–6
Primer implementation: 2–5
Landbook: 1–3
```

These are guidance, not quotas.

---

# 12. K4 — CROSS-SOURCE COMPARISON

`CROSS_SOURCE_COMPARISON.md` must compare evidence under at least these questions:

## A. semantic purpose

What evidence distinguishes:

```text
action
navigation
submission
destructive action
```

## B. hierarchy

What evidence supports or challenges:

```text
one clearly dominant primary action
secondary actions visually subordinate
danger/destructive actions visually and textually distinct
```

## C. accessibility

Compare:

```text
keyboard operation
focus visibility
focus obstruction
target size
accessible naming
role/state communication
disabled/inactive behavior
loading behavior
```

## D. context boundaries

Explicitly distinguish:

```text
normative accessibility requirement
design-system convention
implementation behavior
visual inspiration
```

## E. contradictions

If GOV.UK, Primer, WCAG, or implementation evidence differs:

do not average it away.

Classify as:

```text
CONTEXTUAL TRADEOFF
SCOPE NARROWING
VERSION SPLIT
UNRESOLVED
```

as appropriate.

---

# 13. K5 — CANDIDATE SYNTHESIS

W02 MAY produce candidates only when evidence supports them.

Hard cap:

```text
pattern candidates: 0–2
anti-pattern candidates: 0–1
```

Zero candidates is a valid result.

Do not manufacture candidates to fill folders.

Candidate examples that MAY emerge if evidence supports them:

```text
ACTION_CONTROL_SEMANTIC_ALIGNMENT
SINGLE_DOMINANT_PRIMARY_ACTION
DESTRUCTIVE_ACTION_DISTINCTION
MULTIPLE_COMPETING_PRIMARY_ACTIONS
DISABLED_CONTROL_WITHOUT_RECOVERY_PATH
```

These names are NOT accepted claims.

They are only possible synthesis targets.

Every candidate must:

- link non-empty source IDs;
- link non-empty observation IDs;
- state applicability;
- state non-applicability / legitimate contexts;
- preserve counterexamples;
- include accessibility/performance/responsive implications where relevant;
- remain status `CANDIDATE`;
- leave `accepted_by` and `accepted_at` empty/null as schema permits.

Do not create ACCEPTED records.

---

# 14. ANTI-AI-SLOP DISCIPLINE

This pilot intentionally touches visual hierarchy.

Do not produce:

```text
"this looks AI-generated"
```

as evidence.

If an anti-pattern candidate is synthesized, it must identify:

- observable structure;
- concrete harm mechanism;
- affected context;
- legitimate counter-contexts;
- source evidence;
- counterexamples.

Landbook must not be used to declare a design anti-pattern merely because a style is visually common there.

---

# 15. K6 — MAINTAINER REVIEW PACKET

`review/MAINTAINER_REVIEW_PACKET.md` must contain:

```text
RUN ID
EXACT LUCIEN SOURCE
SOURCE SET
QUALIFICATION SUMMARY
OBSERVATION COUNT

HIGH-CONFIDENCE FINDINGS
LOWER-CONFIDENCE FINDINGS
CONTRADICTIONS
COUNTEREXAMPLES
VERSION LIMITS
LICENSE / STORAGE LIMITS

PATTERN CANDIDATES
ANTI-PATTERN CANDIDATES

WHAT WCAG ACTUALLY REQUIRES
WHAT DESIGN SYSTEMS RECOMMEND
WHAT IMPLEMENTATION CODE DEMONSTRATES
WHAT LANDOOK/LANDBOOK-CLASS INSPIRATION CAN AND CANNOT SUPPORT

UNRESOLVED QUESTIONS

WORKER RECOMMENDATION
```

Correct the typo in the heading if generated; use:

```text
WHAT LANDBOOK-CLASS INSPIRATION CAN AND CANNOT SUPPORT
```

The packet must not self-accept any candidate.

---

# 16. K7 — PROHIBITED IN WORKER TURN

The worker must NOT execute K7 promotion.

No candidate may be changed to ACCEPTED.

No reusable Forge law may be declared.

No pattern becomes mandatory guidance.

The worker returns the review packet to Maintainer.

---

# 17. PRIMER IMPLEMENTATION INSPECTION BOUNDARY

For:

```text
primer/react@7f5303d803986887187d86dcebaeda22a4dc6823
```

Inspect only directly relevant source/tests/docs.

Expected target concepts:

- Button component;
- loading state;
- disabled/inactive semantics;
- variants;
- accessible naming/announcements;
- button group behavior where directly relevant.

Do not inspect unrelated components for "interesting patterns."

Record every inspected path in the source qualification or observation index.

---

# 18. LANDOOK/LANDBOOK INSPIRATION BOUNDARY

The correct provider name is:

```text
Landbook
```

The worker may observe visual presentation from at most three public examples visible from the named landing-page gallery.

It may record observations such as:

- relative prominence of calls to action;
- number of visibly emphasized actions;
- label length/style;
- spatial grouping;
- apparent primary/secondary visual distinction.

It may NOT claim from screenshots alone:

- element semantics;
- keyboard accessibility;
- screen-reader behavior;
- interaction state;
- source code architecture;
- responsive behavior outside observed views;
- performance;
- production correctness.

This source exists partly to verify that the W01 design-reference boundary actually works.

---

# 19. REGISTRY MUTATION

`.forge/knowledge/registry/sources.json` may be populated only with qualified source records from this W02 corpus.

Registry inclusion means:

```text
qualified source record exists
```

It does NOT mean:

```text
source claims accepted
pattern accepted
source universally authoritative
```

Do not add unrelated websites or remembered references.

---

# 20. NEGATIVE CHECKS

Before return, verify:

```text
NO frontend app created
NO package.json created
NO dependency installed
NO framework selected
NO application stack selected
NO vector database created
NO bulk crawl performed
NO sixth independent source added
NO external repo mutated
NO Primer main substituted for the pinned SHA
NO Landbook screenshot copied into Git
NO design asset pack copied
NO candidate marked ACCEPTED
NO worker self-promotion
NO accessibility conformance claim for Lucien
NO design-system convention mislabeled as WCAG requirement
NO visual inspiration mislabeled as engineering proof
NO runtime/build/test PASS fabricated
```

---

# 21. VALIDATION

The worker SHOULD validate:

- exact Lucien branch ancestry;
- current main unchanged;
- all JSON parses;
- every source record conforms structurally to W01 source schema;
- every observation conforms structurally to W01 observation schema;
- every candidate conforms structurally to the corresponding W01 candidate schema;
- source IDs referenced by observations exist;
- observation/source IDs referenced by candidates exist;
- no duplicate IDs;
- source registry contains only W02-qualified sources;
- all changed files remain within W02 authority;
- no accepted status exists in W02 candidates.

If no dedicated JSON Schema validator exists, do not install one unless separately authorized.

Manual/structural schema checking is allowed but must be labeled accurately.

---

# 22. APPLICATION VALIDATION

Expected:

```text
APPLICATION BUILD:
NOT RUN / NOT APPLICABLE

APPLICATION TYPECHECK:
NOT RUN / NOT APPLICABLE

APPLICATION TESTS:
NOT RUN / NOT APPLICABLE

FRONTEND RUNTIME:
NOT RUN / NOT APPLICABLE
```

Do not manufacture application evidence.

---

# 23. REQUIRED W02 REPORT

Return exactly:

```text
KIRION FORGE — LUCIEN
W02 CONTROLLED PILOT ACQUISITION REPORT

1. LIVE SOURCE VERIFICATION

2. PILOT QUESTION

3. FILES CREATED

4. FILES MODIFIED

5. SOURCE CORPUS
S1
S2
S3
S4
S5

6. SOURCE QUALIFICATION RESULTS

7. LICENSE / STORAGE RESULTS

8. OBSERVATION COUNT

9. OBSERVATION SUMMARY BY SOURCE

10. CROSS-SOURCE COMPARISON

11. NORMATIVE VS REFERENCE VS IMPLEMENTATION VS INSPIRATION DISTINCTION

12. CONTRADICTIONS / COUNTEREXAMPLES

13. PATTERN CANDIDATES

14. ANTI-PATTERN CANDIDATES

15. REGISTRY MUTATION

16. NEGATIVE CHECKS

17. VALIDATION ACTUALLY EXECUTED

18. VALIDATION NOT EXECUTED / NOT APPLICABLE

19. UNRESOLVED ITEMS

20. COMMITS CREATED

21. FINAL BRANCH

22. EXACT FINAL SHA

23. DISPOSITION RECOMMENDATION
```

Disposition exactly one:

```text
READY_FOR_MAINTAINER_REVIEW
REWORK_REQUIRED
BLOCKED
SOURCE_DRIFT
```

Then STOP.

Do not begin W03.
Do not promote candidates.
Do not select a frontend stack.
Do not merge to main.
Do not self-accept.

Return control to KIRION Forge Maintainer.


---

# HISTORICAL STATUS

```text
COMPLETED
MAINTAINER DISPOSITION: ACCEPT
REVIEWED WORKER CANDIDATE: ac7b38da1e0e09bad195a5a216dc0dfa7efbfae3
ACCEPTANCE ISSUE: #5

K7:
W02-P01 — ACCEPTED
W02-A01 — ACCEPTED
W02-P02 — DEFERRED / REMAINS CANDIDATE
```

This handoff is historical execution evidence.

It is no longer active authority and MUST NOT be executed again.
