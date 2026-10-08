# KIRION FORGE — W04 MAINTAINER REVIEW PACKET (K6)

## RUN ID
W04_RESPONSIVE_MOBILE_ADAPTATION

## EXACT LUCIEN SOURCE
- Canonical accepted main: c9acd923b11d8695ab5ba41569599fc9165f5b97
- Verified governance W04 head: forge/w04-responsive-mobile-adaptation-intelligence@240a35d4ea17b1667d2baf2a161f08be895b70ad
- Final W04 worker candidate SHA must be taken from GitHub branch/worker return; this precommit packet does not invent it.
- Governing issue #9. Scope K0–K6 only; Maintainer owns K7.

## SOURCE SET
S1 W02-S1 WCAG 2.2; S2 W03-S2 WAI Mobile/Designing; S3 W03-S3 GOV.UK Layout/Type; S4 W03-S4 Carbon 2x Grid; S5 W03-S5 Primer Layout/PageLayout/Typography; S6 W03-S6 pinned PageLayout and responsive utilities at primer/react@7f5303d803986887187d86dcebaeda22a4dc6823.

## QUALIFICATION SUMMARY
Six logical families, all reused from prior qualified identities. Registry untouched and no seventh source. S4 Carbon direct opening failed: only official indexed excerpts, MEDIUM confidence. Other official pages and exact Git code inspected with source/version limits. No external repository mutation.

## VOCABULARY SUMMARY
29 observation-linked working terms: responsive/adaptive/fluid; viewport/breakpoint/range; reflow/stack/wrap/collapse/disclosure/overflow; 2D content; source/visual/focus order; content priority/region ordering; responsive typography/density; safe hiding, critical content/action; target size, orientation, pane movement, progressive reduction and task-justified scroll. No device-name breakpoint values asserted as universal.

## OBSERVATION COUNT
32, all OBSERVED: S1 WCAG 8; S2 WAI 4; S3 GOV.UK 5; S4 Carbon 4; S5 Primer docs 5; S6 implementation 6. Exact individual source links in observations/W04-O01.json through W04-O32.json.

## NORMATIVE RESPONSIVE REQUIREMENTS
WCAG 2.2 1.3.1 (A) Info/Relationships; 1.3.2 (A) Meaningful Sequence; 1.3.4 (AA) Orientation with essential exception; 1.4.4 (AA) 200% text resize with exclusions; 1.4.10 (AA) Reflow at test-equivalent 320 CSS px width / 256 CSS px height, intrinsically 2D exception; 1.4.12 (AA) Text Spacing support with no loss; 2.4.3 (A) Focus Order where sequence matters; 2.5.8 (AA) pointer target 24×24 CSS px with specified exceptions. Source S1, O01–O08. WCAG does NOT select a responsive UI framework, breakpoint or mobile navigation control.

## DESIGN-SYSTEM RESPONSIVE GUIDANCE
WAI is explanatory (O09–O12); GOV.UK advocates small-first service layouts and screen-size rather than device assumptions (O13–O17); Carbon documents fixed/fluid/hybrid grids and legitimate high-density workbenches (O18–O21, excerpts only); Primer advocates function-preserving narrow experiences, viewport ranges and meaningful PageLayout regions (O22–O26).

## PINNED IMPLEMENTATION FINDINGS
Primer utility defines narrow/regular/wide media ranges, getResponsiveAttributes maps responsive values into data attributes, PageLayout supplies responsive region props and CSS layout/order variables, usePaneWidth/DragHandle provide resize mechanics, and stories/tests depict adaptations, including a TODO for hiding a pane. O27–O32; at exact immutable SHA only; **tests/stories READ, NOT EXECUTED**.

## REFLOW FINDINGS
SC 1.4.10 controls information/function loss and two-dimensional scrolling under precise test equivalents, except intrinsically 2D content. Do not equate it with mandated one-column CSS or a universal 320px breakpoint.

## CONTENT-PRIORITY FINDINGS
Preserve task-critical actions and information or provide discoverable alternatives. W02-P01/A01 apply to bounded connected action groups; W03-P01/P02/P03 apply to contextual region alignment, width and responsive composition; no blanket mobile control hierarchy.

## SOURCE/VISUAL/FOCUS ORDER FINDINGS
SC 1.3.2 and 2.4.3 are conditional on meaning/operability; pinned CSS visual reordering alone is not a violation. Runtime keyboard/AT inspection required.

## HIDE/COLLAPSE/MOVE FINDINGS
Primer hidden and pane position props demonstrate possible operations, not safe usage. Alternate views/recoverable disclosure are candidates when a necessary pane cannot fit concurrently; decorative/irrelevant regions may be hidden.

## BREAKPOINT FINDINGS
Primer range labels and fixed utility constants are version-specific; GOV.UK discourages named-device assumptions; Carbon uses breakpoint-bound grid geometry. No numeric universal breakpoint table.

## DENSITY FINDINGS
Carbon high-density full-width workbenches differ from GOV.UK service reading contexts. Task-justified 2D arrangements may require special handling; reducing all dense information to spaced cards can be harmful but was not empirically tested.

## TOUCH/TARGET FINDINGS
WCAG SC 2.5.8 applies to pointer targets with exceptions. WAI Mobile covers diverse devices/input mechanisms. No user reach/touch test or actual measured targets.

## ORIENTATION FINDINGS
WCAG SC 1.3.4 prohibits forced single orientation unless essential. Different portrait/landscape compositions permitted; no device rotation executed.

## FAILURE-MODE HYPOTHESES
All ten in FAILURE_MODE_ANALYSIS.md contain visible structure, mechanism, source grade, legitimate countercontext and candidate rationale.

### SUPPORTED AS BOUNDED CANDIDATES
W04-A01 critical task control disappears with no route or equivalent.
W04-A02 unjustified horizontal overflow for content whose meaning/use does not require 2D presentation.
Both need actual target tests to claim a WCAG violation.

### WEAK / INSUFFICIENT
Mobile as a truncated desktop, CSS visual-semantic divergence without demonstrated disruption, device-name overfitting, multiple disclosure levels, excessive density simplification, target compression without measured target size and generic mobile hierarchy loss remain conditional/weak or folded into narrower hypotheses.

### REJECTED / MISFRAMED AS BLANKET LAW
All horizontal scroll is bad; all high-density layouts are bad; visual order must pixel-match DOM order; every breakpoint corresponds to a device class; all narrow interfaces must become one column; all content must be simultaneously visible. These claims exceed scoped evidence.

## CONTRADICTIONS
GOV.UK service-first versus Carbon workbench: CONTEXTUAL_TRADEOFF. WCAG Reflow vs necessary 2D: scoped EXCEPTION. Live Primer docs vs code: VERSION_SPLIT. Hidden API vs functional completeness: CONTEXTUAL SAFETY CHECK. Carbon indexed excerpts vs direct access: LIMITATION. WAI mobile explanatory guidance vs WCAG: AUTHORITY CLASS distinction.

## COUNTEREXAMPLES
Legitimate 2D tables/canvases; professional dense multi-pane workbench; task-irrelevant sidebar safely hidden; independent decorative content reordered; orientation-dependent task if essential. None automatically earns an exemption without contextual evidence.

## VERSION LIMITS
WCAG Recommendation Dec 12 2024; Primer code exactly 7f5303d803986887187d86dcebaeda22a4dc6823; GOV.UK Type Scale references Frontend v6.0.0+; Carbon indexed update Sep 25 2026; remaining live docs unpinned. No release-equivalence assumed.

## LICENSE / STORAGE LIMITS
W3C copyright/document-use; GOV.UK OGL v3.0 content except exceptions; pinned primer/react MIT; online Carbon and Primer doc license UNKNOWN/reference-only. Only metadata, source IDs/URLs, lawful summaries and observations stored, no copied external code/screenshots.

## PATTERN CANDIDATES
- W04-P01 Recoverable responsive reduction — MEDIUM CANDIDATE.
- W04-P02 Meaningful source and focus order through responsive relocation — MEDIUM CANDIDATE.
- W04-P03 Task-justified horizontal overflow — MEDIUM CANDIDATE.

## ANTI-PATTERN CANDIDATES
- W04-A01 Unrecoverable task-critical control disappearance — MEDIUM CANDIDATE.
- W04-A02 Unjustified horizontal overflow for ordinary content — MEDIUM CANDIDATE.

## WHAT MUST NOT BE GENERALIZED
No universal device breakpoints, no per-device CSS law, no guaranteed accessibility from Primer code, no blanket ban on hiding/collapse/reorder/overflow/density. WAI explanatory pages are not WCAG SC. Professional 2D use is not automatically an exception. Source inspection is not runtime proof.

## PRIOR KNOWLEDGE INTEGRITY
W02-P01 ACCEPTED, W02-A01 ACCEPTED, W02-P02 CANDIDATE/DEFERRED; W03-P01/P02/P03 ACCEPTED, W03-A01 CANDIDATE/DEFERRED. Prior records untouched, W04 all CANDIDATE.

## UNRESOLVED QUESTIONS
No actual application/task model, mobile/browser/AT testing, necessary 2D determination, focus/reflow runtime verification or full Carbon page inspection. Refer UNRESOLVED.md.

## WORKER RECOMMENDATION
READY_FOR_MAINTAINER_REVIEW for independent Maintainer evaluation of source limits and five bounded candidates. No K7, W05, stack selection, runtime claim, self-acceptance or main merge.