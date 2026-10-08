# DECISION LOG

The following decisions were accepted by Maintainer through GitHub issue #1.

## FORGE-0001 — Authority before architecture

**Decision:** Establish repository authority, evidence, classification, validation, work-ledger, and agent contracts before selecting a frontend stack.

**Reason:** The verified repository contains no architecture to inherit.

**Consequence:** Framework or package selection without a later accepted decision is unauthorized.

## FORGE-0002 — Evidence before claims

**Decision:** Any claim about repository state must be traceable to live Git, executed validation, or an explicitly identified human requirement.

**Consequence:** Generated prose and prior chat are supporting context, not repository truth.

## FORGE-0003 — Unknown preservation

**Decision:** Missing information is recorded as `UNKNOWN`, `INPUT REQUIRED`, or `DECISION REQUIRED` rather than being silently filled with defaults.

**Consequence:** Familiar industry choices remain proposals until accepted.

## FORGE-0004 — Maintainer gate

**Decision:** Discoverers/reviewers may establish evidence and classification; workers may enforce architecture only after explicit Maintainer acceptance.

**Consequence:** Worker lanes remain blocked while their controlling decision is under review.

## FORGE-0005 — Exact-source mutation

**Decision:** Every mutation lane begins from a re-verified branch/SHA and reports its final SHA.

**Consequence:** Drift is a stop condition, not something workers silently reconcile.

## Acceptance boundary

These decisions establish governance only.

They do not select a frontend framework, product architecture, package ecosystem, test stack, or curriculum.


## FORGE-0006 — Knowledge workload isolation and Git-checkpointed stage execution

**Decision:** Beginning with W07, substantive Lucien knowledge runs default to bounded K0–K2 qualification, K3 extraction batches, and K4–K6 comparison/synthesis stages. Persist artifacts and exact Git checkpoints; require Maintainer release between major stages and independent final review before K7. A small run may use fewer conversations if its handoff explicitly permits, but must retain all gates.

**Human authority:** Explicit approval on 2026-10-08 to replace monolithic session reliance with dedicated sessions and bounded batching.

**Reason:** Prevent context-related source attribution drift, skipped checks, schema inconsistency, and overclaiming while avoiding gratuitous session fragmentation.

**Binding protocol:** `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`.

**Consequence:** Fresh sessions must rehydrate from live Git and the exact last released checkpoint, not chat memory. Batch target 5–8 observations is a heuristic, not mandatory quotas. Workers may not self-release stages or self-promote K7 knowledge. Prior accepted patterns and record schemas are unchanged.

**Non-goals:** No W07 scope or execution release; no frontend framework, packages, runtime, application code, vector DB, CI architecture, or new autonomous promotion authority.
