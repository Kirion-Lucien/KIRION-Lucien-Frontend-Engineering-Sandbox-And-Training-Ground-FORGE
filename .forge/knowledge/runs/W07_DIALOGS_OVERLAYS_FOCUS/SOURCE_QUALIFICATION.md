# W07 — K2 SOURCE QUALIFICATION

## Six logical families — source type and evidence capability

| Source | Registry ID | Qualification | Type / authority | What the source could support in later authorized K3 | What it cannot establish |
|---|---|---|---|---|---|
| S1 W3C WCAG 2.2 | `W02-S1` REUSED | QUALIFIED, unchanged identity | `OFFICIAL_STANDARD / PRIMARY_NORMATIVE` | Applicable criterion text/levels/conditions within WCAG 2.2: e.g. 1.3.1, 1.4.13, 2.1.1, 2.1.2, 2.4.3, 2.4.7, 2.4.11, 2.5.2, 4.1.2 | A universal UI dialog model, browser implementation or all-overlay component standard |
| S2 WAI APG dialog/tooltip/disclosure | `W07-S2` NEW | QUALIFIED WITH GAPS | `ACCESSIBILITY_REFERENCE / OFFICIAL_REFERENCE` | Explanatory APG patterns/examples/interaction expectations within available pages; modal dialog, tooltip, disclosure | Binding WCAG normative text, executable test result, standalone `/patterns/dialog/` (404) contents, consensus-based tooltip guidance (page WIP) |
| S3 WHATWG HTML | `W07-S3` NEW | QUALIFIED | `OFFICIAL_STANDARD / PRIMARY_NORMATIVE` | Native `dialog`, `popover`, `inert`, light-dismiss/top-layer algorithms where present and current as of retrieval | Accessibility or behavior of a particular browser, library or deployed application |
| S4 USWDS Modal | `W07-S4` NEW | QUALIFIED | `DESIGN_SYSTEM / OFFICIAL_REFERENCE` | USWDS Modal design component usage, accessibility and implementation documentation in its own system | Universal obligation to use USWDS Modal or its implementation as a web-wide standard |
| S5 Primer Dialog/Tooltip/Popover/Overlay | `W07-S5` NEW | QUALIFIED | `DESIGN_SYSTEM / OFFICIAL_REFERENCE` | First-party product conventions for four reached component pages | Normative modality rules; proof that live docs match pinned React snapshot |
| S6 pinned `primer/react` | `W07-S6` NEW | QUALIFIED, VERSION-BOUND | `COMPONENT_LIBRARY / PRIMARY_IMPLEMENTATION` | Exact implementation choices and existing test intent at immutable SHA in five bounded files | Executed test PASS, runtime/browser/keyboard/AT behavior, other versions, production correctness |

## Source identity, dates, independence and confidence boundaries

- **S1:** W3C Recommendation 12 December 2024; exact previously accepted `W02-S1`. Direct official URL reopened 2026-10-08; no new registry identity. This source is normative only in its actual success criteria including conformance level/exception conditions.
- **S2:** W3C WAI APG, retrieved 2026-10-08. Modal-dialog/tooltip/disclosure URLs exist; standalone `/patterns/dialog/` is 404; tooltip explicitly WIP/non-consensus. APG is informative official practice guidance, **not independent normative corroboration of WCAG** even though W3C publishes both. Current page revision unpinned.
- **S3:** WHATWG official HTML Living Standard, retrieved 2026-10-08; mutable by design. Native HTML specification is independently normative for HTML platform behavior (not the same normative scope as WCAG conformance); no frozen commit/review draft pinned.
- **S4:** USWDS Modal page reachable 2026-10-08; exact version/build unavailable in this run. It carries USWDS design-system conventions and may contain implementation/a11y cautions requiring scope-specific later verification.
- **S5:** Primer four product pages reachable 2026-10-08; live currentness beyond retrieval and exact build unknown. Same publisher as S6 but **docs and implementation are not independent votes** on correctness.
- **S6:** `primer/react@7f5303d803986887187d86dcebaeda22a4dc6823` exact Git commit. Five file blob SHAs + MIT license blob recorded in SOURCE_DISCOVERY. Distinct bounded component subtree from existing `W02-S4` Button, `W03-S6` PageLayout, `W05-S6` Navigation and `W06-S6` Forms; same repo commit **does not make identical evidence target**.

**License/storage:** S1 W3C `PUBLIC_REFERENCE_ONLY`; S2 W3C `PUBLIC_REFERENCE_ONLY`; S3 WHATWG CC BY 4.0 `KNOWN_PERMISSIVE` (IPR Policy §7.1.1); S4/S5 documentation `UNKNOWN` (reference only); S6 pinned MIT `KNOWN_PERMISSIVE`. **All five appended Stage A records deliberately use METADATA_ONLY storage**; reference links, metadata, version, rights, limitations and bounded source-capability descriptions only. No external content stored.

## K2 exit limit

Six families qualified at the family level, one requested WAI subpage **unqualified/inaccessible**, tooltip APG **limited / work-in-progress**. Qualification confirms source identity and evidence capability; it does not record observations, compare source claims, accept knowledge or release any later stage. K3/K4/K5/K6/K7 are absent.
