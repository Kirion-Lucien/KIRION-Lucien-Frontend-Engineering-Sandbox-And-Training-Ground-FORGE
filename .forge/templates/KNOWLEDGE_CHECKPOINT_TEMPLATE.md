# KNOWLEDGE CHECKPOINT — TEMPLATE

This template supplements the accepted K0–K7 protocol and `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`. Do not leave example values masquerading as observed evidence.

## Identity
- Run ID:
- Stage: A / B / C
- Batch ID (if B):
- Worker role:
- Stage disposition: DRAFT / READY_FOR_REVIEW / RELEASED / BLOCKED
- Authority: active handoff path + accepted decision ID:
- Canonical main at start: `main@<exact SHA>`
- Input branch/ref and exact SHA:
- Output branch:
- Output exact SHA: record in final stage report/issue after commit (not guessed inside its own commit)
- Commit(s):

## Bounded work
- Objective and negative cases:
- Authorized source families/IDs:
- Allowed output paths:
- Actual changed paths:
- Observation IDs or ID range:
- Claimed source URLs, versions, SHA/anchors and provenance:
- License/storage restrictions:

## Validation performed
Use only accepted evidence labels: PASS, FAIL, SOURCE INSPECTED, RUNTIME OBSERVED, NOT RUN, NOT OBSERVED, UNKNOWN, BLOCKED.

| Check | Evidence status | Exact source/SHA/log |
| --- | --- | --- |
| Input/source ancestry | | |
| Changed-file scope | | |
| JSON parsing | | |
| Schema conformance (distinct from parse) | | |
| Source-ID and observation-ID linkage | | |
| Unique IDs and batch cap | | |
| Prior accepted-record integrity | | |
| Evidence attribution / source spot-check | | |
| No promotion/stack/external mutation | | |
| Runtime/browser/AT (only if executed) | | |

## Handoff / blockers
- Completed artifact paths:
- Unresolved facts/contradictions:
- Checks not executed or not observed:
- Exact next safe task:
- STOP reason, if any:
- Maintainer stage release (required between A→B and B→C):
- Maintainer release reference / accepted checkpoint SHA:

## Return contract
Report exact final Git SHA, actual changed files, source/observation ID ranges, validation executed vs not run, unresolved limits, and one disposition: READY_FOR_STAGE_REVIEW / REWORK_REQUIRED / BLOCKED / SOURCE_DRIFT. These are workflow dispositions, not substitutes for evidence status labels.
