# HANDOFF LAW

A handoff grants bounded mutation authority. It does not create architecture authority by itself.

## Required fields

Every implementation handoff must state:

- role
- repository
- source branch
- exact source SHA
- target branch strategy
- owned files/scope
- accepted decision IDs it relies on
- required outcomes
- architecture invariants
- prohibited scope
- validation required
- stop conditions
- return contract

## Active vs historical

A handoff is active only when the current `.forge/SSOT_CURRENT.md` explicitly points to it or identifies its work item as executable.

Directory names such as `active` are never enough by themselves.

## Drift

If the source SHA moves before work begins:

`STOP → REPORT DRIFT → RETURN TO MAINTAINER`

Do not silently rebase, reset, merge, or reinterpret the lane.

## Completion

A worker completion report is evidence for Maintainer review.

It is not self-acceptance.

The Maintainer must disposition the result before downstream work treats it as accepted.
