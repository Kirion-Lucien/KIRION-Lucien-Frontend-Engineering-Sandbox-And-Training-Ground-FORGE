# W03 VOCABULARY — EVIDENCE-LINKED WORKING DEFINITIONS

These are analytic **working definitions**, not independent standards or accepted patterns. IDs refer to `observations/W03-Oxx.json` and their source URLs. Terms derived from multiple sources are marked context-dependent; where no source formally defines a term, the status remains inference/working vocabulary.

**Source categories:** W02-S1=normative WCAG only; W03-S2=WAI explanatory; W03-S3=GOV.UK official guidance; W03-S4=Carbon official indexed guidance; W03-S5=Primer official guidance; W03-S6=pinned PageLayout implementation. W02-S5 Landbook listing did not establish a technical definition.

## Visual hierarchy

**Working definition:** Observable differences in emphasis/size/alignment/position that make some parts more prominent for a task; visual not necessarily programmatic.

**Evidence:** W03-O17, O19, O21, O23.

**Boundary:** Carbon and Primer recommendations; no universal scale.

## Information hierarchy

**Working definition:** Topic-to-subtopic and main-to-supporting content relationships, including programmatic meaning when present.

**Evidence:** W03-O01, O06, O07, O08.

**Boundary:** May differ from sheer visual prominence.

## Grouping

**Working definition:** Treating related elements as one meaningful content cluster; may use headings, proximity, alignment, regions or visual boundaries.

**Evidence:** W03-O09, O14, O19.

**Boundary:** Grouping does not inherently require a bordered card.

## Proximity

**Working definition:** Spatial closeness used as a cue to topical relation, as described by Carbon and WAI examples.

**Evidence:** W03-O19, O09.

**Boundary:** Not evidence that a particular spacing value has measured effectiveness.

## Spacing rhythm

**Working definition:** Repeatable spacing increments/relationships used to align components and groups.

**Evidence:** W03-O16, O17, O23.

**Boundary:** Carbon 8px mini unit is only Carbon's convention.

## Vertical rhythm

**Working definition:** Intentional pattern of repeated vertical separation of sections/text blocks.

**Evidence:** W03-O16, O19, O23.

**Boundary:** Derived term for spacing; direct Carbon guidelines mention vertical rhythm.

## Content width

**Working definition:** Available measure of a content column or containing region that can be bounded for a given task.

**Evidence:** W03-O12, O13, O20, O23, O27.

**Boundary:** GOV.UK and Primer values differ and are context-bound.

## Line length

**Working definition:** Amount of text on one rendered line, sometimes approximated by characters/line for readability.

**Evidence:** W03-O12, O23.

**Boundary:** ~75 vs ~80 are system guidance, not WCAG norms.

## Layout region

**Working definition:** Semantically or structurally distinct area such as main, navigation, header, footer or pane.

**Evidence:** W03-O08, O24, O26.

**Boundary:** A CSS box does not automatically create an accessible landmark.

## Primary content

**Working definition:** Material central to the user's current page task; distinguished from navigation and supplementary notes.

**Evidence:** W03-O08, O14, O24.

**Boundary:** WAI main element is semantic; page goal is context-specific.

## Secondary content

**Working definition:** Supporting material such as a complementary aside or relevant pane, not necessarily less important in all tasks.

**Evidence:** W03-O09, O14, O24.

**Boundary:** May be essential in some comparison workflows.

## Supporting metadata

**Working definition:** Descriptors and labels contextualizing a primary item; working analytical term, not formally defined by inspected sources.

**Evidence:** W03-O19, O21.

**Boundary:** LOW confidence extrapolation; no normative metadata hierarchy requirement.

## Surface

**Working definition:** Visual treatment area (background, border/elevation) surrounding or connecting content.

**Evidence:** W03-O17, O20, O24.

**Boundary:** Working term only; no accepted universal surface taxonomy.

## Container

**Working definition:** Layout constraint/wrapper that sets width, spacing or grid flow independently of semantic meaning.

**Evidence:** W03-O13, O14, O26, O27.

**Boundary:** A container is not by itself an accessible named region.

## Card

**Working definition:** A bounded visual/content unit, often with its own surface or grouping treatment.

**Evidence:** W03-O20, O24.

**Boundary:** Source corpus does not demonstrate that all cards are good or bad.

## Tile

**Working definition:** A repeated fixed/grid-aligned visual unit, as illustrated in Carbon 2x Grid geometry.

**Evidence:** W03-O16, O17.

**Boundary:** Tile differs from card in sizing/tiling mechanism; actual products may overlap terms.

## Pane

**Working definition:** Primer component-area term for a supporting start/end region that may resize or move responsively.

**Evidence:** W03-O24, O26, O27, O28.

**Boundary:** Primer-specific API term, not a universal semantic role.

## Sidebar

**Working definition:** Adjacent supporting/navigation column, potentially a pane or complementary content; often repositioned at narrow widths.

**Evidence:** W03-O09, O22, O27.

**Boundary:** Sidebar visual placement does not necessarily imply aside semantics.

## Section

**Working definition:** Meaningfully titled division of related content; may carry a heading, not automatically a landmark.

**Evidence:** W03-O06, O07, O08.

**Boundary:** WAI headings guidance and semantics determine navigability.

## Grid

**Working definition:** Spatial alignment/column/row structure with fixed, fluid or hybrid sizes; implementation differs by system.

**Evidence:** W03-O14, O16, O17, O20.

**Boundary:** Do not adopt Carbon's 2x system as a universal engineering law.

## Responsive composition

**Working definition:** Reflow, rearrangement or reduction of region complexity as viewport conditions change while pursuing same task.

**Evidence:** W03-O03, O10, O11, O22, O27, O28.

**Boundary:** Responsive hiding may require alternative access; runtime reflow not tested.

## Density

**Working definition:** Amount and proximity of useful information/controls in available space relative to the task.

**Evidence:** W03-O20, O21, O25.

**Boundary:** High density may be warranted for professional dashboards; no universal threshold.

## Visual weight

**Working definition:** Relative perceived prominence from type, size, position and other visual cues.

**Evidence:** W03-O19, O21, O23.

**Boundary:** This pilot has no experimental ranking of cues or strict numeric measure.

## Scannability

**Working definition:** Ability to locate content/structure through cues such as descriptive headings, regions and differentiated prominence.

**Evidence:** W03-O05, O06, O07, O19.

**Boundary:** Working synthesis, not a directly measured user outcome in this run.

## Progressive emphasis

**Working definition:** Differentiating topic, supporting items and metadata through deliberate priority cues rather than uniform emphasis.

**Evidence:** W03-O19, O21, O23.

**Boundary:** Candidate analytical term; no universal rule to make everything visually unequal.

## Semantic heading hierarchy

**Working definition:** Programmatic heading rank/organization supporting assistive-technology navigation.

**Evidence:** W03-O01, O05, O06, O07.

**Boundary:** Heading order advice has exceptions; a font-size change is not a semantic heading.

## Whitespace

**Working definition:** Unoccupied area used to separate or align content groups and aid layout structure.

**Evidence:** W03-O16, O17, O19.

**Boundary:** No evidence here that more whitespace is always better or empty space alone improves usability.

## Cross-system differences

- **Column/measure:** GOV.UK guides many service pages toward two-thirds reading columns (~75 characters); Primer suggests ~80 characters as a contextual guideline; Carbon explicitly supports full-width high-density screens (W03-O12,O20,O23). These are not contradictory universal limits.
- **Pane/sidebar/aside:** Primer `Pane` is a component region, while WAI `<aside>` is a semantic complementary-content element; physical adjacency does not prove the same role (W03-O09,O24,O26).
- **Card/tile/surface:** The official corpus describes grids, tiles and layout regions more concretely than a single shared card ontology; the distinctions here are working vocabulary, not accepted definitions.
- **Whitespace/density:** Carbon's task-fit models prohibit equating spaciousness with quality or density with failure (W03-O18,O20).

## Unresolved lexical questions

`surface`, `card`, `supporting metadata`, `progressive emphasis`, and quantitative `scannability` lack a formal cross-source definition/measure within the seven-family corpus. Keep definitions provisional; do not present as standards.