# KIRION FORGE — W06 MAINTAINER REVIEW PACKET (K6)

## RUN ID
W06_FORMS_VALIDATION_ERROR_RECOVERY

## EXACT LUCIEN SOURCE
Accepted source main@d58d7885c664553e12c6901a76d69a5da9cf85d4; authorized initial worker branch forge/w06-forms-validation-error-recovery-intelligence@bb636c2eb32e3991f09cbf80a6aafd2a694f2550; issue #13. Resolve final candidate SHA from committed Git before Maintainer K7; this precommit document does not invent it.

## SOURCE SET
Exactly six: S1 normative W02-S1 WCAG 2.2; S2 W06-S2 WAI Forms; S3 W06-S3 GOV.UK Forms/Validation; S4 W06-S4 USWDS Forms; S5 W06-S5 Primer FormControl etc docs; S6 W06-S6 exact pinned primer/react form code at 7f5303d803986887187d86dcebaeda22a4dc6823.

## QUALIFICATION SUMMARY
W02-S1 reused from exact WCAG identity; W06-S2–S6 newly qualified for materially different forms targets. Registry now 20 source records, 5 additions; no seventh source. USWDS fieldset and error-message direct pages failed; no firsthand claims. WAI informative not a new WCAG criterion. Live design-system documentation not assumed identical to pinned implementation.

## VOCABULARY SUMMARY
46 evidence-linked working terms in VOCABULARY.md. Clear separations: label/placeholder, visible label/accessible name, hint/error, checking/communication, field/summary, client/server authority, disabled/readonly, warning/error/success, preservation after failure/redundant entry.

## OBSERVATION COUNT
42 JSON OBSERVED: WCAG 11 (O01–O11), WAI 6 (O12–O17), GOV.UK 7 (O18–O24), USWDS 6 (O25–O30), Primer docs 6 (O31–O36), pinned Primer code/tests 6 (O37–O42).

## NORMATIVE FORM REQUIREMENTS
WCAG 2.2 Recommendation 2024-12-12: 1.3.1 A Info/Relationships; 1.3.5 AA Identify Input Purpose (only specified user information and supporting technology); 2.4.3 A Focus Order; 2.4.6 AA Headings/Labels; 3.2.1 A On Focus and 3.2.2 A On Input; 3.3.1 A Error Identification when auto-detected; 3.3.2 A Labels/Instructions; 3.3.3 AA Error Suggestion where known unless security/purpose exception; 3.3.4 AA Error Prevention for listed legal/financial/data/test changes (one of reversible, checked/correctable, or reviewed/confirmed); 3.3.7 A Redundant Entry same process, with essential/security/stale exceptions; 4.1.2 A Name, Role, Value. O01–O11. WCAG does not mandate validation event, summary, focus target, UI layout or every-submit confirmation.

## WAI EXPLANATORY GUIDANCE
Labels and explicit control association (O12); instruction/format/placeholder boundaries (O13); semantic fieldset/legend/optgroup groups (O14); native HTML checks and accessible scripts (O15); server-side validation for authoritative/security checking (O16); page heading/title, inline and overall feedback options (O17). Explanatory, not additional normative law.

## DESIGN-SYSTEM FORM GUIDANCE
GOV.UK labels/hints/fieldset/radios, error wording, error summary focus/link and preservation on failed submit (O18–O24). Its service pattern generally validates when continuing, not on blur.
USWDS form and text input semantics, native controls, contextual states, immediate-checklist Validation component (O25–O30). **Validation's known accessibility/usability problems and deprecation note after USWDS v3.12.0 are preserved**; not endorsed as modern ideal.
Primer FormControl/TextInput/Select/Checkbox/Radio usage and assistance relationships (O31–O36); live docs not pinned.

## PINNED IMPLEMENTATION FINDINGS
Exact primer/react@7f5303d803986887187d86dcebaeda22a4dc6823: FormControl generates label/caption/validation IDs and aria-describedby (O37), propagates required/disabled and special choice behavior (O38), validation slot has context-derived ID (O39); TextInput sets aria-invalid and derives character count with screen-reader text (O40); Select/Checkbox/Radio native elements and group name usage (O41); unit tests indicate intent only (O42). Tests READ, NOT EXECUTED. No browser/AT/server integration results.

## LABEL / INSTRUCTION FINDINGS
Stable identification, visible labels and accessible names, hints, examples, formatting and placeholders serve different functions. WCAG requires labels/instructions for user input, not a particular label position. Placeholder-only field identity is a narrow candidate failure.

## REQUIRED / OPTIONAL FINDINGS
Communicate required constraints in words/appropriate programmatic state (WAI O14; WCAG O07; Primer O38). No universal asterisk/punctuation/optional wording convention.

## GROUPING FINDINGS
WCAG 1.3.1 relates to programmatic relationships; WAI/GOV/USWDS use fieldset/legend for related choices (O01/O14/O23/O25); pinned source shows radio/checkbox group mechanics (O38/O41). Group only when meaningful.

## VALIDATION-TIMING FINDINGS
GOV.UK generally defers until Continue/Submit (O21); USWDS Validation shows immediate checklist (O28) but records **component deprecation and known issues** (O29). WAI describes native/client/server distinctions (O15/O16). Context/version tradeoff; no universal on-input/on-blur/on-submit law.

## ERROR-COMMUNICATION FINDINGS
WCAG 3.3.1 Level A text error identification and 3.3.3 Level AA known-suggestion scope (O06/O08). GOV near-field actionable messages (O19), WAI inline/overall notifications (O17), Primer messages/aria-invalid wiring (O37/O39/O40). No color-only failure communication.

## ERROR-SUMMARY FINDINGS
GOV.UK says summary even for one error and requires links/wording alignment (O20), but that is system-specific. WCAG does not mandate an error summary for every form. Single-input forms may use contextual inline feedback.

## FOCUS / ANNOUNCEMENT FINDINGS
GOV.UK focus-to-summary after failed submission is its convention (O20); WAI describes page title/heading/inline feedback (O17). WCAG 2.4.3 preserves meaning/operability where focus sequence matters (O03), without selecting first field vs summary. No live AT announcements executed.

## ERROR-PREVENTION FINDINGS
WCAG 3.3.4 AA applies only to specified legally/financially/data/user-test consequential pages, with **one of** reversible, checked+correctable or reviewed+confirmed safeguards (O09). It does not require a confirmation dialog for every form.

## REDUNDANT-ENTRY FINDINGS
WCAG 3.3.7 A applies to same-process previously given information, subject to essential, security and stale exceptions (O10). GOV preserved answers after failed validation (O22) is related, not identical.

## DISABLED / READONLY FINDINGS
Primer source propagates disabled states (O38/O41). Readonly is conceptually distinct but exact browser focus/submission effects were NOT tested. A disabled submit with no correction path is a hypothesis, not a universal disabled-control prohibition.

## RESPONSIVE FORM FINDINGS
Apply accepted W03 semantic hierarchy, W04 recoverable reduction/source-focus order and W05 orientation/navigation role. Preserve task-critical label, error correction and Continue access on narrow screens; not tested on any viewport.

## FAILURE-MODE HYPOTHESES
14 hypotheses, each with observable structure, harm, direct support, inference, legitimate context, counterexample and candidate decision in FAILURE_MODE_ANALYSIS.md.

### SUPPORTED
W06-A01 placeholder-only field identification where no equivalent persistent/programmatic identity. W06-A02 color-only error indicator where an input error is automatically detected and no text describes it. Both remain candidate; no target usability or audit result.

### WEAK / INSUFFICIENT
Disabled submit without recovery, on-blur/in-input too-early or too-late timing, hypothetical server-vs-field errors, form-level summaries missing routes outside GOV context, lost input, ungrouped controls, required markers without text. Some are encompassed by P01/P02/P03 or conditional normative scopes; no universal anti-pattern law.

### REJECTED / MISFRAMED
Every form needs error summary, every failed submit focuses first field, validation only on submit, validation always on blur, disabled submit always bad, all submissions need confirmation, all information may be prefilled without privacy limits, red styling itself is prohibited. All exceed evidence.

## CONTRADICTIONS
GOV delayed validation vs USWDS immediate checklist: contextual and version split; USWDS validation deprecation and known problems material. GOV summary/focus requirement vs flexible WAI methods: provider convention vs general explanatory reference. Primer state props vs WCAG textual error requirement: mechanics not sufficient standalone. USWDS CSS source-order advice vs WCAG condition-specific focus-order: guidance scope, not normative change. Preserved retry values vs redundant same-process input: related separate requirements.

## COUNTEREXAMPLES
Icon search with accessible name and unambiguous visual context; input with placeholder example and visible label; red outline plus associated corrective text; brief isolated form where inline error suffices outside GOV.UK service; genuine client-side live requirement checklist whose feedback was appropriately researched; essential security reentry; disabled submit with explicit recoverable requirements; reversible destructive change without extra confirmation.

## VERSION LIMITS
WCAG 2024 Recommendation. WAI/GOV/USWDS/Primer docs live/unpinned. USWDS site advertises 3.13.0 but Validation deprecated after 3.12.0; do not infer current production suitability. primer/react exact pinned source 7f5303d803986887187d86dcebaeda22a4dc6823 only.

## LICENSE / STORAGE LIMITS
W3C public-reference/document-use; GOV OGL v3.0 except exclusions; USWDS/Primer docs UNKNOWN reference-only; pinned primer/react MIT. Stored summaries, links, IDs, source paths and metadata only; no external code, asset, screenshot or bulk text.

## PATTERN CANDIDATES
W06-P01 Persistent field identity with semantic instruction relationships — MEDIUM/CANDIDATE.
W06-P02 Actionable, source-linked error communication — MEDIUM/CANDIDATE.
W06-P03 Recoverable validation failure with preserved answers — MEDIUM/CANDIDATE.

## ANTI-PATTERN CANDIDATES
W06-A01 Placeholder-only field identification — MEDIUM/CANDIDATE.
W06-A02 Detected field error signaled only by color — HIGH/CANDIDATE (HIGH reflects normative evidence strength within scope, not verified target failure).

## WHAT MUST NOT BE GENERALIZED
No framework, form library, backend validation scheme, universal timing, fixed error summary/focus requirement, global disabled prohibition, universally mandated review or question-page strategy; code inspection/test files are not runtime evidence.

## PRIOR KNOWLEDGE INTEGRITY
All 17 existing W02–W05 knowledge records must remain byte-identical; deferred W02-P02 and W03-A01 remain CANDIDATE. Worker will independently validate tree blob identities after commit.

## UNRESOLVED QUESTIONS
Product-specific fields/tasks, server-rejection categories, privacy and data-retention requirements, native/browser behavior, actual AT output/focus, form usability, GOV/USWDS/Primer live-version correspondence, USWDS validation current availability and documentation licensing.

## WORKER RECOMMENDATION
READY_FOR_MAINTAINER_REVIEW after exact-branch/scope/JSON/prior-record validation; K6 only, no K7 promotion, no W07, no app or main merge.
