# W07 — REGISTRY IDENTITY AND LINK MAP (K2)

**Initial registry:** 20 qualified source identities at exact governance input `64a292f24938e94ecc48f0379ad92ac72a037389`. Preserved order/contents of existing entries; appended exactly five W07-specific qualified entries. Registry after: 25. `schema_version` unchanged. No K3 observations.

| Logical family | Final qualified registry ID | Operation | Exact identity/scoping basis |
|---|---|---|---|
| S1 WCAG 2.2 | `W02-S1` | REUSED, no mutation | Same canonical https://www.w3.org/TR/WCAG22/, Recommendation 12 Dec 2024 |
| S2 WAI APG dialogs/tooltip/disclosure | `W07-S2` | APPENDED | https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/ and exact WAI APG pattern subpages, distinct from W03 headings/W05 menus/W06 forms |
| S3 WHATWG HTML Living Standard | `W07-S3` | APPENDED | https://html.spec.whatwg.org/multipage/interactive-elements.html#the-dialog-element plus popover and inert official sections; no previous WHATWG source |
| S4 USWDS Modal | `W07-S4` | APPENDED | https://designsystem.digital.gov/components/modal/ distinct component target from W05 header and W06 form source IDs |
| S5 Primer Dialog, Tooltip, Popover, Overlay docs | `W07-S5` | APPENDED | https://primer.style/product/components/dialog/ family, distinct from Primer button/layout/navigation/forms docs |
| S6 pinned Primer Dialog/Overlay/Tooltip/Popover | `W07-S6` | APPENDED | Same `primer/react@7f5303d803986887187d86dcebaeda22a4dc6823` repository revision as past scoped source records but **different exact component subtree paths** |

## Duplicate identity defense

Existing precise scope references:
- `W02-S4`: `packages/react/src/Button`
- `W03-S6`: `packages/react/src/PageLayout`
- `W05-S6`: `packages/react/src/{NavList,UnderlineNav,Breadcrumbs}`
- `W06-S6`: `packages/react/src/{FormControl,TextInput,Select,Checkbox,Radio}`
- **New `W07-S6`:** `packages/react/src/{Dialog,Overlay,Tooltip,Popover}`, five exact bounded files including Dialog test. Broad repository and SHA overlap is *explicitly not* a duplicate of file-family evidence identity.

Other previously qualified W3C/USWDS/Primer entries have different canonical documents/component scopes. No mutation to their source records. K3 must use exact assigned IDs, not hypothesized `W07-S1`; W07 family S1 is `W02-S1`.

## Unqualified references (do NOT assign source IDs)

- `https://www.w3.org/WAI/ARIA/apg/patterns/dialog/` — HTTP 404 at discovery. No replacement or separately qualified non-modal guide was imported.
- Tooltip at `https://www.w3.org/WAI/ARIA/apg/patterns/tooltip/` remains **inside qualified W07-S2**, but the official page marks it WIP/no task-force consensus. Do not classify it as consensus pattern.

## Linkage checks
Exactly six logical families resolve to six different qualified IDs, none duplicates an existing ID. No observations, patterns or anti-patterns exist at Stage A; observation-linkage check is NOT APPLICABLE (zero).
