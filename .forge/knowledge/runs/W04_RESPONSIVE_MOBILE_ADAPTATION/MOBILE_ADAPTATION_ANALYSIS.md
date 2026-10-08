# W04 MOBILE ADAPTATION ANALYSIS — K4/K5

These are source-grounded **contextual decisions to evaluate**, not globally accepted UI rules. Evidence IDs refer to observation JSON with precise source URLs and limitations. All runtime/device outcomes remain NOT OBSERVED.

## 1. What must remain available?

Necessary task content, action controls, navigation to complete the task, programmatically meaningful content relationships and necessary status/feedback should remain accessible across constrained layouts. Normative SC 1.4.10 requires no loss of functionality under its specified reflow conditions (W04-O05); Primer docs favor full functionality rather than an impoverished mobile variant (O22). Criticality must be determined from real workflows; no universal inventory was studied.

## 2. What may move?

Supporting panes, navigation and ancillary regions may change visual positions if task access, logical reading meaning and keyboard operation survive (W04-O11,O24,O29,O30,O32). WAI gives header/navigation presentation change examples. Pinned Primer demonstrates pane position variants only in source/stories. Changing visual placement requires actual checks against SC 1.3.2 and 2.4.3; no automatic failure inferred.

## 3. What may stack?

Independent or sequential regions whose side-by-side geometry is not essential may stack as viewport width narrows (GOV O13; Primer O22/O25; pinned CSS O30). Stacking must not scramble meaning or bury an essential next step, and no single-column universal law follows.

## 4. What may wrap?

Repeated controls/tiles may wrap when each unit stays identifiable and its ordering still makes sense. Carbon's fixed tile model explicitly permits wrapping (O20). No dataset-specific wrap order or target size was tested.

## 5. What may collapse behind disclosure?

Optional supporting panes/sections when the resulting disclosure is discoverable, operable and can restore task-critical content. Primer discusses splitting multicolumn workflows (O22); pinned hidden props (O29,O32) alone do not provide a disclosure. This is a PROPOSED reduction pattern, not a directly tested requirement.

## 6. What may scroll horizontally?

Parts intrinsically requiring two-dimensional arrangement for meaning or use may qualify for WCAG 1.4.10's scoped exception (O05), such as task-dependent data comparison. Carbon also mentions overflow scrolling for fixed tiles (O20), but that example alone does not prove normative exception eligibility. Unnecessary full-page horizontal overflow from fixed desktop width lacks that justification.

## 7. What may be hidden?

Decorative, redundant or truly optional content may be visually removed when function, context and task access are preserved, subject to real evaluation. A responsive hidden prop is just a capability (O29/O32). Hiding the sole required action or vital instructions should be treated as a risk until alternative pathways are verified (O05/O22). Do not claim WCAG bans hiding as a method.

## 8. When is preserving desktop geometry harmful?

Where it causes information/function loss or requires two-dimensional scroll for content that does not need 2D relationships, at the SC 1.4.10 test context (O05). Where it makes controls/labels unusable or obscures required task progression, further user testing is necessary (O08/O22). Preserve 2D exceptions where genuinely applicable.

## 9. When is aggressive simplification harmful?

When reduction removes necessary comparison tools, chart controls, essential side information or navigation and makes a professional task impossible. Carbon's high-density style model is legitimate (O21); WAI considers a broad range of devices and inputs (O10). No measured case demonstrates a particular dashboard failure in W04.

## 10. How should action hierarchy survive narrow screens?

Reapply accepted W02-P01/W02-A01 **only within a connected action group**: keep the main user task identifiable when controls wrap/move, without asserting one universal page primary. Check hidden/collapsed actions for task recoverability (O05/O22). No W02 record is changed here.

## 11. How should reading width and type adapt?

Use context-driven width/measure and avoid text clipping at user resizing and spacing overrides: WCAG SC 1.4.4 and 1.4.12 define applicable content preservation (O04/O06). GOV.UK documents small-screen type scale evolution v6+ and wider-content exceptions (O15/O17); WAI recommends legibility/line width consideration (O11). Preserve accepted W03-P02's bounded reading-width guidance; no universal character or CSS px law.

## 12. How should panes and sidebars change?

They may relocate to end/start, stack, become separate views or support constrained resizing (Primer O22,O24,O29–O32). Task-critical panes might remain alongside when adequate width or specialized 2D use demands it (Carbon O21). The pinned implementation shows API knobs, not safe defaults for every product.

## 13. What must be checked when visual order changes?

Inspect DOM/source reading sequence (SC 1.3.2, O02), programmatic relations (SC 1.3.1, O01), sequential focus route (SC 2.4.3, O07), keyboard access to disclosure and hidden regions, visible orientation/zoom and task completion in actual rendered pages. Such validation is NOT RUN in W04.

## Decision method for Maintainer review

Classify each region by task necessity (critical / supporting / optional / decorative), its semantic role, 2D dependence, focusable controls and recovery path. Assess narrow and wide conditions before accepting any hide/move/scroll plan. That classification itself is a candidate method, not a selected frontend implementation.