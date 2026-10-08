# W03 SOURCE QUALIFICATION — K1/K2

Seven logical source families. Five new W03 source records, two exact W02 source identities reused: W02-S1 (WCAG) and W02-S5 (Landbook). No ambiguous duplicate registry entries. Source qualification is not pattern acceptance.

## S1 — W02-S1, WCAG 2.2

Canonical: https://www.w3.org/TR/WCAG22/
Fixed Recommendation: https://www.w3.org/TR/2024/REC-WCAG22-20241212/ ; date December 12, 2024.
OFFICIAL_STANDARD / PRIMARY_NORMATIVE for actual Success Criteria only.
Sections: 1.3.1 Info and Relationships; 1.4.3 Contrast Minimum; 1.4.10 Reflow; 1.4.11 Non-text Contrast; 2.4.6 Headings and Labels.
PUBLIC_REFERENCE_ONLY, W3C copyright/document-use rules, SUMMARIES_AND_OBSERVATIONS.
Does not mandate cards, spacing scales, a grid, a typography scale or an ideal content width.

## S2 — W03-S2, W3C WAI explanatory guidance

https://www.w3.org/WAI/tips/designing/
https://www.w3.org/WAI/tutorials/page-structure/headings/
https://www.w3.org/WAI/tutorials/page-structure/regions/

ACCESSIBILITY_REFERENCE / OFFICIAL_REFERENCE, not PRIMARY_NORMATIVE. W3C copyright/document-use; PUBLIC_REFERENCE_ONLY, SUMMARIES_AND_OBSERVATIONS. Version unpinned / currency UNKNOWN.
Observed heading roles, rank advice and exceptions, page/landmark regions, complementary content, viewport adaptation. Explanatory guidance must never be presented as new WCAG SC text.

## S3 — W03-S3, GOV.UK

https://design-system.service.gov.uk/styles/layout/
https://design-system.service.gov.uk/styles/type-scale/

DESIGN_SYSTEM / OFFICIAL_REFERENCE for GOV.UK service design. OGL v3.0 except stated exceptions, KNOWN_PERMISSIVE, attributed SUMMARIES_AND_OBSERVATIONS. Version unpinned / currency UNKNOWN.
Small-screen-first and two-thirds reading-column guidance, default width 1020px with exceptions, responsive typography examples; none universal.

## S4 — W03-S4, IBM Carbon 2x Grid

https://www.carbondesignsystem.com/building-blocks/foundations/2x-grid/overview
https://www.carbondesignsystem.com/building-blocks/foundations/2x-grid/guidelines

DESIGN_SYSTEM / OFFICIAL_REFERENCE for IBM/Carbon conventions. Search-indexed official excerpts showed last update September 25, 2026. Direct open failed with internal error: ONLY indexed official snippets examined; NOT full-page inspection.
Concepts covered: 8px mini unit, key lines, content-fit hierarchy, editorial/product-docs/high-density style models. Observations MEDIUM confidence due retrieval limitation.
License unverified UNKNOWN, reference-only and SUMMARIES_AND_OBSERVATIONS; no code or design artifacts copied.

## S5 — W03-S5, Primer design documentation

https://primer.style/product/getting-started/foundations/layout/
https://primer.style/product/getting-started/foundations/typography/
https://primer.style/product/components/page-layout/
https://primer.style/product/components/page-layout/accessibility/

DESIGN_SYSTEM / OFFICIAL_REFERENCE for GitHub/Primer experiences. No pinned docs release. Exact webpage reuse license UNKNOWN -> reference only, SUMMARIES_AND_OBSERVATIONS.
Claims cover focused layout, responsive viewport ranges, reading/type rhythm, region definitions and PageLayout accessibility guidance. Not WCAG norms, and not assumed version-equivalent to pinned code.

## S6 — W03-S6, pinned primer/react PageLayout

Commit: https://github.com/primer/react/commit/7f5303d803986887187d86dcebaeda22a4dc6823
COMPONENT_LIBRARY / PRIMARY_IMPLEMENTATION for this exact immutable snapshot.
MIT verified from pinned repository LICENSE. KNOWN_PERMISSIVE, SUMMARIES_AND_OBSERVATIONS; no vendoring.

Inspected paths, all at exact SHA:
- packages/react/src/PageLayout/PageLayout.tsx
- packages/react/src/PageLayout/PageLayout.module.css
- packages/react/src/PageLayout/PageLayout.test.tsx
- packages/react/src/PageLayout/usePaneWidth.ts
- packages/react/src/PageLayout/DragHandle.tsx
- packages/react/src/PageLayout/PageLayout.responsive.stories.tsx

Read-only PageLayout directory discovery; no unrelated component exploration. Tests/stories read but NOT EXECUTED. No browser output, usability or accessibility conformance proven.

## S7 — W02-S5, Landbook gallery reused

https://land-book.com/design/website/landing-page
DESIGN_INSPIRATION / INSPIRATION_ONLY; license UNKNOWN, METADATA_ONLY.
Accessible category listing contained template names, creators and listing actions. Two individual detail links attempted: one timed out and one returned HTTP 403. **Zero** individual showcase previews were successfully inspected (maximum allowed: 3).
No screenshots, page HTML, assets, design packs or claims about showcased composition/semantics/responsiveness/performance were recorded.

## Registry result

Historical W02-S1 to W02-S5 unchanged. Appended only W03-S2 through W03-S6; total registry count 10, representing exactly seven logical W03 source families.