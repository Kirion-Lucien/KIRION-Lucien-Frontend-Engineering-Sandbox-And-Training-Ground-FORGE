# KIRION FORGE: MAINTAINER — W07 STAGE B2 / K3 WHATWG OBSERVATION HANDOFF
# NATIVE DIALOG / POPOVER / INERT / FOCUS PLATFORM MECHANISMS

## Authority

**Stage A (K0–K2): ACCEPTED / released checkpoint** `0e4340649fb71aef1ef00e46caa8433342bf697a`, issue #17.

**Stage B1 (K3 WCAG): ACCEPTED / released checkpoint** `53084dd7c8f812732fc556873c3d7753c3aa1c3b`, issue #18.

**Stage B2:** AUTHORIZED — exactly one bounded WHATWG-only K3 observation batch, conditional on worker verification of the precise **B2 governance head SHA** published on issues #18 and #19 after this handoff and stage-state commits. The B2 governance SHA, not the B1 checkpoint SHA, is the starting mutating source. B1 checkpoint must be a verified ancestor.

**Later K3 batches:** BLOCKED; separate B2 checkpoint review/release.

**Stage C K4–K6:** BLOCKED pending completed extraction and Maintainer stage release.

**K7:** MAINTAINER ONLY — no pattern acceptance.

**Frontend app/dependencies/framework:** BLOCKED.

Role: `KIRION FORGE: FRONTEND KNOWLEDGE OBSERVATION WORKER — STAGE B2`.

Repository: `Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE`.

Canonical accepted main: `main@61987e3de3ff85426e293dd15e596200ad272103`.

Working branch: `forge/w07-dialogs-overlays-focus-intelligence` ONLY; fix forward, no alternate branches, no rebase or main merge.

If main is not the exact accepted SHA, the active issue and branch head disagree, the B1 checkpoint is not an ancestor, or any gate conflicts: `SOURCE_DRIFT`, STOP and return.

## Mandatory reads

Read `AGENTS.md` and all files required by it, W01 knowledge schemas/protocols, `.forge/protocols/KNOWLEDGE_WORKLOAD_ISOLATION.md`, `.forge/templates/KNOWLEDGE_CHECKPOINT_TEMPLATE.md`, accepted W07 Stage A `REQUEST.md`, `SOURCE_DISCOVERY.md`, `SOURCE_QUALIFICATION.md`, `SOURCE_ID_MAP.md`, `LICENSE_AND_RETRIEVAL.md`, `UNRESOLVED.md`, W07 existing B1 observations/index/checkpoint, issue #17 acceptance, issue #18 B1 release decision, and this B2 handoff.

## Source isolation — only S3 WHATWG

Source ID: **`W07-S3`** (already qualified; do not create another ID).

Provider/class: WHATWG `OFFICIAL_STANDARD / PRIMARY_NORMATIVE` within **HTML platform algorithms only**.

Only permitted primary source family:

```text
https://html.spec.whatwg.org/multipage/interactive-elements.html#the-dialog-element
https://html.spec.whatwg.org/multipage/interactive-elements.html#dialog-light-dismiss
https://html.spec.whatwg.org/multipage/popover.html
https://html.spec.whatwg.org/multipage/interaction.html#inert-subtrees
```

These are navigation anchors into the same logical source family. Follow adjacent subsections of the same WHATWG HTML standard only as needed to verify actual normative references, algorithms and terminology. **Do not use APG, WCAG, Primer, USWDS, MDN, WebKit/Chromium implementation, user blogs or an independent seventh source to substantiate B2 observations.**

The HTML Standard is a **Living Standard**, not an immutable published Recommendation. At extraction, record the actual retrieval time and any displayed last-update context; keep exact section anchors and avoid claiming an immutable version. Its algorithms are not browser or assistive-technology test results.

## Planned bounded observation targets — up to six

These are K3 research targets and IDs, **not prewritten conclusions**. Produce only source-grounded `OBSERVED` records if the direct specification supports them:

```text
W07-O07 — HTML dialog element, open state and modal versus nonmodal presentation paths, including show()/showModal() context.
W07-O08 — native modal dialog top-layer and surrounding document inertness/interaction boundaries.
W07-O09 — native dialog focusing steps, autofocus, and relevant initial focus conditions.
W07-O10 — native dialog closing/cancel/request-close paths and documented user-dismissal/light-dismiss conditions.
W07-O11 — popover attribute/state distinctions (auto/manual/hint where present) and algorithmic show/hide/light-dismiss boundaries.
W07-O12 — inert subtree model, focus/interaction semantics and relevant interaction with top-layer/modal contexts.
```

**Zero-to-six records** permitted. Targets may be skipped with documented evidence gap if a current HTML-standard anchor does not support the proposed bounded claim. Do not fabricate records or conflate several independent source claims merely to meet six.

All records must:
- use schema-valid IDs `W07-O07` … `W07-O12` only;
- `source_id: "W07-S3"`;
- `status: "OBSERVED"`;
- `evidence_kind: "NORMATIVE_TEXT"`;
- `domain` chosen from accepted observation schema (e.g. `MODALS`, `OVERLAYS`, `FOCUS_MANAGEMENT`, `SEMANTIC_HTML`, `INTERACTION`);
- retain exact algorithm scope, conditions, exceptions and non-applicability;
- include anchored source location, observation timestamp, source version/retrieval context and limitations;
- not present normative spec text as an empirical browser implementation result or user-tested UI design recommendation.

The B1 WCAG observations remain historical, unchanged and uncombined until an independently released Stage C.

## Owned mutation scope

Create only:

```text
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O07.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O08.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O09.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O10.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O11.json
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/observations/W07-O12.json
```

Modify only:

```text
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/OBSERVATION_INDEX.md
.forge/knowledge/runs/W07_DIALOGS_OVERLAYS_FOCUS/checkpoints/CHECKPOINT_LEDGER.md
```

Index must preserve W07-O01..O06 and append B2 entries distinctly by source/evidence class. Checkpoint ledger must preserve existing Stage A and B1 sections **byte-for-byte as a prefix**; append a separate B2 `READY_FOR_REVIEW` checkpoint section without self-referential final SHA. Publish final SHA after commit in report/issue.

No worker changes to `.forge/SSOT_CURRENT.md`, `.forge/WORK_LEDGER.md`, source registry, source qualification/rights files, prior W02–W06 records, Stage A/B1 history, accepted schemas, active handoff, README, external repos or any other paths.

## Source and rights

Registry `W07-S3` is qualified with `KNOWN_PERMISSIVE` (WHATWG HTML Living Standard under CC BY 4.0 with stated special code-inclusion terms) and `METADATA_ONLY` storage. **Store concise original paraphrased evidence descriptions and canonical URLs, not bulk source text or screenshots.** Provenance/version and attribution remain required.

Do not infer browser support by seeing feature-compatibility annotations within the spec. No package install, runtime, renderer, browser automation, a11y tool or component library.

## Validation and negative gates

Worker MUST:
1. reverify live canonical main SHA, B2 governance starting SHA from issues #18/#19, B1 exact accepted checkpoint ancestor, and Stage B2 SSOT/handoff release;
2. check all B1 observation file/blob SHAs and Stage A qualification files unchanged using exact diff or explicit blob comparisons; preserve accepted registry unchanged;
3. independently retrieve and inspect WHATWG HTML portions quoted/anchored for each actual observation; record official wording, special cases, algorithm steps and living revision time;
4. parse all new JSON, check required properties/types/enums/ID uniqueness/source linkage and accepted observation schema conformance; distinguish custom structural subset checks from a full Draft 2020-12 JSON Schema validator;
5. verify batch count maximum 6 and output paths only;
6. confirm index preservation and checkpoint prefix integrity;
7. state all validation NOT RUN: app build, typecheck, tests, runtime, browser focus/keyboard/AT, responsive-device and user usability;
8. stop on authority drift, spec access blockage, rights/copying contradiction, schema incompatibility, context degradation or scope spill. No substitute source.

Do not write source-derived **candidate patterns**, perform cross-source K4 comparison, alter current source registry or claim WHATWG requires every site to implement `<dialog>` or `popover`.

B2 completion does **NOT** authorize B3, Stage C or K7.

## Worker report — then STOP

Return exactly:

```text
KIRION FORGE — LUCIEN
W07 STAGE B2 / WHATWG HTML K3 CHECKPOINT REPORT

1. LIVE CANONICAL MAIN AND BRANCH HEAD
2. EXACT GOVERNANCE INPUT / ANCESTRY
3. ACCEPTED STAGE A AND B1 CHECKPOINTS
4. WHATWG SOURCE IDENTITY AND LIVING VERSION CONTEXT
5. OFFICIAL SPECIFICATION SECTIONS INSPECTED
6. CREATED OBSERVATION IDS (0–6), SOURCE ANCHORS AND LIMITATIONS
7. OBSERVATION INDEX INTEGRITY
8. APPENDED B2 CHECKPOINT
9. FILES CREATED / MODIFIED
10. JSON PARSE / SCHEMA CHECKS / CROSS-REFERENCE UNIQUENESS
11. NORMATIVE VS RUNTIME / SOURCE-CLASS BOUNDARIES
12. PRIOR W02–W06 KNOWLEDGE / STAGE A / STAGE B1 INTEGRITY
13. VALIDATION ACTUALLY EXECUTED
14. VALIDATION NOT EXECUTED / NOT APPLICABLE
15. CONTRADICTIONS / UNRESOLVED / SOURCE GAPS
16. COMMITS CREATED
17. EXACT FINAL BRANCH
18. EXACT FINAL SHA
19. WORKER RECOMMENDATION
```

Disposition exactly one: `READY_FOR_STAGE_REVIEW`, `REWORK_REQUIRED`, `BLOCKED`, `SOURCE_DRIFT`.

Then **STOP and return to Maintainer**. Do not self-release any further extraction stage or merge main.
