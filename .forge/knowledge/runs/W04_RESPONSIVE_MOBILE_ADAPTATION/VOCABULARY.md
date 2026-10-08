# W04 RESPONSIVE / MOBILE VOCABULARY — K3

All entries are **working analytic definitions** grounded in W04 observation IDs, not freestanding standards or accepted implementation law. Use individual observation JSON records for exact URLs, evidence type and limitations. Normative WCAG statements apply only at actual success-criterion scope.

## Term dictionary

### Responsive design

**Working definition:** Layout/content adapts to available viewport conditions while preserving usable functionality.

**Source observations:** W04-O11,W04-O13,W04-O21,W04-O27,W04-O30.

**Limits:** Working umbrella term; not tied to a device model.

### Adaptive design

**Working definition:** Deliberate switching among context-sensitive layout configurations or viewport-range presentations.

**Source observations:** W04-O22,W04-O27,W04-O29.

**Limits:** Working analytical term; corpus does not supply a unique normative adaptive-vs-responsive dichotomy.

### Fluid layout

**Working definition:** Columns or region dimensions vary continuously with available space within a layout model.

**Source observations:** W04-O18,W04-O19,W04-O30.

**Limits:** Carbon fluid grid model only; not a WCAG requirement.

### Viewport

**Working definition:** Area made available for page presentation, including constraints from zoomed browser windows.

**Source observations:** W04-O05,W04-O11,W04-O22.

**Limits:** Not synonymous with a phone or any named device.

### Breakpoint

**Working definition:** Threshold/constant at which responsive styling may change behavior.

**Source observations:** W04-O19,W04-O22,W04-O27.

**Limits:** Primer and Carbon use system-defined thresholds, never universal numbers.

### Viewport range

**Working definition:** Named interval of widths used by a system to select major layout strategy.

**Source observations:** W04-O22,W04-O27.

**Limits:** Primer narrow/regular/wide labels are API conventions; not device classes.

### Reflow

**Working definition:** Presentation of content at constrained equivalent viewport dimensions without applicable information/functionality loss or unjustified two-dimensional scrolling.

**Source observations:** W04-O05,W04-O25.

**Limits:** WCAG SC 1.4.10 is conditional and contains essential 2D exceptions.

### Stacking

**Working definition:** Moving simultaneous columns into sequential regions, often vertically.

**Source observations:** W04-O13,W04-O21,W04-O25,W04-O30.

**Limits:** Can change reading order and proximity; test real target.

### Wrapping

**Working definition:** Moving repeated items onto subsequent lines or rows when width is insufficient.

**Source observations:** W04-O18,W04-O20.

**Limits:** A content arrangement, not a guarantee all meaning/controls persist.

### Collapse

**Working definition:** Reducing the visible extent of a content region, potentially concealing contents.

**Source observations:** W04-O21,W04-O25,W04-O29,W04-O32.

**Limits:** Not inherently safe; alternate access may be necessary.

### Disclosure

**Working definition:** User-operable mechanism for recovering concealed content, navigation or controls.

**Source observations:** W04-O21,W04-O25.

**Limits:** Derived term; no specific approved component/API supplied by this corpus.

### Overflow

**Working definition:** Content extent surpassing its allocated visual region.

**Source observations:** W04-O05,W04-O20,W04-O30.

**Limits:** Does not imply horizontal scrolling is automatically incorrect.

### Horizontal scroll

**Working definition:** Horizontal viewport/region navigation used when content width exceeds viewing region.

**Source observations:** W04-O05,W04-O20.

**Limits:** May be task-justified for intrinsically two-dimensional content.

### Intrinsically two-dimensional content

**Working definition:** Material whose usage/meaning depends on two-dimensional relationships rather than ordinary reflow.

**Source observations:** W04-O05,W04-O20.

**Limits:** WCAG exception is scoped; professional interface label alone does not prove essential 2D meaning.

### Source order

**Working definition:** Programmatic sequence of elements/content before presentation rearranges them.

**Source observations:** W04-O01,W04-O02,W04-O29.

**Limits:** Source order is relevant but need not equal screen geometry point-by-point.

### Visual order

**Working definition:** Perceived presentation/placement sequence at a particular viewport.

**Source observations:** W04-O02,W04-O30,W04-O32.

**Limits:** Visual differences are not automatically accessibility failures.

### Focus order

**Working definition:** Sequential navigation path among focusable elements.

**Source observations:** W04-O07,W04-O29,W04-O31.

**Limits:** SC 2.4.3 requires meaning/operability preservation where order affects them.

### Content priority

**Working definition:** Relationship of main task and supporting information determining what stays findable.

**Source observations:** W04-O12,W04-O21,W04-O23,W04-O26.

**Limits:** Priority cannot be inferred solely from viewport width.

### Responsive region order

**Working definition:** Viewport-dependent placement of content regions such as pane/main/sidebar.

**Source observations:** W04-O24,W04-O29,W04-O30,W04-O32.

**Limits:** Pinned PageLayout shows mechanics, not actual reading/focus compliance.

### Responsive typography

**Working definition:** Text scale/line height/measure adjusted to remain readable as available space and text settings change.

**Source observations:** W04-O04,W04-O06,W04-O17,W04-O25.

**Limits:** GOV.UK design-system scale distinct from WCAG 200%/text-spacing criteria.

### Responsive density

**Working definition:** Change in how many controls/content regions appear simultaneously while preserving required workflows.

**Source observations:** W04-O20,W04-O21,W04-O26.

**Limits:** High-density workbenches can legitimately remain information-rich.

### Safe hiding

**Working definition:** Removing an element from current visible composition only where its necessary task function remains recoverable/alternative and semantic behavior is verified.

**Source observations:** W04-O05,W04-O21,W04-O25,W04-O29,W04-O32.

**Limits:** Proposed analytical safety criterion, not blanket WCAG ban on hiding.

### Critical content

**Working definition:** Information without which an intended user task cannot be completed or understood.

**Source observations:** W04-O05,W04-O12,W04-O21.

**Limits:** Task-context judgement; not directly labeled by normative criteria.

### Critical control

**Working definition:** Action/navigation control needed to perform or recover a primary user task.

**Source observations:** W04-O05,W04-O07,W04-O21,W04-O29.

**Limits:** Must be identified by actual product task model.

### Touch target

**Working definition:** Pointer-activatable area, including but not limited to touch interaction.

**Source observations:** W04-O08,W04-O10.

**Limits:** 24×24 CSS px minimum with exceptions under WCAG 2.2 SC 2.5.8; not a blanket physical-size rule.

### Orientation

**Working definition:** Portrait or landscape display alignment; WCAG restricts forced orientation unless essential.

**Source observations:** W04-O03,W04-O10.

**Limits:** Do not invent portrait-only or landscape-only rules.

### Pane relocation

**Working definition:** Changing the placement of supporting content area by viewport using region positions.

**Source observations:** W04-O24,W04-O29,W04-O32.

**Limits:** Primer-specific PageLayout instance; changing visual placement requires sequence evaluation.

### Progressive reduction

**Working definition:** Contextual reduction of concurrent visible regions while maintaining necessary access.

**Source observations:** W04-O21,W04-O25,W04-O29,W04-O32.

**Limits:** Working term; no accepted rule to remove necessary information.

### Task-justified horizontal overflow

**Working definition:** Horizontal navigation whose retained spatial relationship is essential for meaning/usage.

**Source observations:** W04-O05,W04-O20,W04-O26.

**Limits:** Candidate terminology; qualifies WCAG reflow exception only with actual content evidence.

## Critical distinctions

- **Responsive ≠ phone-only:** WAI covers many device and input contexts (W04-O09/O10), and Primer named viewport ranges are layout units, not device classes (W04-O22/O27).
- **Viewport range ≠ individual breakpoint:** major composition transition versus fine-grained threshold in Primer's vocabulary (W04-O22/O27).
- **Source ≠ visual ≠ focus order:** examine meaningful reading sequence and sequential keyboard operation in the actual rendered context (W04-O02/O07/O29/O32).
- **Reflow ≠ forced single column:** WCAG 1.4.10 preserves intrinsically two-dimensional content exceptions; high-density tasks may justify other strategies (W04-O05/O20).
- **Hide ≠ collapse with recovery:** code-level `hidden` may remove a region outright, whereas recoverable disclosure requires a separate mechanism (W04-O21/O29/O32).
- **Touch target ≠ device model:** WCAG SC 2.5.8 applies to pointer targets and defines exceptions (W04-O08).

## Not yet established

No universal responsive breakpoint values, device-name segmentation, single navigation pattern, generalized density threshold, or tested pane relocation outcome is established. `adaptive design`, `safe hiding`, and `progressive reduction` are analytic working terms rather than terms formally standardized across these six sources.