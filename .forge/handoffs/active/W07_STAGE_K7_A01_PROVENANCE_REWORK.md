# KIRION FORGE: CODE WRITER — LUCIEN / W07 K7-A01 PROVENANCE REWORK

## AUTHORITY — ONE-RECORD FIX-FORWARD ONLY
**State:** Maintainer-authorized bounded rework; NOT K7 acceptance, status promotion, source acquisition, or frontend implementation.
**Human Technical Authority:** Kirch Ivan Balite. **Independent K7 Maintainer:** Nox decision recorded on issue #26 comment `6085714859`; review outcome three ACCEPT *decisions only*, A01 REWORK.
**Repo:** `Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE`.
**Only existing branch:** `forge/w07-dialogs-overlays-focus-intelligence`, no new branch.
**Canonical main:** `61987e3de3ff85426e293dd15e596200ad272103` (frozen; do not touch).
**Reviewed K7 decision input:** `7c2d86e7712ac82bfb3d49af483d8fb8c12dd15c`, issue #26 CLOSED/completed as adjudication; this does NOT mean knowledge promoted.
**Exact new worker governance start SHA:** supplied in tracking **issue #27** after this handoff/SSOT/ledger release. Confirm live HEAD matches exactly before any file change; STOP on drift.
**Governance:** FORGE-0006, W01 K0–K7 record lifecycle, approved schema and source register.

## REQUIRED EXACT DEFECT
K7 decided `W07-A01` REWORK because `W07-O11` (WHATWG HTML manual/nonmodal popover, registered source `W07-S3`, `status=OBSERVED`) is explicitly linked in one A01 counterexample and named in the K6 review packet's candidate evidence inventory, but is missing from A01's root `observation_ids`. This is **semantic provenance/index inconsistency, not a JSON-schema structural failure**. No other substantive defect was approved to repair.

## ALLOWED WRITE 1 — EXACT JSON INDEX CORRECTION
Path:
```
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/candidates/anti-patterns/W07-A01.json
```
Edit **ONLY** root `observation_ids` by inserting the exact string `"W07-O11"` **once**, in ascending ID sequence **after `W07-O08` and before `W07-O12`**. Preserve all other IDs, order, fields, values, JSON structure, source IDs, caveats, evidence attribution, counterexample text, `confidence=MEDIUM`, `recency=VERSION_BOUND`, and **`status=CANDIDATE`**. Do not add `accepted_by`, `accepted_at`, or other K7 acceptance metadata.

The existing counterexample specifically attributes O11 to qualified W07-S3. The K6 packet already names O11; keep the K6 packet READ-ONLY. If schema or authoritative source contradicts this precise one-value insertion, STOP and report rather than pivoting scope.

## ALLOWED WRITE 2 — APPEND-ONLY CHECKPOINT
Path:
```
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/checkpoints/CHECKPOINT_LEDGER.md
```
Append a bounded K7-A01 provenance rework checkpoint stating issue #27, exact start SHA, what one JSON field changed, source/observation verification, tests actually RUN/NOT RUN, the continued `CANDIDATE` state, pending independent acceptance and no promotion. **All previous bytes must remain the exact prefix**. Do not attempt to insert post-commit SHA into that same commit.

## PROTECTED / FORBIDDEN
- `W07-P01`, `W07-P02`, `W07-A02` untouched. Their K7 `ACCEPT` *decisions* survive; stored `CANDIDATE` statuses cannot change under this handoff.
- W07 O01–O36, `OBSERVATION_INDEX.md`, C1 K4 comparisons, contradictions, `UNRESOLVED.md`, K6 packet, Stage A qualifications, all source registry/schema files, historical checkpoints except allowed append, previous W02–W06 knowledge/deferred records, and FORGE protocol immutable.
- No `main` merge, PR, new branch, app/frontend/backend, framework, runtime, tests fiction, independent sources, candidate creation or schema migration.
- Lucien worker must not self-accept A01 or revise the independent Nox K7 decision.

## INDEPENDENT WORKER CHECKS / STOP CONTRACT
1. Verify exact start SHA from issue #27, canonical main unchanged, issue #26 CLOSED with Nox comment `6085714859`, and only this rework active handoff.
2. Confirm exactly 2 file deltas: A01 JSON root observation_ids + O11 once (no other semantic JSON diff) and append-only checkpoint. Correct source O11 W07-S3 link, existing nonmodal exception/counterexample maintained.
3. Parse record and evaluate against actual anti-pattern schema, no fabricated full external Draft 2020-12 PASS. All four candidates remain `CANDIDATE`. Verify all protected old blobs or at minimum compare exact Git changed paths from the authorized start.
4. No app tests needed or authorized. Explicit `NOT RUN` for browser, keyboard, AT, performance, build/typecheck, upstream test suite and unexecuted validators.
5. Commit non-force on sole existing branch only after expected SHA check. Return exact final worker commit, delta, validation, and `READY_FOR_STAGE_REVIEW` or `BLOCKED`, then STOP.

**Next independent gate:** Maintainer re-review of A01 provenance at exact worker commit, then separate K7 disposition review as appropriate. Three preapproved candidates do not automatically promote. **Separate SHA-bound record-promotion authorization required for any `ACCEPTED` status**; K7 remains Maintainer-only.
