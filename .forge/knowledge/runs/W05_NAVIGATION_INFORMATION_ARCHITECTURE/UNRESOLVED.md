# W05 UNRESOLVED / RISKS

1. **No target product IA.** No site taxonomy, route map, application journey, customer task priority, existing link structure or localization requirements were supplied. No universal product navigation structure inferred.
2. **User research not executed.** Navigation label clarity, depth/breadth, megamenu discoverability and breadcrumb comprehension remain unevaluated in W05. USWDS user-testing recommendations are guidance, not local evidence.
3. **No runtime checks.** Browser navigation, Tab/arrow keyboard behavior, focus order, assistive-technology landmark output, responsive menu recoverability and breadcrumb overflow were not tested.
4. **Primer version boundary.** Product docs are live/unpinned while implementation is exact primer/react@7f5303d803986887187d86dcebaeda22a4dc6823; no release equivalence assumed.
5. **GOV.UK header direct retrieval.** The specific GOV.UK header direct page failed to open; related official Navigate a Service and Service Navigation references supplied scope information. No direct header-component inspection claim.
6. **Licensing.** USWDS navigation docs and Primer documentation reuse statuses remain UNKNOWN until separately verified; no third-party code/docs copied.
7. **WCAG AAA.** SC 2.4.8 Location is AAA. W05 does not promote it to AA or mandate breadcrumbs.
8. **Multiple Ways.** SC 2.4.5 Level AA explicitly excludes pages within processes; product page-set relationships not inventoried.
9. **Breadcrumb termination variants.** GOV.UK recommends ending at parent; Primer and USWDS examples include current page; contextual difference left intact.
10. **Tabs ambiguity.** GOV.UK in-page tabs and Primer URL-backed UnderlineNav are distinguishable products; system-specific examples do not establish universal tab roles or browser behavior.
11. **Application menu boundaries.** WAI desktop application-menu guidance requires role/keyboard alignment; W05 made no menu interaction implementation or AT trial.
12. **Responsive current paths.** Pinned overflow mechanics observed, but no runtime proof that hidden links, aria-current or focus behave as intended in actual product.
13. **Prior authority preserved.** W02-P02/W03-A01 remain CANDIDATE/DEFERRED. W04 accepted patterns and anti-patterns govern responsive route behavior; W05 may not re-disposition.
14. **K7 and W06 blocked.** All W05 candidates await independent Maintainer decision.
