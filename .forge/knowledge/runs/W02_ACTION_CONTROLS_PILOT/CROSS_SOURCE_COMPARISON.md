# W02 CROSS-SOURCE COMPARISON — K4

## A. Semantic purpose

- **Action / submission:** GOV.UK S2/O07 shows saving and progressing through service forms, with documented default submit buttons. Primer S3/O12 describes buttons as action initiators. Pinned code S4/O16 renders Button as native button with type button; callers separately decide submission behavior.
- **Navigation:** GOV.UK S2/O09 demonstrates a start-page link when no form data is submitted. S4/O16 LinkButton defaults to an anchor. This does not establish a blanket standard for all contexts.
- **Destructive action:** GOV.UK S2/O10 warns that warning-button emphasis should be sparing. Primer S3/O12 uses a danger variant sparingly, usually near confirmation. Neither proves a mandated color or universal confirmation procedure.
- **Accessible purpose:** WCAG S1/O05 requires name and role to be programmatically determinable. It does not dictate primary/secondary visual hierarchy.

## B. Hierarchy

- GOV.UK S2/O08 cautions that multiple default buttons reduce impact and complicate next-step identification.
- Primer S3/O12 says not more than one primary in a group and rarely more than one per page.
- Convergent design-system guidance supports **bounded candidates**, not universal law or a numeric rule for independent page regions.
- Visual danger/secondary distinctions do not replace keyboard, accessible naming or other WCAG criteria.

## C. Accessibility and state

- Keyboard: WCAG S1/O01 is normative; S4/O19 shows source-level toolbar-specific horizontal arrow focus behavior, NOT tested runtime behavior.
- Focus: WCAG S1/O02/O03 separately requires visible keyboard focus and prevents focused controls from being entirely obscured. Primer docs S3/O13 claims focus preservation in loading, and S4/O17 shows its wrapper/ARIA strategy; no actual focus test performed.
- Pointer target size: S1/O04 records WCAG minimum and exceptions. No observation establishes the size of displayed showcase or Primer rendered buttons.
- Name/role/value: S1/O05 normative; S4/O16/O17 source constructs native elements and ARIA attributes, which do not prove page-wide conformance.
- Disabled/inactive: S2/O11 warns about confusing disabled controls; S3/O14 distinguishes disabled from interactive inactive; S4/O18 exposes distinct code props. These are contextual alternatives, not the same state.
- Loading/status: S3/O13 and S4/O17 describe spinner, aria-disabled, retained label, status announcement and click suppression. S1/O06 provides status-message criteria; whether a specific rendered announcement meets them remains UNTESTED.

## D. Evidence classes

| Evidence class | Source | Can support | Cannot support |
|---|---|---|---|
| Normative accessibility | S1 WCAG | Success criteria, levels, exceptions | Primary-action color/number |
| Official design-system guidance | S2 GOV.UK, S3 Primer docs | System-specific conventions | Universal normative requirement or measured success |
| Primary implementation | S4 pinned primer/react | Pinned code structure, prop handling, test intent | Actual passing tests, browser/AT behavior, current main |
| Inspiration/metadata | S5 Landbook | Its listing, filtering and curation metadata | Showcased sites' real visual CTA hierarchy, DOM, focus, performance or readiness |

## E. Contradictions and counterexamples

1. **Navigation semantics:** GOV.UK start-page anchor example includes role button; pinned Primer LinkButton uses anchor by default. The interaction/keyboard implications are context-dependent and were not runtime-tested. UNRESOLVED.
2. **Disabled and inactive:** GOV.UK cautions against disabled controls; Primer offers an interactive inactive state and a loading strategy. CONTEXTUAL TRADEOFF, not contradiction by majority vote.
3. **Primary action scope:** Both official systems constrain competing primaries; separate, unrelated task groups can legitimately have independent local primaries. SCOPE NARROWING.
4. **Version mismatch:** Live Primer docs are not pinned to the historical code SHA. Do not claim they are synchronized. VERSION SPLIT / UNRESOLVED.
5. **Visual versus normative:** Design prominence neither proves nor substitutes for keyboard, focus, target, name/role/state or status-message requirements. DIFFERENT EVIDENCE CLASSES.

## K5 boundary

Proposed: patterns W02-P01, W02-P02; anti-pattern W02-A01. All CANDIDATE, no K7.