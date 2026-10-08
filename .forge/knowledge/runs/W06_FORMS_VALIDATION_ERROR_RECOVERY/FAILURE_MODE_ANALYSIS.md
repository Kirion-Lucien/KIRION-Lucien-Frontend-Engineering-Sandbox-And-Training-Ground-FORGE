# W06 FAILURE MODE ANALYSIS — 14 CHALLENGED HYPOTHESES

Direct evidence below describes documented semantics or guidance; inferred harm remains unmeasured without target users. Do not turn 'bad form UX' into an anti-pattern label.

## PLACEHOLDER_AS_ONLY_LABEL

1. **Observable structure:** Transient placeholder is the sole field-identification text.
2. **Claimed harm:** After typing, control purpose may be unavailable.
3. **Direct support:** WAI O12/O13; USWDS O26.
4. **Inference / limits:** Outcome inferred; no user test.
5. **Legitimate context:** Search field whose purpose is already unambiguous and programmatically named.
6. **Counterexample:** Visually hidden but accessible label plus surrounding context.
7. **Candidate disposition:** W06-A01 contextual candidate.

## ERROR_BY_COLOR_ONLY

1. **Observable structure:** Invalid state shown only by red border or icon.
2. **Claimed harm:** No textual detected error diagnosis.
3. **Direct support:** WCAG O06; USWDS O27; Primer O40.
4. **Inference / limits:** No target contrast/AT test.
5. **Legitimate context:** Color as supplementary cue alongside text.
6. **Counterexample:** Red outline with error description associated to field.
7. **Candidate disposition:** W06-A02 contextual candidate.

## UNLINKED_ERROR_MESSAGE

1. **Observable structure:** Error text not associated to affected question/control.
2. **Claimed harm:** User cannot locate or interpret failure easily.
3. **Direct support:** WAI O17; GOV O19; Primer O37/O39.
4. **Inference / limits:** Real user impact untested.
5. **Legitimate context:** Error notice explicitly names affected field and is adjacent.
6. **Counterexample:** Clear nearby localized message with programmatic association.
7. **Candidate disposition:** Covered by W06-P02; no separate anti.

## ERROR_SUMMARY_WITHOUT_FIELD_ROUTE

1. **Observable structure:** Overview lists errors but links not navigable to invalid answers.
2. **Claimed harm:** Repeated manual scanning after submission.
3. **Direct support:** GOV O20.
4. **Inference / limits:** Harm inferred, GOV-specific design choice.
5. **Legitimate context:** Short one-control form with clear local error.
6. **Counterexample:** GOV summary linked to each invalid field.
7. **Candidate disposition:** W06-P02; no global summary law.

## ERROR_TEXT_WITHOUT_CORRECTION_GUIDANCE

1. **Observable structure:** Known correction omitted from error message.
2. **Claimed harm:** Users do not know next step.
3. **Direct support:** WCAG O08 when suggestions known; GOV O19.
4. **Inference / limits:** Suggestion exception for security/purpose; outcomes unmeasured.
5. **Legitimate context:** Unknown or security-sensitive correction.
6. **Counterexample:** Brief explanation that does not expose secret validity criteria.
7. **Candidate disposition:** W06-P02.

## LOST_USER_INPUT_AFTER_VALIDATION_FAILURE

1. **Observable structure:** Failed submit discards previous answers.
2. **Claimed harm:** Unnecessary reentry and inability to edit.
3. **Direct support:** GOV O22; WCAG O10 related but different.
4. **Inference / limits:** Loss measured in hypothetical task only.
5. **Legitimate context:** Intentionally cleared highly sensitive secrets by security design.
6. **Counterexample:** Redisplay retained safe answer values with identified error.
7. **Candidate disposition:** W06-P03.

## FORM_GROUP_WITHOUT_GROUP_LABEL

1. **Observable structure:** Options share a question only through visual proximity.
2. **Claimed harm:** Missing semantic grouping cue.
3. **Direct support:** WCAG O01; WAI O14; GOV O23.
4. **Inference / limits:** No screen-reader test in this run.
5. **Legitimate context:** Independent checkboxes with individually complete prompts.
6. **Counterexample:** fieldset/legend for shared radio question.
7. **Candidate disposition:** Candidate P01 scope, no extra anti.

## REQUIRED_STATE_VISUAL_ONLY

1. **Observable structure:** Mandatory field indicated only by color or ambiguous asterisk.
2. **Claimed harm:** Required status not obvious without visual cue.
3. **Direct support:** WCAG O07; WAI O14.
4. **Inference / limits:** No particular marker universally mandated.
5. **Legitimate context:** All fields required with upfront visible textual instruction.
6. **Counterexample:** Text 'Required' plus programmatic required status.
7. **Candidate disposition:** Contextual; fold into P01.

## DISABLED_SUBMIT_WITHOUT_RECOVERY_GUIDANCE

1. **Observable structure:** Submit unavailable while no reason/correction given.
2. **Claimed harm:** Blocked progress.
3. **Direct support:** WAI O13; Primer disabled O38; prior W04-A01.
4. **Inference / limits:** User impact inferred.
5. **Legitimate context:** Disabling under explicitly known unmet condition with clear instruction.
6. **Counterexample:** Disabled control with visible unmet-requirement checklist.
7. **Candidate disposition:** WEAK, no categorical disabled anti.

## VALIDATION_TOO_EARLY_FOR_TASK_CONTEXT

1. **Observable structure:** Errors fire before answer is complete.
2. **Claimed harm:** Premature interruption to entry.
3. **Direct support:** GOV O21.
4. **Inference / limits:** Real outcome only service-specific guidance.
5. **Legitimate context:** Live password criteria for consenting users.
6. **Counterexample:** GOV Continue-triggered service validation.
7. **Candidate disposition:** CONTEXT TRADEOFF.

## VALIDATION_TOO_LATE_FOR_TASK_CONTEXT

1. **Observable structure:** Known expensive constraint revealed after long input.
2. **Claimed harm:** Avoidable wasted effort.
3. **Direct support:** USWDS O28; Primer character count O40.
4. **Inference / limits:** USWDS component has known issues/deprecation O29.
5. **Legitimate context:** Short uncomplicated form with submit-time checks.
6. **Counterexample:** Informative character counter before limit exceeded.
7. **Candidate disposition:** CONTEXT TRADEOFF.

## SERVER_ERROR_PRESENTED_AS_FIELD_ERROR

1. **Observable structure:** Connectivity/internal error attributed to user's input.
2. **Claimed harm:** Misdiagnosis and futile corrections.
3. **Direct support:** GOV O21; WAI O17.
4. **Inference / limits:** No server integration observed.
5. **Legitimate context:** Server verified field constraint genuinely invalid.
6. **Counterexample:** Separate process-unavailable message and correction route.
7. **Candidate disposition:** Contextual analysis only.

## DESTRUCTIVE_SUBMISSION_WITHOUT_RECOVERY

1. **Observable structure:** Scoped consequential submit has no reversal/check/correction/confirmation.
2. **Claimed harm:** Potential irrevocable user mistake.
3. **Direct support:** WCAG 3.3.4 AA O09.
4. **Inference / limits:** Applies only to listed operations, not all forms.
5. **Legitimate context:** Reversible saved draft or undo path.
6. **Counterexample:** Review-and-confirm step for scoped deletion.
7. **Candidate disposition:** Normative scoped concern, not extra anti candidate.

## REDUNDANT_REENTRY_WITHOUT_NECESSITY

1. **Observable structure:** Previously provided same-process info forced again.
2. **Claimed harm:** Unnecessary memory/time burden.
3. **Direct support:** WCAG 3.3.7 A O10.
4. **Inference / limits:** Essential/security/stale exceptions apply.
5. **Legitimate context:** Fresh password confirmation required for security.
6. **Counterexample:** Auto-populate previous response or allow selection.
7. **Candidate disposition:** Contextual concern in P03.

## K5 limitation

Only A01 placeholder-only identification and A02 error-by-color-only merit independent bounded anti-pattern records. Unrecoverable loss and actionable error linkage are better represented within bounded P02/P03; premature/late validation are context tradeoffs, not universal failures. USWDS Validation's known issues/deprecation matter.
