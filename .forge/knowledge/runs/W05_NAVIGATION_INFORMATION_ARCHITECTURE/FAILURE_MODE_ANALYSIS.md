# W05 FAILURE MODE ANALYSIS

Twelve hypotheses only; no runtime usability, keyboard, browser or assistive technology results. Direct guidance and source implementation are distinct from inferred harm.

## CURRENT_LOCATION_AMBIGUITY

- Observable structure: No current page or section signal.
- Claimed harm: uncertain position.
- Direct evidence: WCAG O02/O07, WAI O12, Primer O30.
- Inferential limit: discovery cost inferred, not measured.
- Legitimate counter-context: short single-page UI with obvious heading.
- Counterexample: title and page heading may suffice.
- Candidate decision: W05-P01.


## NAVIGATION_ACTION_SEMANTIC_COLLAPSE

- Observable structure: Link and command control roles mixed.
- Claimed harm: wrong activation expectation.
- Direct evidence: WAI O11/O13, Primer O33.
- Inferential limit: user harm unmeasured.
- Legitimate counter-context: editor command controls.
- Counterexample: properly implemented application menu.
- Candidate decision: NARROW_TO_A02.


## BREADCRUMB_AS_HISTORY_TRAIL

- Observable structure: Visited pages shown as ancestral parents.
- Claimed harm: false hierarchy.
- Direct evidence: GOV O19; USWDS O28; Primer O32.
- Inferential limit: wayfinding harm not tested.
- Legitimate counter-context: recently-viewed pages widget.
- Counterexample: history displayed under separate history label.
- Candidate decision: W05-A01.


## BREADCRUMB_AS_STEPPER

- Observable structure: Sequential steps shown as breadcrumb ancestors.
- Claimed harm: hierarchy/process confusion.
- Direct evidence: GOV O17/O19, USWDS O28.
- Inferential limit: harm not tested.
- Legitimate counter-context: ordered transaction workflow.
- Counterexample: labeled progress indicator.
- Candidate decision: W05-A01.


## TAB_NAVIGATION_AS_LINEAR_WORKFLOW

- Observable structure: Peer-view tabs used for mandatory sequential steps.
- Claimed harm: required stages obscured.
- Direct evidence: GOV O21; Primer O33.
- Inferential limit: harm not tested.
- Legitimate counter-context: independent nonsequential related views.
- Counterexample: URL-backed peer views.
- Candidate decision: W05-P03.


## DEEP_NAVIGATION_WITHOUT_ORIENTATION

- Observable structure: Nested paths with no location cue.
- Claimed harm: harder discovery.
- Direct evidence: USWDS O26/O27; WCAG AAA O07.
- Inferential limit: depth effect unmeasured.
- Legitimate counter-context: specialist deep ontology.
- Counterexample: hierarchy with strong search and titles.
- Candidate decision: WEAK.


## DUPLICATIVE_NAVIGATION_WITHOUT_ROLE_DISTINCTION

- Observable structure: Overlapping bars and rails without named scope.
- Claimed harm: extra competing choices.
- Direct evidence: USWDS O26/O28; WAI O14.
- Inferential limit: cost unmeasured.
- Legitimate counter-context: distinct global/local roles.
- Counterexample: properly labelled primary and section nav.
- Candidate decision: WEAK.


## ORGANIZATION_CHART_AS_USER_NAVIGATION

- Observable structure: Departments replace user vocabulary.
- Claimed harm: possible label mismatch.
- Direct evidence: USWDS O27; Primer O30.
- Inferential limit: only inference; no org IA study.
- Legitimate counter-context: staff departmental directory.
- Counterexample: department directory as primary task.
- Candidate decision: INSUFFICIENT.


## HIDDEN_PRIMARY_ROUTE_ON_RESPONSIVE_REDUCTION

- Observable structure: Only task route unavailable when menu collapses.
- Claimed harm: task incompleteness.
- Direct evidence: GOV O23; accepted W04-A01.
- Inferential limit: no browser test.
- Legitimate counter-context: inapplicable link.
- Counterexample: accessible mobile menu preserving route.
- Candidate decision: ALREADY_GOVERNED_W04.


## APPLICATION_MENU_ROLE_OVERUSE

- Observable structure: Ordinary site nav adopts menubar roles without special keys.
- Claimed harm: role-behavior mismatch.
- Direct evidence: WAI O11/O13.
- Inferential limit: no actual keyboard trial.
- Legitimate counter-context: genuine editor command menu.
- Counterexample: scripted desktop application menu.
- Candidate decision: W05-A02.


## UNLABELED_MULTIPLE_NAV_LANDMARKS

- Observable structure: Two navigation regions have no distinguishing names.
- Claimed harm: ambiguous landmark purpose.
- Direct evidence: WAI O14; Primer O35.
- Inferential limit: AT effect untested.
- Legitimate counter-context: single nav region.
- Counterexample: distinctly named nav regions.
- Candidate decision: W05-P01.


## ACTIVE_STATE_ONLY_BY_COLOR

- Observable structure: Current link has no machine-readable current cue.
- Claimed harm: potential loss of current context.
- Direct evidence: WAI O12; GOV O18; Primer O34/O37.
- Inferential limit: actual conformance untested.
- Legitimate counter-context: decorative color with other indicators.
- Counterexample: aria-current and visible current label.
- Candidate decision: W05-P01.


## Consolidated decisions

Two bounded W05 anti-pattern candidates only: confusing breadcrumb ancestry with temporal sequence and imposing desktop-application menu semantics on ordinary site navigation. Hidden primary route already has accepted W04-A01 coverage. Other failures remain weak/contextual. No blanket bad-IA label, numeric depth law or inferred usability certification.