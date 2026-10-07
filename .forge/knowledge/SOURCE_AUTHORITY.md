# SOURCE AUTHORITY AND EVIDENCE WEIGHT

## Purpose

Authority weight records how strongly a particular source can support a particular claim. It is not a reputation score, popularity score, visual-quality score, or automatic trust label.

Every source record preserves source class, authority weight, reason for weight, canonical identity, version context where available, retrieval date, license/provenance state, and recency status.

## Authority classes

- PRIMARY_NORMATIVE — controlling or normative authority for the claim within its stated scope.
- PRIMARY_IMPLEMENTATION — direct implementation evidence from the system, codebase, runtime, or artifact being studied.
- OFFICIAL_REFERENCE — first-party explanatory/reference material authoritative about its own product/system but not itself a normative standard.
- HIGH_QUALITY_SECONDARY — well-supported secondary analysis with identifiable expertise, primary evidence, reproducible reasoning, or measured results.
- SUPPORTING_REFERENCE — useful corroborating material that should not independently establish strong doctrine.
- INSPIRATION_ONLY — useful for visual, interaction, or conceptual exploration but insufficient alone for engineering claims.
- ANECDOTAL — experience report, discussion, or opinion with limited generalizability.
- UNKNOWN_QUALITY — source quality or authority has not yet been established.

## Weight assignment rules

1. Record an explicit authority_reason. Never infer high weight from stars, followers, search ranking, visual polish, brand prestige, or repetition across derivative sources.
2. Weight is claim-sensitive. A design system may be PRIMARY_IMPLEMENTATION for its own component behavior but not PRIMARY_NORMATIVE for general accessibility law.
3. First-party means authoritative about the documented system within its version and scope, not universally correct.
4. Multiple weak sources do not automatically equal one strong source.
5. Popularity is supporting context at most unless the research question is itself adoption/popularity.
6. When quality cannot be established, use UNKNOWN_QUALITY.

## Recency and version law

Technical knowledge must carry version context where available, including framework/library version, browser/platform version, design-system release, standards version, tag, release, or commit SHA.

Knowledge recency is:

- CURRENT — current for the observed source and stated context.
- VERSION_BOUND — valid only for an identified version/range or implementation snapshot.
- HISTORICAL — retained to explain prior behavior or decisions, not presumed current.
- SUPERSEDED — explicitly replaced by later authoritative material for the same context.
- UNKNOWN — currency cannot be established.

A later date does not automatically invalidate older evidence. Supersession must be established by scope, version, or explicit replacement.

## Contradictory authority

When high-quality sources disagree, preserve disagreement and compare context, scope, version, reversibility, user risk, and implementation constraints. Do not resolve conflict by majority vote alone.

## Acceptance boundary

Authority weight is evidence metadata. It does not itself make a pattern ACCEPTED. Pattern acceptance remains a Maintainer disposition under KNOWLEDGE_PROMOTION.md.
