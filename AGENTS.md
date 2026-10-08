# AGENTS.md — KIRION LUCIEN FORGE CONTRACT

This file applies to the entire repository.

## 1. Mandatory read order

Before proposing or changing repository content, read:

1. `.forge/AUTHORITY.md`
2. `.forge/SSOT_CURRENT.md`
3. `.forge/EVIDENCE.md`
4. `.forge/CLASSIFICATION.md`
5. `.forge/DECISIONS.md`
6. `.forge/VALIDATION.md`
7. `.forge/WORK_LEDGER.md`
8. the exact active handoff, if one exists

If these sources disagree, stop and resolve the authority conflict before implementation.

## 2. Gate before work

The active gate is defined only by `.forge/SSOT_CURRENT.md`.

If it says `HOLD`, `BLOCKED`, `REVIEW`, or `INPUT REQUIRED`, a worker must not convert that state into implementation authority.

A repository name, issue title, user idea, prior chat, generated plan, or worker preference is not implementation authority by itself.

## 3. Evidence law

Workers must distinguish:

- **live repository fact**
- **accepted authority**
- **accepted decision**
- **derived inference**
- **proposal**
- **unknown**
- **runtime evidence**
- **not run / not observed**

Never upgrade source inspection into runtime proof.

Never upgrade a proposal into accepted architecture.

Never silently fill an unknown with a familiar industry default.

## 4. Repository-truth rule

Live Git is the authority for what currently exists.

Accepted Forge documents govern what may happen next.

Human authority may supersede Forge documents, but the supersession must be recorded before workers enforce it.

## 5. Role boundaries

### Maintainer
May classify evidence, accept/reject candidate authority, issue bounded handoffs, and disposition completed work.

### Discoverer / Reviewer
Read-only unless explicitly authorized. Finds reality, attaches evidence, identifies contradictions and unknowns.

### Code Writer
Mutates only the exact authorized branch and scope. Does not expand architecture because it seems convenient.

### QA / Validator
Reports only evidence actually executed or observed.

One assistant may perform multiple roles in separate passes, but it must not collapse the gates between them.

## 6. Stop conditions

Stop and return to Maintainer when:

- the source SHA moved unexpectedly;
- the requested change requires a new architectural decision;
- evidence contradicts the active handoff;
- a dependency, framework, package, service, or data model would be introduced without authority;
- the worker would need to guess a product requirement;
- scope would spill outside owned files or lanes.

## 7. Worker return contract

Every mutation lane must return:

- source branch and source SHA;
- final branch and final SHA;
- commits created;
- files changed;
- validation actually executed;
- evidence not executed;
- remaining risks/unknowns;
- confirmation of prohibited scope not touched;
- final disposition recommendation.

## 8. Bootstrap invariant

Until W00 is accepted, **no frontend implementation is authorized**.

After W00 is accepted, this file becomes the standing enforcement contract for future agents.


## 9. Knowledge workload isolation (FORGE-0006)

For substantive knowledge-acquisition runs from W07 onward, follow the accepted K0–K7 lifecycle with bounded A (K0–K2), B (K3 batches), and C (K4–K6) stages. Use Git-backed checkpoints, exact released checkpoint SHAs, stage-release gates, and independent Maintainer K7 review. A worker cannot infer release from its own successful commits. Read `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md` and use the checkpoint/stage templates. The rule does **not** authorize W07 or any frontend application implementation.
