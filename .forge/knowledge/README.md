# LUCIEN KNOWLEDGE CONTROL PLANE

## Purpose

This directory defines how Lucien may acquire frontend-engineering knowledge without converting raw internet material, visual taste, popularity, or model memory into authority.

The governing lifecycle is:

SOURCE
→ ACQUISITION RECORD
→ OBSERVATION
→ CLASSIFICATION
→ COMPARISON
→ CANDIDATE
→ MAINTAINER REVIEW
→ ACCEPTED / REJECTED / DEPRECATED

No stage may be silently skipped.

## Core separation

A source is not a recommendation.
An observation is not a recommendation.
A repeated pattern is not automatically correct.
Popularity is not authority.
Visual quality is not engineering proof.
Public availability is not license permission.
Model memory is not evidence.

Only Maintainer-dispositioned knowledge may become accepted reusable Forge guidance.

## Control-plane map

- SOURCE_TAXONOMY.md — source class.
- SOURCE_AUTHORITY.md — evidentiary authority.
- KNOWLEDGE_SCHEMA.md — domain vocabulary and record rules.
- PATTERN_LIFECYCLE.md — pattern promotion and use.
- ANTI_PATTERN_LIFECYCLE.md — evidence-bearing failure-mode model.
- DESIGN_REFERENCE_POLICY.md — design evidence boundaries.
- LICENSING_AND_PROVENANCE.md — attribution, storage, and reuse.
- registry/ — source registry; intentionally empty at W01 completion.
- schemas/ — machine-readable record contracts.
- ../protocols/ — acquisition, qualification, and promotion.
- ../templates/ — bounded intake/candidate templates.

## Worker consultation contract

When another Forge worker asks Lucien for guidance, the answer MUST separate evidence state from recommendation state and SHOULD use:

QUERY
DOMAIN
TARGET CONTEXT

ACCEPTED PATTERNS
CANDIDATE PATTERNS
RELEVANT ANTI-PATTERNS

IMPLEMENTATION CONSTRAINTS
ACCESSIBILITY CONSIDERATIONS
PERFORMANCE CONSIDERATIONS
RESPONSIVE CONSIDERATIONS

REFERENCE SOURCES
COUNTEREXAMPLES
UNRESOLVED QUESTIONS

CONFIDENCE
AUTHORITY STATUS

Rules:

1. ACCEPTED PATTERNS may be presented as reusable Forge guidance only when accepted for the requesting context.
2. CANDIDATE or OBSERVED material must stay labeled and cannot be phrased as Forge law.
3. Preserve relevant version, recency, provenance, and licensing limits.
4. Surface contradictory evidence rather than averaging it away.
5. Context-free claims such as “always use X”, “never use Y”, “professional apps use Z”, or “industry standard is Q” are prohibited unless applicable accepted authority supports them.
6. Prefer contextual wording: for context C, evidence A/B/C supports pattern P because of stated tradeoffs and constraints.

## W01 boundary

This control plane contains no ingested source knowledge, accepted Golden Patterns, accepted anti-patterns, frontend stack choice, application code, dependency manifest, vector database, or third-party design pack.

W01 establishes machinery only.
