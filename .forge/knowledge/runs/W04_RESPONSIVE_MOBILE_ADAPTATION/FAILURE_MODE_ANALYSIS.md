# W04 RESPONSIVE FAILURE MODE ANALYSIS — K5

These are **testable hypotheses, not a verdict on mobile interfaces**. A source showing an implementation option is not proof of usability harm; a WCAG failure requires matching the actual success-criterion conditions including exceptions. No browser/device/user test was conducted.

## DESKTOP_GEOMETRY_PRESERVATION

- **Observable structure:** Viewport retains wide fixed column structure at narrow equivalent width.
- **Claimed harm:** May cause nonessential two-dimensional scrolling/content loss at WCAG 1.4.10 conditions.
- **Evidence class/IDs:** WCAG O05 normative condition; GOV O13 and Primer O22 offer alternative guidance.
- **Legitimate counter-context:** Intrinsically two-dimensional comparison/viewer task.
- **Decision:** CONTEXT BOUNDED; fold into W04-A02 unjustified overflow.

## MOBILE_AS_TRUNCATED_DESKTOP

- **Observable structure:** Small presentation removes task functions rather than offering usable adaptation.
- **Claimed harm:** Incomplete task flow and nonrecoverable control loss.
- **Evidence class/IDs:** Primer O22 and WCAG O05 reflow functionality; inference beyond exact test context.
- **Legitimate counter-context:** Authorized mobile-specific subset where removed features are not part of that workflow.
- **Decision:** PARTIALLY SUPPORTED; overlap W04-A01.

## CRITICAL_CONTROL_DISAPPEARANCE

- **Observable structure:** Sole task-required action hidden at narrow viewport with no alternative access.
- **Claimed harm:** Users cannot complete task; loss of functionality in scoped reflow evaluation.
- **Evidence class/IDs:** WCAG O05 and Primer O22; direct normative only if SC conditions are met.
- **Legitimate counter-context:** Intentional removal of genuinely inapplicable action, or alternate workflow access provided.
- **Decision:** W04-A01 CANDIDATE; contextual, not universal ban on hiding.

## VISUAL_ORDER_SEMANTIC_ORDER_DIVERGENCE

- **Observable structure:** CSS order changes make visible item sequence differ from source/keyboard path.
- **Claimed harm:** May break meaningful reading or focus progression.
- **Evidence class/IDs:** WCAG O01/O02/O07; pinned code O29/O30 proves mechanism but no actual failure.
- **Legitimate counter-context:** Decorative reordering or independent pieces when sequence does not affect meaning.
- **Decision:** UNRESOLVED: only failure if meaning/operation actually disrupted.

## DEVICE_NAME_BREAKPOINT_OVERFITTING

- **Observable structure:** Responsive changes tied to presumed phone/tablet model instead of width/content constraints.
- **Claimed harm:** May fail zoom, unusual viewport/input combinations.
- **Evidence class/IDs:** GOV O14 and WAI O09/O10; Primer O23/O27 show ranges.
- **Legitimate counter-context:** Named-device QA matrices or hardware-specific app features can still be valid.
- **Decision:** WEAK: no measured failure; no candidate.

## HORIZONTAL_OVERFLOW_WITHOUT_TASK_JUSTIFICATION

- **Observable structure:** Full-page sideways scrolling of ordinary text/form content due to fixed desktop widths.
- **Claimed harm:** Unnecessary two-dimensional navigation; possible SC 1.4.10 failure under its conditions.
- **Evidence class/IDs:** WCAG O05 normative and GOV O13/Primer O22 alternatives.
- **Legitimate counter-context:** Truly two-dimensional task content per explicit WCAG exception; scrollable tile region may be contextually warranted.
- **Decision:** W04-A02 CANDIDATE bounded by exception.

## OVER_COLLAPSED_INFORMATION_ARCHITECTURE

- **Observable structure:** Several necessary navigation/metadata/controls concealed behind multiple undiscoverable layers.
- **Claimed harm:** Increased task search or lost workflow context.
- **Evidence class/IDs:** Primer O22/O25 and WAI O11; direct measured outcomes absent.
- **Legitimate counter-context:** Stepwise mobile flow with clear affordances may appropriately reduce simultaneous regions.
- **Decision:** WEAK / INFERENTIAL; no candidate.

## DENSITY_DESTRUCTION_IN_PROFESSIONAL_TOOLS

- **Observable structure:** Comparable high-density information converted to isolated sparse cards across many screens.
- **Claimed harm:** Potential loss of side-by-side professional comparison.
- **Evidence class/IDs:** Carbon O21 supports legitimate dense models; no outcome measurement.
- **Legitimate counter-context:** Reading-first GOV.UK service pages benefit from constrained columns.
- **Decision:** CONTEXTUAL TRADEOFF; no independent anti candidate.

## TOUCH_TARGET_COMPRESSION

- **Observable structure:** Dense controls yield pointer activation regions smaller than applicable target size.
- **Claimed harm:** May breach WCAG SC 2.5.8, impede reliable pointer selection.
- **Evidence class/IDs:** WCAG O08 normative with exceptions; WAI O10 broad input modes.
- **Legitimate counter-context:** 24×24 rule has spacing, equivalent, inline, UA and essential exceptions.
- **Decision:** SUPPORTED normative risk when tested; no separate anti record to avoid overclaim.

## RESPONSIVE_HIERARCHY_LOSS

- **Observable structure:** Narrow layouts obscure intended main step beneath supporting material or hidden navigation.
- **Claimed harm:** Delayed discovery of main task; possible loss of operation.
- **Evidence class/IDs:** Primer O26, WAI O12 and accepted W02 bounded action hierarchy; no W04 usability experiment.
- **Legitimate counter-context:** Independent regions and task-specific action groups may legitimately vary prominence.
- **Decision:** WEAK / INFERENTIAL; preserve as hypothesis.

## Consolidation

W04-A01 covers task-critical control disappearance and the narrow special case of truncated mobile tasks; W04-A02 covers unjustified horizontal overflow and the narrow fixed-desktop-geometry special case. All other hypotheses remain weak, conditional, unresolved or relevant to contextual tradeoffs, without separate candidate records.

**Prohibitions:** No “mobile slop” category; no blanket ban on visual CSS reordering, dense interfaces, compact controls, content collapse, scrolling, portrait/landscape differences or device testing. None establishes a global frontend implementation preference. Retain actual exceptions and counterexamples.