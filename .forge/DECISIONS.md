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
