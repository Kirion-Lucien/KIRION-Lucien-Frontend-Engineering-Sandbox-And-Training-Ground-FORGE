# W05 SOURCE QUALIFICATION (K1/K2)

Six logical source families. One **existing exact normative** identity reused; five new **navigation-specific** identities append to source registry. Registry membership does not imply acceptance.

| S | ID | Primary type | Authority | Qualification |
|---|---|---|---|---|
| S1 WCAG 2.2 | W02-S1 (reuse) | OFFICIAL_STANDARD | PRIMARY_NORMATIVE | Exact same W3C WCAG 2.2 Recommendation already qualified, distinct navigation SCs examined |
| S2 WAI menus/regions | W05-S2 (new) | ACCESSIBILITY_REFERENCE | OFFICIAL_REFERENCE | Navigation/menu targets materially distinct from W03-S2's composition/headings focus; some overlap in WAI region tutorial acknowledged |
| S3 GOV.UK service navigation | W05-S3 (new) | DESIGN_SYSTEM | OFFICIAL_REFERENCE | Component/pattern navigation target differs from W02-S2 Button and W03-S3 Layout/Type |
| S4 USWDS navigation | W05-S4 (new) | DESIGN_SYSTEM | OFFICIAL_REFERENCE | New officially published U.S. government design-system corpus |
| S5 Primer navigation docs | W05-S5 (new) | DESIGN_SYSTEM | OFFICIAL_REFERENCE | NavList/Breadcrumbs/UnderlineNav target differs from W02 Button, W03 PageLayout |
| S6 pinned primer/react nav | W05-S6 (new) | COMPONENT_LIBRARY | PRIMARY_IMPLEMENTATION | New navigation-specific source paths at same pinned repo SHA, distinct from W02 Button and W03 PageLayout |

## Exact versions and evidence

- **WCAG:** W3C Recommendation 2024-12-12, https://www.w3.org/TR/WCAG22/. Only success-criterion language normative; preserve levels and exceptions. W3C license PUBLIC_REFERENCE_ONLY as prior registry.
- **WAI:** https://www.w3.org/WAI/tutorials/menus/, /structure/, /application-menus/, and /page-structure/regions/, /headings/. W3C tutorial non-normative guidance. Document-use restrictions; summaries only. Live page version not pinned.
- **GOV.UK:** https://design-system.service.gov.uk/patterns/navigate-a-service/ plus service-navigation, govuk-header, breadcrumbs, back-link, tabs, skip-link. GOV.UK header direct open failed; GOV.UK header/site role inferred only from first-party navigate-a-service pattern. OGL v3.0 except stated exclusions, summary storage. Live build unpinned.
- **USWDS:** https://designsystem.digital.gov/components/header/ plus headers/basic, header/extended, side-navigation, breadcrumb. Official component documentation displays download v3.13.0. Exact documentation snapshot is not code-pin verified. License not checked = UNKNOWN/reference-only.
- **Primer docs:** https://primer.style/product/ui-patterns/navigation/ plus nav-list, breadcrumbs guidelines/accessibility and underline-nav guidelines/accessibility. Live first-party docs, no exact release SHA. License UNKNOWN/reference-only.
- **Pinned code:** primer/react@7f5303d803986887187d86dcebaeda22a4dc6823. Inspected NavList.tsx, NavList.module.css, NavList.test.tsx; UnderlineNav.tsx, UnderlineNavItem.tsx, UnderlineNav.module.css, UnderlineNav.test.tsx; Breadcrumbs.tsx, Breadcrumbs.module.css. Navigation code license MIT at pinned snapshot, validated by accepted prior source qualification. **Only source/test files read; tests not executed.**

## Independence, licensing, and limitations

WAI and WCAG share publisher but serve explanatory vs normative roles and are not independent normative votes. GOV.UK, USWDS, Primer offer different institutional contexts. Exact code proves only the pinned implementation choices, not current live component operation. Store metadata, URLs, structured observation summaries and SHA; no external source vendoring or copying.

No seventh family; no framework/IA-depth law. Source identity and currentness subject to the precise reference caveats above.
