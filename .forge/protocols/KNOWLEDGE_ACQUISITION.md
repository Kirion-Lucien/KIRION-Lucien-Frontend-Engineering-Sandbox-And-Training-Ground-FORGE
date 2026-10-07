# KNOWLEDGE ACQUISITION PROTOCOL

## Purpose

Every acquisition run must move through K0-K7. The stages separate discovery from qualification, observation, synthesis, and authority.

## K0 — Request

Resolve and record:

- acquisition goal;
- requested knowledge domain;
- target audience or workflow;
- target-specific versus broad research mode;
- requesting authority;
- known constraints;
- explicit non-goals.

If the request cannot be bounded without inventing requirements, stop as INPUT REQUIRED.

## K1 — Source discovery

Find candidate sources only.

At this stage:

- capture enough identity to revisit the source;
- do not extract generalized conclusions;
- do not assign pattern acceptance;
- do not treat search ranking or popularity as authority.

Discovery output is a candidate source set, not a knowledge result.

## K2 — Source qualification

For each candidate source:

- verify source identity and provider;
- assign source_type;
- assign authority_weight with an authority_reason;
- capture canonical URL, repository, and path;
- capture version, release, date, tag, or commit SHA where available;
- capture license/provenance state;
- classify recency/currentness;
- choose lawful content-storage policy;
- reject or quarantine sources whose identity/evidence cannot be responsibly used.

Only qualified sources enter the source registry.

## K3 — Observation extraction

Extract bounded observations linked to source IDs and precise evidence locations.

Rules:

- observation describes what the evidence shows;
- observation does not silently become a recommendation;
- distinguish normative text, documentation statement, source code, runtime behavior, visual artifact, measurement, test result, review discussion, and other evidence;
- record limitations and source-version context;
- preserve contradictions rather than normalizing them away.

## K4 — Comparison

Cluster observations by domain, problem, context, and relevant version.

Compare:

- source quality and independence;
- agreement and disagreement;
- contextual differences;
- alternative solutions;
- accessibility implications;
- performance implications;
- maintainability implications;
- responsive implications;
- counterexamples;
- recency/version boundaries.

“Majority wins” is not a valid comparison rule.

## K5 — Candidate synthesis

Produce only bounded outputs:

- pattern candidates;
- anti-pattern candidates;
- vocabulary or terminology discoveries;
- unresolved questions;
- explicit non-applicability and counterexamples.

Candidate synthesis must link back to source and observation records. Do not invent evidence to complete a preferred answer.

## K6 — Review packet

Return candidate knowledge to Maintainer with:

- acquisition scope and source set;
- evidence quality;
- candidate records;
- contradictions and counterexamples;
- unresolved questions;
- license/provenance limitations;
- recency/version boundaries;
- recommendation for ACCEPT, REJECT, REWORK, or continued investigation.

K6 is not promotion.

## K7 — Promotion

Only after Maintainer disposition:

- mark accepted, rejected, or deprecated states as authorized;
- record acceptance authority and time for accepted records;
- preserve rejected knowledge for provenance where useful;
- connect deprecated records to replacement/reason;
- update reusable worker guidance only from accepted records.

No worker may perform K7 by inference or self-acceptance.

## Stop conditions

Stop and return to Maintainer when source identity changes materially, licensing blocks intended storage/use, evidence requires an unapproved architecture assumption, scope expands beyond the request, or high-severity contradictions cannot be bounded.
