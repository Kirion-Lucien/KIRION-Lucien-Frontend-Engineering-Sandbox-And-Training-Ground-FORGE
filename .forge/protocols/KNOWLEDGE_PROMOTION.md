# KNOWLEDGE PROMOTION PROTOCOL

## Governing principle

Promotion changes authority state. It is therefore a Maintainer action, not a synthesis convenience.

## Promotion path

RAW SOURCE
→ OBSERVATION
→ CROSS-SOURCE COMPARISON
→ CANDIDATE
→ MAINTAINER REVIEW
→ ACCEPTED / REJECTED
→ DEPRECATED when superseded

## Candidate completeness gate

Before review, a pattern or anti-pattern candidate must have:

- defined context and problem or recurring structure;
- source IDs and observation IDs;
- authority and provenance preserved in those source records;
- rationale or harm mechanism tied to evidence;
- applicability and non-applicability or legitimate contexts;
- tradeoffs or consequences;
- counterexamples;
- accessibility, performance, maintainability, and responsive considerations where relevant;
- confidence;
- recency/version boundary;
- unresolved contradictions made explicit.

Missing evidence linkage is a blocker, not a reason to fill gaps with model memory.

## Maintainer review considerations

Review should consider:

- authority quality of supporting sources;
- independence of sources;
- agreement and disagreement;
- similarity between observed and target context;
- counterexamples and edge cases;
- reversibility and user risk;
- accessibility impact;
- performance impact;
- maintainability impact;
- responsive implications;
- technical version drift;
- licensing/provenance constraints.

No unaccepted numeric scoring model may be presented as objective truth.

## Contradiction handling

Conflicting evidence may produce:

- CONTEXTUAL TRADEOFF — both approaches are valid under different constraints;
- SCOPE NARROWING — candidate applies only to a smaller context;
- VERSION SPLIT — behavior differs by version or platform;
- REWORK — evidence is insufficient or incorrectly synthesized;
- REJECTED — claim is not supportable;
- UNRESOLVED — more evidence is required.

A vote count alone cannot resolve a technical contradiction.

## Acceptance

For ACCEPTED records, record accepted_by and accepted_at. Acceptance is bounded to the reviewed context and evidence; it does not create a universal law.

## Rejection

REJECTED records retain enough provenance to explain what was considered and why it was not promoted. Rejection is not evidence that the opposite claim is automatically true.

## Deprecation

DEPRECATED records retain historical provenance and identify deprecated_by and deprecation_reason. A later source does not automatically cause deprecation; replacement must be demonstrated.

## Worker guidance

Only accepted, context-applicable records may be surfaced as Forge-required guidance. Candidate material must remain visibly candidate.
