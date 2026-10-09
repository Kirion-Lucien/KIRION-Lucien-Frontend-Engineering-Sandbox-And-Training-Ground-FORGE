# KIRION FORGE — LUCIEN CODE RESEARCH WORKER

## W07 STAGE B6 — PINNED PRIMER REACT IMPLEMENTATION K3 SOURCE OBSERVATIONS

**STATUS: MAINTAINER AUTHORIZED — ONE BOUNDED PINNED SOURCE-FAMILY BATCH, K3 ONLY.**

- **Human Technical Authority:** Kirch Ivan Balite. Maintainer controls stage release and acceptance, not the Observation Worker.
- **Canonical accepted main:** `main@61987e3de3ff85426e293dd15e596200ad272103`; never mutate.
- **Only existing worker branch:** `forge/w07-dialogs-overlays-focus-intelligence`; no branch creation or reset.
- **Accepted exact B5 worker checkpoint:** `36a0d143f31c04a38111c806464e83ecce21f901`, independent Maintainer acceptance **issue #22 comment 6074967674**.
- **B6 EXACT mutating governance input:** issued after these governance commits in **GitHub tracking issue #23**; do not derive from this file or prior B5 SHA.
- **Policy:** `FORGE-0006` — `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`; W01 K0–K7; accepted schema and Stage A qualified registry.

### Hard preflight gate
Before any B6 worker change: independently read LIVE Git `main`, worker branch and issue #23 to verify **exact issued B6 start SHA**, confirm accepted B5 is ancestor and issue #22 is CLOSED/completed with separate Maintainer comment, verify sole active B6 handoff, intact prior O01..O30 records, source `W07-S6` and its correct path set. Abort and report SOURCE_DRIFT or BLOCKED on inconsistency. No worker self-release.

### Source family W07-S6 — pinned primary implementation
Only authorized external read-only repository/version:
```
primer/react@7f5303d803986887187d86dcebaeda22a4dc6823
```
Only authorized EXACT five files:
```
packages/react/src/Dialog/Dialog.tsx
packages/react/src/Dialog/Dialog.test.tsx
packages/react/src/Overlay/Overlay.tsx
packages/react/src/Tooltip/Tooltip.tsx
packages/react/src/Popover/Popover.tsx
```
Source ID **`W07-S6`**, classification `COMPONENT_LIBRARY / PRIMARY_IMPLEMENTATION`, source version `VERSION_BOUND`, license `KNOWN_PERMISSIVE / MIT` verified at Stage A; evidence content policy `METADATA_ONLY`. Fetch these **at exact immutable commit**, never HEAD/main/latest and no automatic dependency traversal. The five exact file paths/blob identities were independently reverified at handoff. No writes to `primer/react`.

**Do not infer that live Primer Product docs from B5 (W07-S5) describe this exact revision.** Notably the inspected pinned `Tooltip.tsx` bears `@deprecated` declarations; capture this actual version-bound caveat, not a blanket claim about current Primer or all tooltip APIs. Pinned `Dialog.test.tsx` contains authored assertions, not tests executed by Forge.

Produce metadata, bounded original behavioral descriptions, file/line and symbol evidence locations (GitHub `blob/7f5303...` links), exact blob SHA when available, source intent/test-intent limits and no copied code corpus. Do not execute source, import packages, reproduce large code excerpts, or call test definitions `PASS`.

### 0–6 bounded extraction targets (NOT presumed outcomes)
- **`W07-O31`** — Dialog production code's semantic role/name/description or state conventions from `Dialog.tsx`; be specific, distinguish conditional branches.
- **`W07-O32`** — Dialog focus trap, initial/return focus and Escape/close event-control flow from `Dialog.tsx` only, including use of imported hooks vs proof of their implementations.
- **`W07-O33`** — `Dialog.test.tsx` authored test assertions and contexts (such as role/focus/close) as **`CODE_TEST_INTENT`** or the precise allowed schema evidence kind; **never `TEST_RESULT`** unless tests are truly executed and separately authorized. If schema lacks `CODE_TEST_INTENT`, use schema-allowed intent classification with explicit explanation; no novel enum.
- **`W07-O34`** — Overlay implementation props/refs/portal/escape/outside-click handling in `Overlay.tsx`; avoid claiming actual events were observed.
- **`W07-O35`** — `Tooltip.tsx` pinned rendering/accessible relationships and **deprecated version-specific** API markings; do not mislabel deprecated as current policy.
- **`W07-O36`** — `Popover.tsx` conditional visibility/positioning/close handling and boundaries; distinguish useOnEscapePress/useOnOutsideClick hook calls from actual hook implementation not separately authorized.

Use **only schema-allowed evidence kinds** appropriate to source code (`CODE_INSPECTION` / `CODE_TEST_INTENT` are investigation labels, not permission to invent enums); verify actual observation schema before writing and use its exact allowed names. If a target is unsupported, omit it. 0–6 is acceptable. Scope is ONE pinned family; do not conduct K4 comparison with WCAG, APG, WHATWG, USWDS or product docs. Reading earlier observations is allowed ONLY for integrity. Source tests do not establish that code works in browser, accessibility conformance, version parity, execution PASS, nor Kirion's adopted architecture.

### Worker-owned paths only
Create 0–6:
```
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O31.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O32.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O33.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O34.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O35.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O36.json
```
Append only:
```
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/OBSERVATION_INDEX.md
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/checkpoints/CHECKPOINT_LEDGER.md
```
Preserve exact pre-B6 index/checkpoint prefixes, all O01..O30 blobs, W02..W06 accepted/deferred knowledge, registry/qualifications, schema, governance handoffs, SSOT, work ledger and protocols. No other path writes. **BLOCKED**: K4–K6, K7, external implementation edits, frontend app code, framework/component selection, packages, PR/merge, main mutation, tests-fabrication.

### Worker validation/reporting
Verify committed SHA and one authorized diff, exact main/branch, six IDs/source/provenance uniqueness, permitted schema enums, JSON parse, historical prefixes, protected file integrity. Record actual checks and limitations, explicitly separate full Draft 2020-12 validator from custom subset. If application build/test, runtime, browser, keyboard, AT, responsive or source test suite NOT RUN, say NOT RUN; assertions read from committed test files count `SOURCE INSPECTED`, not tests executed. Report exact output SHA after commit, observed targets, source files/paths and full pinned SHA, changed files, gaps/caveats and READY_FOR_STAGE_REVIEW / REWORK_REQUIRED / BLOCKED / SOURCE_DRIFT.

**STOP for independent Maintainer B6 acceptance and explicit Stage B closure decision** before any K4–K6 stage. Never self-close Stage B or begin K7.
