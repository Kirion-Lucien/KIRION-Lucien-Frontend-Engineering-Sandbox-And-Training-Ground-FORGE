# W06 FORM MODEL ANALYSIS

All answers are **working contextual analysis** tied to W06 observations; no application stack, CSS system or actual form is selected.

1. **Field identifiable:** persistent user-readable purpose plus correctly associated programmatic name, optionally with helpful descriptions (O04/O07/O12/O37).
2. **Label content:** concise description of requested information or selection; not the entire validation contract or ephemeral placeholder (O12/O13/O26).
3. **Hint/instruction:** expected format, constraints, examples, optional nature or necessary context that supports the label (O13/O18/O36).
4. **Examples useful:** unfamiliar dates/codes/lengths; not proof that one universal format is required (O13/O18).
5. **Grouping:** when controls answer one question or share instructions; use appropriate group semantics/legend rather than visual proximity alone (O01/O14/O23/O25).
6. **Required/optional:** communicate visibly and programmatically in user/context appropriate way; WAI shows required attribute/text; no universal asterisk rule (O07/O14/O31/O38).
7. **Choice groups:** group prompt+options; related checkboxes allow independent choices, radios represent exclusive selection; validate at group context where appropriate (O14/O24/O30/O38/O41).
8. **Character limits:** communicate constraint before long effort and present accessible status/count when needed; Primer pinned TextInput derives length and hidden counter text (O32/O40). Actual screen-reader updates untested.
9. **Disabled vs readonly:** disabled expresses unavailable interaction; readonly exposes non-editable value in contexts that use it. Neither state substitutes for explaining blocked task progress. The precise platform-level focus/submission differences are outside acquired runtime evidence (O33/O38).
10. **Responsive:** stack/reflow while preserving label-control, group and error relationships and task-critical submit route, applying accepted W03/W04/W05 bounds (O03/O25/O37).
11. **Visual versus programmatic:** error colors/icons/asterisks may help sighted scanning; associated label, descriptions, required/current-invalid state need appropriate programmatic semantics (O01/O07/O12/O37/O40).
12. **Not color alone:** detected invalid input must be described textually under WCAG 3.3.1 (O06); do not infer conformance from red outlines or validation icons (O29/O40).

No product-specific input taxonomy, validation library, CSS pattern, field count or question-page architecture prescribed.
