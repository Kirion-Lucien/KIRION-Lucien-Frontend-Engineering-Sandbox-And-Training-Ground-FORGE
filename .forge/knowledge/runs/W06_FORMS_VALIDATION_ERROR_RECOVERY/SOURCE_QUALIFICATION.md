# W06 K1/K2 SOURCE QUALIFICATION

Exactly six logical source families qualified; **W02-S1 reused** for identical W3C WCAG 2.2 Recommendation, **five W06-specific source records appended** because their form targets differ materially from prior composition/navigation/button sources.

| Family | Identity | Source type / authority | Recency and storage |
|---|---|---|---|
| S1 W3C WCAG 2.2 | W02-S1 REUSE | OFFICIAL_STANDARD / PRIMARY_NORMATIVE | Recommendation 2024-12-12 / PUBLIC_REFERENCE_ONLY |
| S2 W3C WAI Forms | W06-S2 NEW | ACCESSIBILITY_REFERENCE / OFFICIAL_REFERENCE | Live docs unpinned / PUBLIC_REFERENCE_ONLY |
| S3 GOV.UK Forms Validation | W06-S3 NEW | DESIGN_SYSTEM / OFFICIAL_REFERENCE | Live unpinned / OGL v3.0 except exceptions |
| S4 USWDS Forms | W06-S4 NEW | DESIGN_SYSTEM / OFFICIAL_REFERENCE | Site advertises v3.13.0, page build unpinned / license UNKNOWN |
| S5 Primer Forms | W06-S5 NEW | DESIGN_SYSTEM / OFFICIAL_REFERENCE | Live docs unpinned / license UNKNOWN |
| S6 pinned primer/react Forms | W06-S6 NEW | COMPONENT_LIBRARY / PRIMARY_IMPLEMENTATION | Exact commit 7f5303d803986887187d86dcebaeda22a4dc6823 / MIT |

**Canonical URLs:** S1 https://www.w3.org/TR/WCAG22/ ; S2 https://www.w3.org/WAI/tutorials/forms/ ; S3 https://design-system.service.gov.uk/patterns/validation/ ; S4 https://designsystem.digital.gov/components/form/ ; S5 https://primer.style/product/components/form-control/ ; S6 https://github.com/primer/react/tree/7f5303d803986887187d86dcebaeda22a4dc6823/packages/react/src/FormControl .

**Specific official subpages:** WAI labels/instructions/grouping/validation/notifications; GOV text-input/error-message/error-summary/question-pages/fieldset/radios/checkboxes; USWDS form/validation/text-input/radio-buttons (direct opens to error-message and fieldset failed); Primer FormControl/TextInput/Select/Checkbox/Radio; pinned corresponding source/components/tests.

**Pinned implementation inspected:** FormControl.tsx, _FormControlContext.tsx, _FormControlContextProvider.tsx, _FormControlValidation.tsx, FormControlLabel.tsx, FormControlCaption.tsx, TextInput.tsx and tests, Select.tsx and tests, Checkbox.tsx and tests, Radio.tsx and tests. Code only at exact commit; tests READ NOT EXECUTED. Source inspected does not prove browser, AT or production behavior.

**Critical historical caveat:** USWDS Validation page's own change log notes deprecation after 3.12.0, and known accessibility/usability issues regarding unnoticed changes. Its immediate-validation example is version-bound and NOT promoted as a preferred current system pattern.

**Scope:** Source class != authority. Same W3C provider does not make WAI explanatory tutorial an extra WCAG criterion or independent normative vote. No source code/docs copied; metadata, summaries, precise URLs and SHA only. Five new scoped records do not duplicate earlier narrower source identities; WCAG exact identity retained.
