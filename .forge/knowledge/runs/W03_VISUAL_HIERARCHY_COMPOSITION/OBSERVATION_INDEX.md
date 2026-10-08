# W03 OBSERVATION INDEX — K3

Total 30, all OBSERVED. Source-linked JSON records at observations/W03-O01.json to observations/W03-O30.json. Each stores exact evidence location, domain, context, evidence kind, version, limitations and timestamp.

| Logical family | Registry source ID | Observation IDs | Count | Authority |
|---|---|---|---:|---|
| S1 WCAG | W02-S1 reused | O01–O05 | 5 | NORMATIVE_TEXT |
| S2 WAI | W03-S2 | O06–O10 | 5 | DOCUMENTATION_STATEMENT |
| S3 GOV.UK | W03-S3 | O11–O15 | 5 | DOCUMENTATION_STATEMENT |
| S4 Carbon | W03-S4 | O16–O20 | 5 | DOCUMENTATION_STATEMENT, indexed official excerpts |
| S5 Primer docs | W03-S5 | O21–O25 | 5 | DOCUMENTATION_STATEMENT |
| S6 PageLayout code | W03-S6 | O26–O29 | 4 | SOURCE_CODE |
| S7 Landbook | W02-S5 reused | O30 | 1 | OTHER: listing metadata only |

## By observation

- O01 WCAG programmatically determinable relationships, 1.3.1.
- O02 WCAG text contrast and exceptions, 1.4.3.
- O03 WCAG reflow and 2D exceptions, 1.4.10.
- O04 WCAG non-text contrast and exemptions, 1.4.11.
- O05 WCAG descriptive heading/label purpose, 2.4.6.
- O06 WAI headings navigable organizational cues.
- O07 WAI ranked heading nesting and fixed-sidebar caveat.
- O08 WAI landmark regions header/footer/nav/main/aside.
- O09 WAI labeled navigation and complementary aside.
- O10 WAI viewport and line-width adaptation advice.
- O11 GOV.UK small-screen-first single column for its system.
- O12 GOV.UK two-thirds text measure and about 75-character lines.
- O13 GOV.UK 1020px default page max with content exception.
- O14 GOV.UK grid row/column and width wrapper examples.
- O15 GOV.UK responsive type scale.
- O16 Carbon 8px mini unit geometry (indexed).
- O17 Carbon key-line alignment (indexed).
- O18 Carbon fit-for-purpose layout and user goals (indexed).
- O19 Carbon hierarchy via size/proximity (indexed).
- O20 Carbon centered/editorial, docs and high-density models (indexed).
- O21 Primer focused, calm uncluttered experience guidance.
- O22 Primer viewport range and multicolumn reduction guidance.
- O23 Primer typographic scale, weight vs color and ~80-character length.
- O24 Primer PageLayout header/content/pane/footer regions.
- O25 Primer PageLayout accessibility expectations.
- O26 Pinned PageLayout containerWidth and region slot configuration.
- O27 Pinned CSS max widths, responsive pane widths and region order variables.
- O28 Pinned pane resize constraints, DragHandle pointer/keyboard code.
- O29 Pinned PageLayout test assertions and TODO (not run).
- O30 Landbook template listing metadata only; two example-detail access failures; no individual visual inspection.

## Evidence boundary

OBSERVATION != RECOMMENDATION. Source inspection is not runtime proof. The same provider's docs and code remain distinct source families when the target/scope differs. Failed Landbook detail retrieval cannot be silently upgraded to visible design findings.