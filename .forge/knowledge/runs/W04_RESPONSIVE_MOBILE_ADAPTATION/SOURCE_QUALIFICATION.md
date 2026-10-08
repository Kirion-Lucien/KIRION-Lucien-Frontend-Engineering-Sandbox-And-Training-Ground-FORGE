# W04 SOURCE QUALIFICATION — K1 / K2

Exactly six logical source families qualified and directly inspected in scope. All six already have **materially matching W02/W03 qualified source IDs**, so no new registry records are necessary or allowed just to rename the inquiry. Entire registry retained byte-for-byte.

| Family | Reused source ID | Type / authority | Coverage |
|---|---|---|---|
| S1 W3C WCAG 2.2 | W02-S1 | OFFICIAL_STANDARD / PRIMARY_NORMATIVE | WCAG 2.2 Recommendation, Dec 12 2024; 8 named SC |
| S2 W3C WAI mobile/tips | W03-S2 | ACCESSIBILITY_REFERENCE / OFFICIAL_REFERENCE | Mobile Accessibility and Designing Tips |
| S3 GOV.UK | W03-S3 | DESIGN_SYSTEM / OFFICIAL_REFERENCE | Layout and Type Scale |
| S4 Carbon | W03-S4 | DESIGN_SYSTEM / OFFICIAL_REFERENCE | 2x Grid overview and guidelines |
| S5 Primer docs | W03-S5 | DESIGN_SYSTEM / OFFICIAL_REFERENCE | Layout; PageLayout; Accessibility; Typography |
| S6 Primer code | W03-S6 | COMPONENT_LIBRARY / PRIMARY_IMPLEMENTATION | PageLayout source/tests/stories, responsive values/attribute utilities, pinned SHA |

## S1 — WCAG

Canonical: https://www.w3.org/TR/WCAG22/ ; pinned Recommendation https://www.w3.org/TR/2024/REC-WCAG22-20241212/. Normative only for success criteria and specified exceptions. Relevant: 1.3.1 (A), 1.3.2 (A), 1.3.4 (AA), 1.4.4 (AA), 1.4.10 (AA), 1.4.12 (AA), 2.4.3 (A), 2.5.8 (AA). Reuse existing PUBLIC_REFERENCE_ONLY record (W3C document-use rules); do not copy specification text. Not evidence for universal breakpoints or mobile navigation.

## S2 — WAI

https://www.w3.org/WAI/standards-guidelines/mobile/ and https://www.w3.org/WAI/tips/designing/. Official explanatory reference, not a new WCAG standard. WAI explicitly says W3C has no independent mobile accessibility guideline and identifies an in-progress mobile-mapping draft. Reference-only W3C provenance under reused W03-S2; no new normative SC invented. Current page revision unpinned.

## S3 — GOV.UK

https://design-system.service.gov.uk/styles/layout/ and https://design-system.service.gov.uk/styles/type-scale/. Official GOV.UK design conventions; first-party content, not WCAG or broad research. Small-screen-first and reading-width guidance, with exceptions and type-scale revision stated for Frontend v6.0.0+. OGL v3.0 content (except stated exceptions), attributed summaries. Doc page revisions not SHA-pinned.

## S4 — Carbon

https://www.carbondesignsystem.com/building-blocks/foundations/2x-grid/overview and https://www.carbondesignsystem.com/building-blocks/foundations/2x-grid/guidelines. Official IBM system-specific guidance, marked updated Sep 25 2026 in indexed results. **Direct open failed on both URLs**; source text limited to official indexed page extracts. Observations W04-O18–O21 have MEDIUM confidence and explicitly preserve this access limitation. Specific reuse license UNKNOWN; reference-only summaries/observations, no copied assets.

## S5 — Primer docs

https://primer.style/product/getting-started/foundations/layout/ ; https://primer.style/product/components/page-layout/ ; https://primer.style/product/components/page-layout/accessibility/ ; https://primer.style/product/getting-started/foundations/typography/. First-party Primer guidance for its own product system. Page version not pinned; reuse license UNKNOWN => reference-only. Not assumed release-identical to pinned primer/react implementation.

## S6 — pinned primer/react

Commit: https://github.com/primer/react/commit/7f5303d803986887187d86dcebaeda22a4dc6823. Exact SHA verified and reused from qualified W03-S6; MIT LICENSE verified in prior accepted W03 qualification.

Inspected at exact SHA, no external repository mutation:
- packages/react/src/PageLayout/PageLayout.tsx
- packages/react/src/PageLayout/PageLayout.module.css
- packages/react/src/PageLayout/PageLayout.responsive.stories.tsx
- packages/react/src/PageLayout/PageLayout.test.tsx
- packages/react/src/PageLayout/usePaneWidth.ts
- packages/react/src/PageLayout/DragHandle.tsx
- packages/react/src/hooks/useResponsiveValue.ts
- packages/react/src/internal/utils/getResponsiveAttributes.ts

Source and tests/stories READ, not executed. Current main not substituted. Breakpoint constants belong to Primer code version only.

## K2 disposition

Six source families, six reused IDs, **zero added registry sources**. No independent seventh source. Source qualification alone conveys no pattern acceptance.
