# W02 SOURCE QUALIFICATION — K1/K2

Qualification means source identity and evidence limits are recorded; it does not accept conclusions. Source registry contains exactly five logical families.

## W02-S1 — W3C WCAG 2.2

- Canonical: https://www.w3.org/TR/WCAG22/
- Verified fixed Recommendation: https://www.w3.org/TR/2024/REC-WCAG22-20241212/ (12 December 2024).
- OFFICIAL_STANDARD; PRIMARY_NORMATIVE only for actual accessibility criteria within levels/scope/exceptions.
- Status ACTIVE; recency VERSION_BOUND.
- Copyright W3C / document-use rules; PUBLIC_REFERENCE_ONLY, SUMMARIES_AND_OBSERVATIONS.
- Examined SC 2.1.1, 2.4.7, 2.4.11, 2.5.8, 4.1.2, 4.1.3.
- Does not support claims about number/color of primary actions.

## W02-S2 — GOV.UK Design System Button

- Canonical: https://design-system.service.gov.uk/components/button/
- DESIGN_SYSTEM; OFFICIAL_REFERENCE for its own guidance, not universal normative law.
- ACTIVE; recency UNKNOWN (page release not pinned).
- Footer: Open Government Licence v3.0 except where stated; KNOWN_PERMISSIVE, SUMMARIES_AND_OBSERVATIONS with attribution.
- Examined How it works, Default, Start, Secondary, Warning, Disabled and Grouping buttons.
- No independent usability test, WCAG conformance test or deployment inspection.

## W02-S3 — Primer Product Button documentation

- Canonical: https://primer.style/product/components/button/
- DESIGN_SYSTEM; OFFICIAL_REFERENCE for Primer's own product UI.
- ACTIVE; recency UNKNOWN (documentation release not pinned).
- Public documentation reuse license not verified: UNKNOWN / reference only / SUMMARIES_AND_OBSERVATIONS.
- Examined style variants, leading/trailing visuals, loading, loading with visuals, inactive, props.
- Do not assume it is the same version as the pinned implementation.

## W02-S4 — Primer React implementation

- Exact immutable source: https://github.com/primer/react/commit/7f5303d803986887187d86dcebaeda22a4dc6823
- COMPONENT_LIBRARY; PRIMARY_IMPLEMENTATION for this snapshot only.
- ACTIVE; recency VERSION_BOUND; source SHA verified through GitHub Git data.
- MIT license verified from pinned LICENSE file; KNOWN_PERMISSIVE; SUMMARIES_AND_OBSERVATIONS without vendoring.
- Exact inspected source and test paths:
  - packages/react/src/Button/Button.tsx
  - packages/react/src/Button/ButtonBase.tsx
  - packages/react/src/Button/types.ts
  - packages/react/src/Button/LinkButton.tsx
  - packages/react/src/Button/__tests__/Button.test.tsx
  - packages/react/src/ButtonGroup/ButtonGroup.tsx
- Directory discovery was limited to root, packages/, packages/react/, packages/react/src/, Button/, ButtonGroup/ and Button/__tests__/.
- Source/test files inspected only; NO tests executed, NO browser/AT conformance claimed, NO use of current main and NO repo mutation.

## W02-S5 — Landbook gallery

- Canonical: https://land-book.com/design/website/landing-page
- DESIGN_INSPIRATION; INSPIRATION_ONLY; ACTIVE; recency UNKNOWN.
- License UNKNOWN, reference only; METADATA_ONLY. No screenshots, assets or templates copied.
- Visible listing title, filters, example titles/creators and listing actions were inspected.
- Individually inspected showcased examples: 0 (under maximum 3).
- No claim about showcased pages' CTA hierarchy, semantics, accessibility, responsiveness, performance or architecture.

## K2 outcome

Exactly five qualified sources W02-S1 through W02-S5. No sixth independent source. Qualification is metadata, not acceptance.