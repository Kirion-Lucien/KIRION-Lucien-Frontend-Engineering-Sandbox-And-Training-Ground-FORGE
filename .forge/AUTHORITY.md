# FORGE AUTHORITY

## Purpose

Define who may establish truth, who may change direction, and what sources outrank others.

## Authority precedence

When sources conflict, use this order:

1. **Explicit current human technical authority**
2. **Live repository evidence for what exists**
3. **Accepted Forge decisions**
4. **Current `.forge/SSOT_CURRENT.md` gate and state**
5. **Current bounded handoff**
6. **Current work ledger**
7. **Supporting references / historical records**
8. **Worker inference**

Lower layers may not override higher layers.

## Truth classes

### Repository truth
What files, commits, branches, tests, workflows, dependencies, and behavior actually exist.

Source: live Git and executed evidence.

### Architecture authority
What structures, invariants, dependencies, and boundaries are accepted.

Source: accepted decisions and Maintainer disposition.

### Work authority
What a worker may mutate now.

Source: current SSOT plus an exact bounded handoff.

### Product / training intent
What the human wants to achieve.

Source: explicit human direction.

Intent does not automatically prove repository architecture.

## Supersession

A new human direction may supersede an older accepted decision.

Before workers enforce the new direction, the Maintainer must:

1. identify the superseded rule;
2. record the replacement;
3. update the current SSOT/gate;
4. issue a new bounded handoff if implementation is required.

## Historical material

Historical files remain evidence of prior reasoning, not current authority, unless the current SSOT explicitly reactivates them.
