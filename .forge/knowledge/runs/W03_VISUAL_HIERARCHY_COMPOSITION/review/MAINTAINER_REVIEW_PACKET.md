# KIRION FORGE — W03 MAINTAINER REVIEW PACKET (K6)

## RUN ID
W03_VISUAL_HIERARCHY_COMPOSITION

## EXACT LUCIEN SOURCE
- Accepted main: 20a2bb44461a1066b44aa242c6bad18fac673025
- Exact verified W03 governance head: forge/w03-visual-hierarchy-composition-intelligence@9004a7a5dbaf674bc4cc99ed6e48fc16b5eb8eb5
- Final worker candidate SHA is returned in worker report/GitHub branch; this pre-commit document does not invent it.
- Maintainer issue #7; K7 prohibited in worker turn.

## SOURCE SET
S1 W02-S1 WCAG 2.2 (reused);
S2 W03-S2 WAI Designing/Headings/Regions;
S3 W03-S3 GOV.UK Layout/Type;
S4 W03-S4 IBM Carbon 2x Grid;
S5 W03-S5 Primer Layout/Typography/PageLayout;
S6 W03-S6 primer/react pinned PageLayout at 7f5303d803986887187d86dcebaeda22a4dc6823;
S7 W02-S5 Landbook gallery (reused, inspiration only).

## QUALIFICATION SUMMARY
7 logical families, 5 newly appended qualified source records, 2 exact source identities reused. Full acquisition limits and provenance in SOURCE_QUALIFICATION.md.

## VOCABULARY SUMMARY
27 evidence-linked working terms in VOCABULARY.md spanning visual/information hierarchy, grouping, proximity, spacing/vertical rhythm, content width/line length, regions, content roles, metadata, surface/container/card/tile/pane/sidebar/section/grid, responsive composition, density, visual weight, scannability, progressive emphasis, heading semantics and whitespace. Provisional terms are labeled; no cross-system numerical standards created.

## OBSERVATION COUNT
30, all OBSERVED. S1=5, S2=5, S3=5, S4=5, S5=5, S6=4, S7=1. All source-linked; no test or user study executed.

## HIGH-CONFIDENCE FINDINGS
- WCAG 2.2 SC 1.3.1, 1.4.3, 1.4.10, 1.4.11, 2.4.6 are normative for their actual scope/exceptions (O01–O05), not a page layout prescription.
- WAI describes heading hierarchy and semantic region navigation, with explicit sidebar heading caveat (O06–O09).
- GOV.UK describes service-reading widths and small-screen-first layouts and allows wider content when required (O11–O15).
- Primer docs describe focused experiences and viewport-aware composition (O21–O25).
- Pinned PageLayout code defines layout slots, CSS width/pane variables and resize/test intentions (O26–O29). HIGH confidence these source constructs exist, NOT that runtime is accessible.

## LOWER-CONFIDENCE FINDINGS
- Carbon indexed official-page text supports consistent 8px/2x geometry, key lines, proximity/hierarchy and editorial-vs-dense models, but direct opening failed (O16–O20).
- Outcome claims about actual user scannability were not measured; W03-A01 inferred from hierarchy guidance is LOW confidence.
- Landbook category listing was observed (O30), but zero detail previews were successfully opened. No visual composition observations are claimed for showcased websites.

## HIERARCHY FINDINGS
Actual topic/subtopic and region relationships need both meaningful presentation and programmatic identification where normative success criteria apply. Type, weight, proximity, headings, alignment and content width provide different cues. A visual heading is not automatically a semantic heading.

## GROUPING FINDINGS
Grouping can use proximity, aligned key lines, title/subtitle relationships, semantic regions and structural columns; a bordered card is not required for each group. Nested GOV.UK/Primer layout wrappers can be legitimate implementation mechanisms, not self-evident anti-patterns.

## DENSITY FINDINGS
Carbon distinguishes centered editorial, bounded docs and full-width high-density layouts by task. Primer encourages focus/minimizing distractions. There is no universal card count, ideal whitespace volume or density cutoff in the reviewed corpus.

## RESPONSIVE-COMPOSITION FINDINGS
WAI adaptation, GOV.UK small-screen-first, Primer viewport range decomposition and pinned PageLayout responsive pane mechanics describe alternative techniques. WCAG Reflow governs only specified contexts/exceptions. Code/stories do not prove executed browser behavior.

## NORMATIVE VS REFERENCE VS IMPLEMENTATION VS INSPIRATION
- S1 WCAG: normative SC text only.
- S2 WAI: official explanatory teaching, not normative SC.
- S3 GOV.UK, S4 Carbon, S5 Primer: official system-specific reference guidance.
- S6 pinned code: PRIMARY_IMPLEMENTATION for exact snapshot, test intent only.
- S7 Landbook: INSPIRATION_ONLY listing metadata, no engineering or visual showcase findings.

## ANTI-SLOP HYPOTHESES
See ANTI_SLOP_ANALYSIS.md for 10 distinct harm/context/evidence/counterexample reviews.

SUPPORTED FOR LOW-CONFIDENCE CANDIDATE ONLY:
- UNIFORM_VISUAL_WEIGHT / UNDIFFERENTIATED_CONTENT_PRIORITY -> W03-A01, scoped to unequal information roles whose emphasis is undifferentiated.

WEAK / INSUFFICIENT:
- DECORATIVE_CARD_OVERLOAD
- CONTAINER_NESTING_WITHOUT_INFORMATION_VALUE
- EXCESSIVE_SECTION_FRAGMENTATION
- WHITESPACE_WITHOUT_STRUCTURAL_PURPOSE
- DECORATIVE_ICON_SATURATION
- MEANINGLESS_METRIC_SURFACES

REJECTED OR MISFRAMED AS BLANKET CLAIM:
- GENERIC_HERO_COMPOSITION (no individually inspected Landbook example)
- FAKE_DASHBOARD_DENSITY (contradicted by legitimate Carbon high-density model)
- WEAK_INFORMATION_HIERARCHY is addressed by programmatic relationship and grouping evidence, not accepted as a broad anti-style verdict.

## CONTRADICTIONS AND COUNTEREXAMPLES
- GOV.UK roughly 75 characters/line vs Primer roughly 80: SYSTEM_CONVENTION.
- Constrained reading vs full-width high-density: CONTEXTUAL_TRADEOFF by task.
- Small-screen-first one-column vs responsive pane positioning: SCOPE_NARROWING.
- Visual grid/React Pane != WAI named semantic landmark automatically.
- WCAG contrast/reflow constraints != brand aesthetics.
- Primer docs unpinned vs implementation exact SHA: VERSION_SPLIT.
- Carbon official indexed only, Landbook previews inaccessible: EVIDENCE LIMITATION.

## VERSION LIMITS
WCAG 2.2 Recommendation Dec 12 2024; Carbon indexed page claims Sep 25 2026 update; Primer React exactly 7f5303d803986887187d86dcebaeda22a4dc6823. WAI/GOV.UK/Primer docs and Landbook unpinned. No cross-version equivalence inferred.

## LICENSE / STORAGE LIMITS
WCAG/WAI W3C copyright and document-use restrictions; GOV.UK content OGL v3.0 except exceptions; primer/react MIT verified; Carbon/Primer online docs/Landbook page reuse unknown => references only. Metadata, lawful bounded summaries and observations stored. No screenshots, copied designs, packs or third-party code stored.

## PATTERN CANDIDATES
- W03-P01 Semantic and visual region alignment — CANDIDATE, MEDIUM.
- W03-P02 Purpose-bounded reading width — CANDIDATE, MEDIUM.
- W03-P03 Content-first responsive composition — CANDIDATE, MEDIUM.

## ANTI-PATTERN CANDIDATE
- W03-A01 Undifferentiated content priority — CANDIDATE, LOW. Requires actual target evaluation/user context before Maintainer promotion.

## WHAT SHOULD NOT BE GENERALIZED
Neither 8px nor 1020px nor ~75/~80 chars is normative for all sites. Full-width/high-density is not automatically slop. Nested wrappers are not automatically bad. A visual box does not automatically establish landmarks; reading code is not a runtime test. Landbook listing is not visual inspection. No "AI-looking" engineering finding exists.

## ACCEPTED PRIOR KNOWLEDGE PRESERVED
- W02-P01 ACCEPTED/MEDIUM (bounded primary action group).
- W02-A01 ACCEPTED/MEDIUM (bounded competing primary controls).
- W02-P02 CANDIDATE/DEFERRED. Unchanged.

## UNRESOLVED QUESTIONS
Carbon full-page verification; Landbook blocked individual showcases; measured scannability; semantic/visual mapping in real target; responsive keyboard and focus behavior; exact doc versions; licenses for restricted-reference pages; card/surface ontology. Details in UNRESOLVED.md.

## WORKER RECOMMENDATION
READY_FOR_MAINTAINER_REVIEW, for independent decision on evidence limitations and 3+1 candidate set. No K7 promotion, W04, framework selection, main merge or self-acceptance.