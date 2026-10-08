# W06 VALIDATION & ERROR RECOVERY ANALYSIS

**14 bounded answers;** distinct normative, system-convention and source-code authority.

1. **Identify errors:** name affected item and describe error in text if automatically detected (WCAG 3.3.1 A, O06).
2. **Actionable:** where known, supply correction suggestion except if security/purpose would be jeopardized (WCAG 3.3.3 AA, O08); GOV examples identify how to correct (O19).
3. **Inline enough:** a localized field error may suffice for simple isolated cases if the user can find and correct it; WAI documents inline feedback (O17). This is candidate judgment, not a WCAG exemption claim.
4. **Summary value:** multi-error or page-level overview/return-to-field route; GOV requires summary even for one invalid field within its own service component guidance (O20). Not universally mandatory.
5. **Summary links:** GOV requires summary items link to affected answers and match nearby error wording; connection must be meaningful, not dummy href (O20).
6. **Focus:** GOV shifts focus to summary; actual product focus destination is contextual and must preserve meaningful order. WCAG 2.4.3 does not select it (O03/O20).
7. **Preserved values:** GOV redisplays answers as entered after failed continue/submit (O22). Actual server/session persistence not verified.
8. **Announcements:** WAI describes title/heading and explicit inline/overall notifications (O17); pinned FormControl and TextInput show ids/status but cannot certify AT speech (O39/O40).
9. **When validate:** native, input, blur, submit, server response are distinct. GOV generally delays until Continue; USWDS immediate checklist is documented but subject to deprecation and known issues (O14/O21/O28/O29). No global timing rule.
10. **Server errors:** distinguish constraint errors that user can correct from server/process unavailable or eligibility decisions; GOV validation pattern excludes those as generic field errors (O21). Client checks cannot provide authoritative server validation (O15/O28); no backend design added.
11. **Prevention/review:** scoped WCAG 3.3.4 AA requires one of reversal, checked/correctable, confirmed/reviewed for specified transactions/data changes (O09); not every form.
12. **Reduce redundant entry:** in the same process, allow prior information to be selected or prefilled unless essential/security/stale exceptions (O10); preservation after failure is separate (O22).
13. **Blocked progress:** make cause and corrective path discoverable; disabled submission without diagnosis remains a hypothesis, not a categorical anti-pattern. Preserve accessible task-critical Continue (O07/O19 and accepted W04-A01).
14. **Non-generalization:** one-question pages, focus-to-summary, summary-per-error, immediate checklists, one marker, disabled policies or exact Primer state attributes are provider-specific or context dependent; no actual usability/keyboard/AT/server integration executed.

**Outstanding:** scope of user tasks, server rejection categories, upload/payment/legal workflows, native browser details and actually accessible announcement/focus behavior remain UNKNOWN.
