# W03 CROSS-SOURCE COMPARISON — K4

## A. Hierarchy mechanisms

- **Normative boundaries:** WCAG requires conveyed information relationships to be programmatically determinable or text-equivalent (O01), headings/labels to describe purpose (O05), and applicable contrast/reflow criteria (O02–O04). It does not prescribe CSS grid, card count, exact page width or aesthetic hierarchy.
- **Heading/typography:** WAI rank nesting (O06,O07), GOV.UK responsive type styles (O15), Primer weight/line-height guidance (O23) and Carbon content priority/proximity (O19) all describe different mechanisms. A large visible word alone does not automatically create a semantic heading.
- **Width and measure:** GOV.UK uses two-thirds service column and ~75 characters/line (O12), Primer offers ~80 as guideline (O23), while Carbon distinguishes wide high-density layouts (O20). These are contextual models, not competing WCAG numbers.
- **Alignment and whitespace:** Carbon's 8px mini unit/key-line scheme (O16,O17) shows a concrete system-specific rhythm; no corpus result proves 8px always optimal.
- **Action emphasis:** Existing W02-P01 and W02-A01 are ACCEPTED only for bounded connected decision groups. They may support local action hierarchy conceptually but do not become whole-page layout law. W02-P02 remains DEFERRED/CANDIDATE.

## B. Grouping

Grouping can be conveyed through proximity and alignment (Carbon O17,O19), a meaningful title/subheading (WAI O06,O07), semantic page regions (WAI O08,O09), or intentional columns/content areas (GOV O14, Primer O24,O26).

A visible border/card can be an optional design surface; none of these sources establishes that every logical group needs a card, or that every CSS wrapper implies a semantic landmark.

Counterexample: GOV.UK explicitly uses nested structural width/grid wrappers (O14) and pinned Primer code uses nested layout wrappers (O26); presence of nesting alone is not a defect.

## C. Density

Carbon O20 distinguishes centered editorial, bounded product/docs and full-width high-density interface models by task/content needs. Thus high density can be legitimate.

Primer O21 says focused content should avoid distraction and O25 warns against overloading a section. These are its system-specific expectations, not a universal numeric density threshold.

Whitespace can help separate groups, but excessive gap claims require content/task/outcome evidence; this corpus measures none. GOV.UK readable columns (O12/O13) and Carbon wide high-density models (O20) are contextually different solutions.

## D. Responsive composition

- WAI O10 advises adapting visible navigation and text width across viewport sizes.
- GOV.UK O11 begins with small-screen single-column service design but allows differing content constraints.
- Primer O22 recommends streamlining complex multicolumn experiences at narrow viewport ranges.
- Pinned Primer PageLayout O27/O28 demonstrates region width and pane-resize/order mechanics, NOT proven end-user results.
- WCAG reflow O03 is normative only with its stated tests and exceptions. Hiding needed content or moving it into an undiscoverable pane is not justified by the mere existence of responsive props.
- Preserve task priority, meaningful reading order and access to necessary secondary navigation when narrowing a layout.

## E. Semantics vs appearance

- Visual heading != semantic HTML heading automatically (O01,O06,O07).
- Visual card != accessible named landmark automatically (O08,O09,O24).
- Visual divider != programmatically determinable information relationship automatically (O01).
- Code with landmark props != tested application accessibility (O29).
- Inspiration gallery listing != inspected visual layout or runtime implementation (O30).

## F. Disagreements / classifications

1. **GOV.UK ~75 vs Primer ~80 character line guidance:** SYSTEM_CONVENTION / CONTEXTUAL_TRADEOFF, not normative conflict; neither numeric target is WCAG (O12,O23).
2. **Constrained service reading width vs Carbon full-width dense workbench:** CONTEXTUAL_TRADEOFF driven by task goal; not majority vote (O12,O20).
3. **Responsive single-column starter vs responsive pane/grid options:** SCOPE_NARROWING; task-specific narrow-screen arrangements (O11,O22,O27).
4. **WAI named semantics vs Primer Pane component areas:** DIFFERENT EVIDENCE TYPES; visual/React composition does not automatically imply semantic landmark (O08,O24,O26).
5. **Carbon direct web open failed:** EVIDENCE LIMITATION, lower confidence for O16–O20 than full live page inspection.
6. **Landbook individual example open unavailable:** UNRESOLVED; no snapshot hierarchy conclusions supported.
7. **Pinned PageLayout code vs live unpinned Primer docs:** VERSION_SPLIT / UNRESOLVED; no identity of version assumed.

## Candidate synthesis limit

Only W03-P01, W03-P02, W03-P03 and W03-A01 are candidate records. All CANDIDATE; no K7 execution, no global best-practice statements.