# SOURCE TAXONOMY

## Governing law

SOURCE TYPE != AUTHORITY WEIGHT

Source type describes what a source is. Authority weight describes how strongly that specific source can support a specific claim. Two sources of the same type may have different credibility, scope, currency, and evidentiary value.

A visually attractive reference does not become engineering authority merely because it looks mature. A popular community source does not outrank a normative or first-party source merely because it is widely cited.

## Required source classes

### Normative and first-party technical sources

- OFFICIAL_STANDARD — specification, standard, normative requirement, or standards-body publication.
- OFFICIAL_PLATFORM_DOCUMENTATION — browser, web platform, runtime, or platform-owner documentation.
- OFFICIAL_FRAMEWORK_DOCUMENTATION — first-party framework documentation.
- OFFICIAL_LIBRARY_DOCUMENTATION — first-party library documentation.

### Implementation and system sources

- DESIGN_SYSTEM — documented design system, including principles, tokens, components, or patterns.
- COMPONENT_LIBRARY — reusable coded component collection.
- REFERENCE_IMPLEMENTATION — implementation intentionally suitable for technical study or comparison.
- OPEN_SOURCE_APPLICATION — complete or substantial application source available for inspection.

### Design and pattern sources

- UI_KIT — design-oriented kit or component asset set.
- PATTERN_LIBRARY — catalog of interaction, UX, or interface patterns.
- FIGMA_RESOURCE — Figma/community resource or equivalent editable design artifact.
- TEMPLATE_OR_THEME — reusable visual or application template/theme.
- ICON_OR_ASSET_SYSTEM — iconography, illustration, asset, or visual-symbol system.

### Engineering analysis sources

- ENGINEERING_ARTICLE — engineering explanation or technical article.
- CASE_STUDY — contextual account of a design or engineering intervention and outcome.
- POSTMORTEM — retrospective analysis of a failure, incident, migration, or decision.
- REVIEW_DISCUSSION — code/design review, issue, RFC discussion, or documented technical debate.

### Specialist references

- ACCESSIBILITY_REFERENCE — accessibility-focused guidance or evidence.
- PERFORMANCE_REFERENCE — performance-focused guidance or evidence.
- SECURITY_REFERENCE — frontend/security-focused guidance or evidence.

### Weak or non-authoritative contextual sources

- DESIGN_INSPIRATION — visual or experiential inspiration without implied engineering proof.
- COMMUNITY_DISCUSSION — public discussion containing potentially useful claims or examples.
- COMMUNITY_OPINION — primarily subjective judgement or preference.

## Classification rules

1. Choose the class that best describes the source’s actual role in the acquisition run.
2. If a source spans multiple roles, select one primary type and record secondary tags rather than inventing an unsupported hybrid type.
3. Unknown classification remains unknown until resolved; do not force a record into a false category.
4. Classification never grants acceptance. Every source still requires qualification under SOURCE_AUTHORITY.md and ../protocols/SOURCE_EVALUATION.md.
5. Source taxonomy may be extended only by a later reviewed change when existing classes cannot truthfully represent new evidence.
