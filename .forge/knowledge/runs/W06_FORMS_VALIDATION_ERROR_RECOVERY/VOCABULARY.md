# W06 FORM / VALIDATION / ERROR-RECOVERY VOCABULARY

These **46 evidence-linked working definitions** are not accepted general-purpose form laws. WAI/GOV.UK/USWDS/Primer conventions remain system-specific. WCAG scope and exceptions are preserved in observation JSON.

### form

**Working definition:** User-input collection and submission context.

**Evidence:** W06-O12, W06-O18, W06-O25. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### form control

**Working definition:** Single interactive data-entry or selection interface.

**Evidence:** W06-O12, W06-O37. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### field

**Working definition:** Input with purpose, value and related labels/instructions.

**Evidence:** W06-O07, W06-O18, W06-O37. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### label

**Working definition:** Persistent identifying name for a form control.

**Evidence:** W06-O04, W06-O07, W06-O12, W06-O18. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### accessible name

**Working definition:** Programmatically exposed name, potentially different from a visible label.

**Evidence:** W06-O11, W06-O12. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### caption

**Working definition:** Supporting text adjacent to a control, Primer's named helper slot.

**Evidence:** W06-O31, W06-O37. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### hint

**Working definition:** Non-error guidance about constraints or expected information.

**Evidence:** W06-O13, W06-O18. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### instruction

**Working definition:** How to enter or select an acceptable value.

**Evidence:** W06-O07, W06-O13, W06-O21. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### example

**Working definition:** Illustrative acceptable value or format, not a label.

**Evidence:** W06-O13, W06-O18. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### placeholder

**Working definition:** Transient in-control prompt that disappears or changes with entered content.

**Evidence:** W06-O13, W06-O26. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### required

**Working definition:** Constraint that an answer must be provided.

**Evidence:** W06-O07, W06-O14, W06-O31, W06-O38. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### optional

**Working definition:** Field without completion requirement; communicated by system convention.

**Evidence:** W06-O13, W06-O18. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### constraint

**Working definition:** Condition such as type, format, length or required status.

**Evidence:** W06-O13, W06-O14, W06-O32. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### validation

**Working definition:** Checking input against a rule or constraint.

**Evidence:** W06-O14, W06-O21, W06-O28. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### client-side validation

**Working definition:** Feedback/checking in user agent, not inherently server-authoritative.

**Evidence:** W06-O15, W06-O28. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### server-side validation

**Working definition:** Verification beyond client execution, necessary for authoritative acceptance/security.

**Evidence:** W06-O15, W06-O22, W06-O28. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### native validation

**Working definition:** User-agent HTML required/type/constraint checking.

**Evidence:** W06-O14. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### validation state

**Working definition:** Programmatic/visual state of validity, warning or success.

**Evidence:** W06-O29, W06-O33, W06-O39. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### error identification

**Working definition:** Identifying invalid items and describing detected errors in text.

**Evidence:** W06-O06, W06-O19. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### error suggestion

**Working definition:** Available corrective suggestion, with WCAG 3.3.3 exceptions.

**Evidence:** W06-O08, W06-O19. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### inline error

**Working definition:** Message placed close to the affected input or group.

**Evidence:** W06-O17, W06-O19. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### field-level error

**Working definition:** Failure tied to a particular field or question group.

**Evidence:** W06-O19, W06-O21. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### form-level error

**Working definition:** Feedback about overall submission or processing, not a single field.

**Evidence:** W06-O17, W06-O20. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### error summary

**Working definition:** Overview of failed answers with links when GOV.UK service pattern applies.

**Evidence:** W06-O20. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### warning

**Working definition:** Caution or status distinct from a failed validation rule.

**Evidence:** W06-O34. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### success

**Working definition:** Communicated completion or valid state, not necessarily final persistence.

**Evidence:** W06-O17, W06-O29. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### focus management

**Working definition:** Selection of keyboard focus target following a state transition.

**Evidence:** W06-O03, W06-O20. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### error recovery

**Working definition:** Restoring a viable path to correct errors and continue task.

**Evidence:** W06-O19, W06-O22. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### preserved input

**Working definition:** Keeping previously entered answers available after failure.

**Evidence:** W06-O22. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### fieldset

**Working definition:** Semantic container for related controls.

**Evidence:** W06-O14, W06-O23, W06-O25. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### legend

**Working definition:** Accessible name/heading for related fieldset control group.

**Evidence:** W06-O14, W06-O23, W06-O25. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### choice group

**Working definition:** Related input alternatives sharing one prompt.

**Evidence:** W06-O14, W06-O24, W06-O41. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### radio group

**Working definition:** Mutually exclusive selection within one named group.

**Evidence:** W06-O24, W06-O35, W06-O41. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### checkbox group

**Working definition:** Independent selections that may share common instructions.

**Evidence:** W06-O14, W06-O24, W06-O34. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### input purpose

**Working definition:** Specified personal-data input type identifiable in WCAG 1.3.5 scope.

**Evidence:** W06-O02. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### autocomplete

**Working definition:** Programmatic input-purpose token/support where applicable.

**Evidence:** W06-O02. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### format guidance

**Working definition:** Help describing accepted date/code/value formats.

**Evidence:** W06-O13, W06-O18. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### character limit

**Working definition:** Maximum permitted text length established per field.

**Evidence:** W06-O32, W06-O40. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### character count

**Working definition:** Visible or accessible feedback about text length relative to limit.

**Evidence:** W06-O32, W06-O40. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### disabled

**Working definition:** Nonavailable control state with restricted interaction; source examples exist.

**Evidence:** W06-O33, W06-O38, W06-O41. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### readonly

**Working definition:** Inspectable but non-editable value state; contrast to disabled needs target checks.

**Evidence:** W06-O33, W06-O38. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### submission

**Working definition:** Sending form data or progressing service stage.

**Evidence:** W06-O17, W06-O21. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### confirmation

**Working definition:** Explicit user confirmation before a scoped consequential action.

**Evidence:** W06-O09. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### review step

**Working definition:** Opportunity to inspect/correct submitted information before final acceptance.

**Evidence:** W06-O09. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### error prevention

**Working definition:** Scoped reversibility/checking/confirmation under WCAG 3.3.4.

**Evidence:** W06-O09. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

### redundant entry

**Working definition:** Same-process reentry of previously entered/provided info with exceptions.

**Evidence:** W06-O10. **Boundary:** The term describes the referenced source context; it does not certify a specific implementation.

## Non-equivalences

- **Label ≠ placeholder:** a transient example is not a persistent accessible control identity (O12/O13/O26).
- **Accessible name ≠ necessarily visible label:** programmatic naming alternatives are conditional; user-facing identity can be different (O12).
- **Hint ≠ error:** help offered before entry differs from diagnosis after invalid input (O13/O19).
- **Validation ≠ error communication:** a rule check can occur without intelligible, linked user feedback (O06/O14/O19).
- **Disabled ≠ readonly:** one denotes nonavailable operation and the other a non-editable value; implementation-specific focus/submission behavior was not measured here (O33/O38/O41).
- **Field error ≠ form summary:** localization and aggregate overview serve different needs (O19/O20).
- **Client-side feedback ≠ authoritative server verification:** browser checking can be bypassed (O15/O28).
- **Warning ≠ validation failure, success ≠ confirmed persistence:** do not collapse distinct states (O17/O34).

No library/schema/backend policy, universal event timing, summary, focus target, required marker or disabled-submit rule is established.
