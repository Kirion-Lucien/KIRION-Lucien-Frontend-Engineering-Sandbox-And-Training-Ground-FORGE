# PATTERN LIFECYCLE

## Definition

A pattern is a reusable, contextual solution structure supported by evidence. It is not a style preference, repeated screenshot motif, package popularity signal, or automatically correct behavior.

## Lifecycle

RAW SOURCE
→ OBSERVATION
→ CROSS-SOURCE COMPARISON
→ CANDIDATE
→ MAINTAINER REVIEW
→ ACCEPTED / REJECTED
→ DEPRECATED when superseded

Allowed record states:

- OBSERVED — recurring solution observed but not yet synthesized as guidance.
- CANDIDATE — evidence compared and bounded reusable claim ready for review.
- ACCEPTED — Maintainer accepted the claim for a stated context.
- DEPRECATED — formerly accepted knowledge is no longer preferred/current for the identified context; replacement/reason is recorded.
- REJECTED — reviewed claim was not accepted.

## Candidate requirements

A candidate must state:

- problem and target context;
- observed solution;
- rationale supported by evidence;
- tradeoffs;
- applicability and non-applicability;
- accessibility, performance, and responsive implications;
- implementation notes without pretending one stack is mandatory;
- source IDs and observation IDs;
- known counterexamples;
- related patterns and anti-patterns;
- confidence and recency/version constraints.

A candidate with no evidence linkage is defective.

## Promotion considerations

Maintainer review considers source quality, independence, agreement/disagreement, context similarity, counterexamples, target applicability, accessibility impact, performance impact, maintainability impact, reversibility, and version/recency constraints.

No arbitrary numeric score may masquerade as objective truth unless the scoring model is separately reviewed and accepted.

## Contradictions and counterexamples

Disagreement is preserved. A source favoring confirmation for destructive operations and another favoring immediate reversible deletion with undo may indicate a CONTEXTUAL TRADEOFF rather than a winner.

Counterexamples must record why a pattern may not apply. Non-applicability is first-class knowledge.

## Worker use

Workers may use ACCEPTED patterns as reusable guidance only when the requesting context fits the acceptance boundary. CANDIDATE and OBSERVED patterns may be inspected but must stay labeled non-authoritative.

No worker may self-promote a candidate.
