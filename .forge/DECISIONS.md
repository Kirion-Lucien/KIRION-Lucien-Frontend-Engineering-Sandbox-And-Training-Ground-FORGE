# DECISION LOG

All entries below are **PROPOSED during W00** until GitHub issue #1 records Maintainer acceptance.

## FORGE-0001 — Authority before architecture

**Proposed decision:** Establish repository authority, evidence, classification, validation, work-ledger, and agent contracts before selecting a frontend stack.

**Reason:** The verified repository contains no architecture to inherit.

**Consequence:** Framework or package selection before W00 acceptance is unauthorized.

## FORGE-0002 — Evidence before claims

**Proposed decision:** Any claim about repository state must be traceable to live Git, executed validation, or an explicitly identified human requirement.

**Consequence:** Generated prose and prior chat are supporting context, not repository truth.

## FORGE-0003 — Unknown preservation

**Proposed decision:** Missing information is recorded as `UNKNOWN`, `INPUT REQUIRED`, or `DECISION REQUIRED` rather than being silently filled with defaults.

**Consequence:** Familiar industry choices remain proposals until accepted.

## FORGE-0004 — Maintainer gate

**Proposed decision:** Discoverers/reviewers may establish evidence and classification; workers may enforce architecture only after explicit Maintainer acceptance.

**Consequence:** Worker lanes are blocked while the controlling decision is under review.

## FORGE-0005 — Exact-source mutation

**Proposed decision:** Every mutation lane begins from a re-verified branch/SHA and reports its final SHA.

**Consequence:** Drift is a stop condition, not something workers silently reconcile.
