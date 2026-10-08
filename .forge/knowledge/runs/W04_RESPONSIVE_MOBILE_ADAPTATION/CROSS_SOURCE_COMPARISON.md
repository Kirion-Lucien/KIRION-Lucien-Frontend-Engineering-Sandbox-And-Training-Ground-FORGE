# W04 CROSS-SOURCE COMPARISON — K4

## Reflow versus responsive preference

WCAG 2.2 SC 1.4.10 (W04-O05) requires content/function preservation and avoidance of unnecessary two-dimensional scrolling at the specified 320 CSS px width / 256 CSS px height equivalents, with its essential two-dimensional-content exception. It does **not** mandate a 320px CSS breakpoint or a single column. WAI offers explanatory adaptation guidance (O09–O11); GOV.UK starts small-screen-first for services (O13); Primer splits multicolumn workflows into views when necessary (O22); Carbon describes fixed, fluid and hybrid arrangements (O18–O21).

## Content priority

Main tasks, actions, navigation and necessary secondary information remain context-dependent. Primer calls for full functionality across small screens (O22). WAI describes adaptation of navigation and prominent critical feedback (O11,O12); Carbon legitimizes information-rich workbenches (O21). Accepted W02-P01/W02-A01 govern bounded action groups; W03-P01/P02/P03 govern bounded region alignment, reading widths and content-first responsive behavior. None is automatically a global ordering law.

## Source order, visual order, focus order

SC 1.3.1 (O01) applies to programmatically determinable relationships, SC 1.3.2 (O02) to meaningful reading sequence, and SC 2.4.3 (O07) to focus order preserving meaning/operability when order matters. Pinned PageLayout CSS region order and position props (O29,O30,O32) demonstrate visual mechanics; they do not prove source/focus order matches or fails. CSS visual reordering is not automatically inaccessible. Real DOM, keyboard, zoom and assistive-technology observation remains required.

## Hide, collapse, relocate

WAI describes changed header/navigation presentation rather than blanket removal (O11). Primer documentation says smaller screens should remain fully functional, possibly through multiple views (O22). Pinned PageLayout offers responsive hidden and position props (O29,O32), but code does not establish a recovery path. Retaining access to critical controls is a context-dependent synthesis of WCAG reflow's functionality boundary and Primer guidance; no universal WCAG prohibition on hiding exists.

## Breakpoints and viewport ranges

GOV.UK explicitly advises screen-size reasoning instead of named device assumptions (O14). Primer distinguishes viewport ranges for major layout adaptation and breakpoints for fine-tuning (O23), while its pinned utility has named ranges and constants (O27). Carbon uses breakpoint-bound fixed/fluid geometry (O19). These are SYSTEM CONVENTIONS and implementation constants, not universal phone/tablet/desktop cutoffs. Content-driven change points remain inferred rather than formally measured.

## Density and horizontal overflow

GOV.UK reading width can widen for content needs (O15); Carbon uses high-density full-width models, fixed tile wrapping and sometimes scrollable regions (O20,O21). Over-simplification may damage comparable professional content. Conversely, mere preference for desktop geometry cannot invoke WCAG's intrinsic 2D exception (O05). No universal density threshold or general approval of horizontal scroll follows.

## Touch and target

WCAG SC 2.5.8 establishes pointer target minimum 24×24 CSS px with spacing/equivalent/inline/user-agent/essential exceptions (O08). WAI Mobile includes varied input mechanisms (O10). The standard does not prescribe one physical touch-button dimension for every layout. No pointer usability test performed.

## Orientation

WCAG SC 1.3.4 restricts forcing one orientation unless essential (O03); layout may differ in portrait/landscape. This is not an identical-rendering requirement. No device orientation test performed.

## Contradictions and classifications

- GOV.UK small-screen-first vs Carbon high-density workbench: CONTEXTUAL_TRADEOFF.
- Primer hide props vs documented functionality preservation: SCOPE_NARROWING; caller determines safety.
- CSS reordering vs SC 1.3.2/2.4.3: UNRESOLVED until actual meaning/operation tested.
- SC 1.4.10 no-2D-scroll vs intrinsically 2D content: scoped NORMATIVE EXCEPTION.
- Primer live docs vs pinned code: VERSION_SPLIT, synchronization not established.
- Carbon official indexed page vs direct opening failure: SOURCE INSPECTION LIMITATION (MEDIUM).
- WAI mobile explanation vs WCAG Recommendation: DIFFERENT EVIDENCE AUTHORITY.

## Synthesis boundary

Only source-linked, context-bounded CANDIDATE records may be proposed. No K7 promotion, device breakpoint standardization or application implementation is authorized.