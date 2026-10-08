# W06 K4 CROSS-SOURCE COMPARISON

## A — Labels versus placeholders, hints, examples
WCAG 3.3.2 Level A labels/instructions (O07) and 2.4.6 Level AA descriptive labels (O04) are separate norms. WAI explains persistent explicit label associations, with conditional programmatic alternatives (O12), and differentiates instructions, examples and placeholder text (O13). GOV.UK Text Input (O18) and USWDS Text Input (O26) provide separate visible labels. Primer FormControl label+caption slots and pinned ids (O31/O36/O37) demonstrate mechanics. Placeholder-only identification is an anti-pattern hypothesis, not a new WCAG label-placement law.

## B — Required and optional
WCAG 3.3.2 requires labels/instructions when input is required (O07), while Identify Input Purpose 1.3.5 AA applies to specified personal-input fields (O02). WAI uses visible required text plus programmatic attributes (O14). GOV/USWDS/Primer use different textual or styling conventions (O18/O25/O31/O38). No universal asterisk/optional punctuation mandate.

## C — Semantic grouping
WCAG 1.3.1 A applies to programmatically identifiable relationships (O01); WAI fieldset/legend radio and checkbox examples (O14), GOV fieldset and choice groups (O23/O24), USWDS (O25/O30), pinned Primer checkbox/radio grouping (O38/O41). A group with only visual proximity may lack programmatic question association. Individual isolated controls need not be arbitrarily wrapped in nested fieldsets.

## D — Validation timing
WCAG 3.2.1/3.2.2 A concern unexpected context change, not mandatory blur or submit validation (O05). GOV.UK advises checking on Continue/Submit instead of interrupting entry, with task-evidence exceptions such as character counts (O21). USWDS's Validation component describes immediate checklist feedback (O28), **but notes deprecation and known notices/accessibility issues** (O29). WAI shows native/browser and scripted strategies (O15/O17). These approaches are **contextual/version split**, not one winning universal timing.

## E — Error communication
WCAG 3.3.1 A requires textual identification of automatically detected input errors; 3.3.3 AA supplies known suggestions unless security/purpose risk (O06/O08). GOV.UK puts actionable error alongside relevant question and adds linked summary (O19/O20), WAI distinguishes field and overall notifications (O17), Primer provides validation slots and aria-invalid wiring (O31/O39/O40). A red outline alone does not provide user-understandable textual diagnosis. Never claim a particular live announcement succeeded.

## F — Focus on failure
WCAG 2.4.3 A governs meaningful sequential focus when it matters (O03), but not mandatory focus to first field or summary. GOV.UK specifically directs focus to error summary (O20) for its service pattern; WAI supports page title/heading/notifications (O17). Which to focus in an actual product is UNRESOLVED and must be evaluated in context.

## G — Error prevention
WCAG 3.3.4 AA for legal/financial/stored-data/user test submissions requires **at least one** of reversible, checked/correctable, or reviewed/confirmed (O09); it is not mandatory confirmation for every action. WAI discusses user confirmation and undo techniques (O15); no consequential product action was designed.

## H — Redundant entry
WCAG 3.3.7 A applies to previously entered/supplied information required again in the same process, with reentry-essential, security and no-longer-valid exceptions (O10). GOV preservation after validation (O22) is related but not identical: preservation on retry versus later-step redundant reentry must not be conflated.

## I — Disabled, readonly, blocked progress
Primer supports disabled propagation (O33/O38/O41). Readonly is conceptually an input that cannot be edited but may still represent data; exact browser focus/submission mechanics were not tested or established by these source observations. A disabled submit may be justified, but when it hides why progress cannot continue it raises a **contextual hypothesis**. No unconditional prohibition accepted.

## J — Responsive form integrity
Accepted W03/W04/W05 rules bound grouping, priority, essential controls, source/focus ordering and orientation. Labels, errors, actionable corrections and Continue/Submit access must not disappear because of narrow geometry. USWDS advises form control visual/markup order alignment (O25), as product guidance rather than universal ban on all CSS reordering. No actual form reflow was rendered.

## Cross-source tradeoffs
1. GOV submit-time vs USWDS immediate feedback: CONTEXT and VERSION SPLIT; USWDS example has known issues/deprecation.
2. GOV summary for every error vs WAI's flexible notification techniques: SYSTEM CONVENTION, not normative conflict.
3. GOV focus-to-summary vs first-field/inline approaches: TASK-DEPENDENT focus decision, no WCAG universal focus target.
4. Primer visual validation status vs WCAG descriptive error requirement: capability vs normative obligation; status color alone insufficient.
5. WAI native validation vs custom script: browser-dependent and system-specific; no automatic server trust.
6. Error prevention for scoped consequential actions vs universal confirmation: SCOPE NARROWING.
7. Field preservation vs Redundant Entry: RELATED but DIFFERENT requirements.
8. Disabled vs readonly: distinct states; effect of specific target implementation UNOBSERVED.

No seventh source or empirical result introduced.
