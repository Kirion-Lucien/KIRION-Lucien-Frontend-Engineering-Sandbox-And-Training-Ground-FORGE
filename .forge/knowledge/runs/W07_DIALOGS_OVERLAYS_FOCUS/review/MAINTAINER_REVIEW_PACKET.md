# KIRION FORGE — W07 STAGE C2 K6 MAINTAINER REVIEW PACKET

**WORKER PREPARATION ONLY — READY_FOR_STAGE_REVIEW, NOT K7.** Four K5 records have candidate state **CANDIDATE** (never accepted). An independent Maintainer must inspect the exact final worker commit to ACCEPT / REWORK / REJECT / DEFER each record separately; **nothing in this file is a sign-off or K7 promotion**.

## 1. Immutable authority and checkpoint inputs

- Repository `Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE`; sole branch `forge/w07-dialogs-overlays-focus-intelligence`.
- Accepted canonical `main@61987e3de3ff85426e293dd15e596200ad272103`, unchanged at C2 preflight. **Do not merge.**
- W07 Stage A K0–K2 accepted `0e4340649fb71aef1ef00e46caa8433342bf697a`, issue #17.
- W07 Stage B1–B6 independently accepted: B1 `53084dd7c8f812732fc556873c3d7753c3aa1c3b`; B2 `791910cb0f623de36edfb301afbe6e7586ced214`; B3 `e1ee045c6ff16a89771272abefd4223ad2a2d4b6`; B4 `cf6d6ccc1a197efd3f24250821f3a0b7e55b00df`; B5 `36a0d143f31c04a38111c806464e83ecce21f901`; B6 `be19e287e14e31483392fb467ede90ba6f0a04b8` (issue #23, independent Stage B closure).
- Accepted C1 K4 comparison exact worker `977a6ebfd1b7e6a54ad04f142f1a18b287887cad`, independently accepted [issue #24](https://github.com/Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE/issues/24#issuecomment-6076535555) CLOSED/completed.
- Exact C2 released governance worker start **`98f0eb7751ed8bb6919e93213ec6aa8a3883d1fa`**, [issue #25](https://github.com/Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE/issues/25) OPEN; active handoff `.forge/handoffs/active/W07_STAGE_C2_CANDIDATE_SYNTHESIS_AND_REVIEW_PACKET.md` and FORGE-0006. C1→C2 governance five commits ahead/zero behind, no accepted evidence edits.
- **Output SHA not self-referenced** in this precommit file; worker must report final exact SHA after safe commit and read-back.

## 2. Evidence census, coverage and authority

**Accepted source-bound K3 corpus: 36 observations, all OBSERVED** (W07-O01..O36), accepted C1 **20 analytic comparison entries**, **0 confirmed DIRECT_CONFLICT** *within observed corpus only*. Full [comparison/36-ID source URL matrix](../CROSS_SOURCE_COMPARISON.md), [20-entry contradiction register](../CONTRADICTIONS_AND_CONTEXT.md), [historical and current unresolved boundaries](../UNRESOLVED.md).

| Qualified logical family | Source ID and accepted K3 coverage | Authority and verification limits |
|---|---|---|
| WCAG 2.2 W3C Recommendation 2024-12-12 | W02-S1, O01–O06 | NORMATIVE_TEXT limited to criterion applicability, exceptions and levels; not a universal dialog solution |
| WHATWG HTML Living Standard (retrieved 2026-10-08) | W07-S3, O07–O12 | NORMATIVE_TEXT for native platform algorithms; living/unpinned and NOT executed browser evidence |
| WAI-ARIA APG (retrieved 2026-10-08) | W07-S2, O13–O18 | INFORMATIVE; Tooltip page explicitly WIP/no task-force consensus; standalone nonmodal page unavailable (404); not a second WCAG normative vote |
| USWDS Modal (live unpinned) | W07-S4, O19–O24 | System usage/accessibility documentation; first-party publisher checklist, not Kirion tests; documentation license UNKNOWN |
| Primer Product Dialog/Tooltip/Popover/Overlay (live unpinned) | W07-S5, O25–O30 | Contextual product docs and API props, not native standards; UNKNOWN documentation rights; same publisher as React implementation |
| Primer React 7f5303d803986887187d86dcebaeda22a4dc6823 (5 permitted files) | W07-S6, O31–O36 | SOURCE_CODE in five records and O33 `OTHER / CODE_TEST_INTENT`; pinned MIT source does not prove runtime, pass tests, present-day product parity or universal Tooltip deprecation |

Source independence is limited: **W3C WCAG/APG** different authority classes, not two votes; **Primer Product/pinned code** same publisher with no verified version identity. WHATWG normative HTML scope is not WCAG conformance. USWDS and Primer docs UNKNOWN rights -> **original paraphrases and source links, no copied third-party text/code**. Confidence refers to strength of sourced mechanism, not measured usability or conformance.

**C1 analytic categories:** CONTEXTUAL_TRADEOFF 4; SOURCE_AUTHORITY_SPLIT 4; VERSION_MISMATCH 4; EVIDENCE_GAP 4; NOT_COMPARABLE 4; same-context DIRECT_CONFLICT 0 confirmed (not global absence). Outstanding C02 forced action; C05/C20 absent subtitle reference; C07 focus-return hooks; C09 native vs product popover; C10/C11 tooltip WIP and version; C13/C18 mobile/zoom/AT; C14/C19 tests versus intent.

## 3. K5 exact candidate inventory and selection discipline

**Generated: 2 patterns + 2 anti-patterns, below hard ceilings 3+2.** No P03 or third/fifth candidate was filled just to consume a quota. Every record uses schema-required attributes, at least one source ID, actual accepted W07 observation IDs and grounded counterexamples; all use `CANDIDATE`, with no accepted_by/accepted_at or promotional status. Each record has its own applicable and non-applicable contexts, performance and responsive limitations where its schema permits.

| Candidate path / ID | Present status and confidence | Focus | Supporting observation IDs | C1 tensions | Principal unresolved reviewer challenge |
|---|---|---|---|---|---|
| [W07-P01](../candidates/patterns/W07-P01.json) | `CANDIDATE` / MEDIUM | Interruption choice | `W07-O07`, `W07-O11`, `W07-O18`, `W07-O19`, `W07-O20`, `W07-O23`, `W07-O25` | C03 C12 C16 | No universal interruption threshold; no product brief, mobile measurement or comparison experiment. |
| [W07-P02](../candidates/patterns/W07-P02.json) | `CANDIDATE` / MEDIUM | Modal entry/exit/return focus | `W07-O01`, `W07-O02`, `W07-O03`, `W07-O04`, `W07-O08`, `W07-O09`, `W07-O13`, `W07-O14`, `W07-O15`, `W07-O16`, `W07-O20`, `W07-O21`, `W07-O22`, `W07-O26`, `W07-O31`, `W07-O32` | C01 C02 C04 C05 C06 C07 C08 C13 C20 | Forced-action exit unknown; opener may vanish; aria-describedby conditional issue; imported focus/escape hooks uninspected; browser/AT/zoom NOT RUN. |
| [W07-A01](../candidates/anti-patterns/W07-A01.json) | `CANDIDATE` / MEDIUM | False modality claim | `W07-O02`, `W07-O07`, `W07-O08`, `W07-O11`, `W07-O12`, `W07-O13`, `W07-O14`, `W07-O20`, `W07-O31`, `W07-O32`, `W07-O34` | C01 C02 C03 C04 C08 | No deployed false-modal instance observed; do not call it a measured WCAG failure. Nonmodal surfaces and forced tasks are valid countercontexts. |
| [W07-A02](../candidates/anti-patterns/W07-A02.json) | `CANDIDATE` / MEDIUM | Hidden critical tooltip-only information | `W07-O06`, `W07-O17`, `W07-O18`, `W07-O27`, `W07-O28`, `W07-O35` | C10 C11 C12 C18 | APG tooltip is WIP; pinned v1 deprecation not current; discoverability/outcome not measured; WCAG exceptions and nonessential tooltip use matter. |

No additional tooltip-centric universal pattern candidate was formed: APG O17 is WIP, HTML popover O11 and Primer Popover O29/O36 are not equivalent mechanisms, and native tooltip/trigger/user-input runtime was not observed (C09–C12/C18). No separate pinned Primer implementation pattern: imported useFocusTrap, useOverlay, useOnOutsideClick and useOnEscapePress were outside Stage B read scope; pinned code does not demonstrate hooks' actual behavior (C05/C07/C17/C20). No universal forced-action dismissal candidate because C02's keyboard/task/requirements tension remains unresolved.

## 4. Individual Maintainer decision cards (independent adjudication, not self-vote)

### W07-P01 — Interruption choice

- **Status:** `CANDIDATE` · **confidence:** `MEDIUM` · **recency:** `VERSION_BOUND` · **path:** [W07-P01](../candidates/patterns/W07-P01.json)
- **Problem and falsifiable mechanism:** Task interruption inappropriate for long structured content, field-local feedback or routine disclosure. Evaluate whether a proposed dialog preserves the task context relative to a page/inline/disclosure alternative; a task can falsify universal last-resort wording.
- **Support:** USWDS and Primer contextual advice align on short transient use and page/inline alternatives, APG disclosure and WHATWG are distinct mechanics. **Exact observation links:** `W07-O07`, `W07-O11`, `W07-O18`, `W07-O19`, `W07-O20`, `W07-O23`, `W07-O25`; **C1 comparison:** `C03 C12 C16`.
- **Challenging evidence / legitimate exceptions:** USWDS required acknowledgment can intentionally retain the interruption until an explicit choice is made. (W07-O20) Large dialog content can be presented in a dialog variant, but Primer asks whether a dedicated page is more appropriate. (W07-O25)
- **Material limits:** No universal interruption threshold; no product brief, mobile measurement or comparison experiment.
- **Independent decision options:** ACCEPT if task-conditional choice and nonmodal alternatives remain explicit; REWORK if wording sounds like mandatory last-resort law; REJECT if it assumes native/dialog equivalence; DEFER for project-specific task approval.


### W07-P02 — Modal entry/exit/return focus

- **Status:** `CANDIDATE` · **confidence:** `MEDIUM` · **recency:** `VERSION_BOUND` · **path:** [W07-P02](../candidates/patterns/W07-P02.json)
- **Problem and falsifiable mechanism:** Genuinely modal task with named purpose but lost focus entry/exit or incoherent restoration; validate actual focus transition, keyboard route, meaningful ordering and opener/task-continuation exceptions rather than assuming refs are executable guarantees.
- **Support:** WCAG provides conditional keyboard/focus criteria; APG conditional modal guidance; HTML native algorithms and product ref code illustrate distinct implementation levels. **Exact observation links:** `W07-O01`, `W07-O02`, `W07-O03`, `W07-O04`, `W07-O08`, `W07-O09`, `W07-O13`, `W07-O14`, `W07-O15`, `W07-O16`, `W07-O20`, `W07-O21`, `W07-O22`, `W07-O26`, `W07-O31`, `W07-O32`; **C1 comparison:** `C01 C02 C04 C05 C06 C07 C08 C13 C20`.
- **Challenging evidence / legitimate exceptions:** APG recommends a static first-focus target for complex/scrolling content instead of invariably selecting the first interactive control. (W07-O15) Post-close focus may go to a newly relevant workflow item when the invoking control no longer exists. (W07-O16) USWDS forced-action gate intentionally differs from an ordinary dismissible dialog. (W07-O20)
- **Material limits:** Forced-action exit unknown; opener may vanish; aria-describedby conditional issue; imported focus/escape hooks uninspected; browser/AT/zoom NOT RUN.
- **Independent decision options:** ACCEPT if framed as falsifiable lifecycle and actual-application validation obligation; REWORK if Escape/Tab/first focus universalized; REJECT if code hooks are called proven; DEFER for forced-gate/AT follow-up.


### W07-A01 — False modality claim

- **Status:** `CANDIDATE` · **confidence:** `MEDIUM` · **recency:** `VERSION_BOUND` · **path:** [W07-A01](../candidates/anti-patterns/W07-A01.json)
- **Problem and falsifiable mechanism:** Modality represented by backdrop/aria-modal while background remains interactive or no task-valid keyboard path exists. This is a potential mismatch to prove against rendered interaction and AT evidence, not an observed application failure.
- **Support:** WCAG keyboard exit, native inertness and APG truthful aria-modal support the proposed failure mechanism; pinned code supplies mechanics without proof of effects. **Exact observation links:** `W07-O02`, `W07-O07`, `W07-O08`, `W07-O11`, `W07-O12`, `W07-O13`, `W07-O14`, `W07-O20`, `W07-O31`, `W07-O32`, `W07-O34`; **C1 comparison:** `C01 C02 C03 C04 C08`.
- **Challenging evidence / legitimate exceptions:** An intentionally nonmodal HTML popover may expose background interaction and use manual dismissal; that is not a broken modal unless it falsely claims modality. (W07-O11) A forced-action acknowledgment may vary Escape/close controls if the user has an explicit task-valid choice and accessible keyboard path. (W07-O20)
- **Material limits:** No deployed false-modal instance observed; do not call it a measured WCAG failure. Nonmodal surfaces and forced tasks are valid countercontexts.
- **Independent decision options:** ACCEPT if it targets a false claim / missing keyboard way out, not all popovers; REWORK if treating CSS overlay as intrinsically bad; REJECT if claiming a tested bug; DEFER for actual AT behavior.


### W07-A02 — Hidden critical tooltip-only information

- **Status:** `CANDIDATE` · **confidence:** `MEDIUM` · **recency:** `VERSION_BOUND` · **path:** [W07-A02](../candidates/anti-patterns/W07-A02.json)
- **Problem and falsifiable mechanism:** Critical instructions supplied solely through initially hidden tooltip. Seek a concrete input mode or user path missing vital information; distinguish optional hint, native UA tooltip exception and author-controlled qualifying hover/focus content.
- **Support:** Primer explicitly warns about initially hidden important tooltip information; WCAG 1.4.13 governs qualifying additional content; provisional APG/disclosure distinguishes interactions. **Exact observation links:** `W07-O06`, `W07-O17`, `W07-O18`, `W07-O27`, `W07-O28`, `W07-O35`; **C1 comparison:** `C10 C11 C12 C18`.
- **Challenging evidence / legitimate exceptions:** Primer Product documents tooltip for supplementary information but explicitly warns to avoid relying on hidden tooltips for important content. (W07-O27) APG disclosure intentionally reveals controlled content on Enter/Space with state-matched aria-expanded, rather than relying on pointer-hover visibility. (W07-O18)
- **Material limits:** APG tooltip is WIP; pinned v1 deprecation not current; discoverability/outcome not measured; WCAG exceptions and nonessential tooltip use matter.
- **Independent decision options:** ACCEPT if limited to sole critical content with no discoverable alternative; REWORK if it bans all tooltips; REJECT if claiming WCAG universally forbids tooltip use; DEFER pending input-mode/AT verification.



## 5. Testing and validation truth

- **Observed/read:** exact live C2 issue/branch/main/ancestry preflight; accepted K3 source-linked records and C1 artifacts; existing schemas and governance; proposed record JSON structural checks before staging.
- **Prior publisher claim, not ours:** USWDS O24 reports 14 WCAG **2.1 AA** component tests, 13 passed/1 conditional (version last-test v3.8.2, separate v3.13.0 banner); not WCAG 2.2 or Kirion application PASS.
- **Pinned authored test INTENT, not result:** Primer React O33 `OTHER` cites Dialog.test.tsx assertions that were NOT RUN, not `TEST_RESULT`.
- **NOT RUN:** component tests, app build/typecheck, browser, keyboard, focus, screen reader/AT, zoom/mobile, accessibility conformance audits, upstream library suite, user study, performance metrics and independent Draft 2020-12 validator. Generic JS in-session structural validation is *not* a full external schema engine.

## 6. K7 decision questions and conditions reserved for Maintainer

1. Does each candidate state a falsifiable recurrent structure and narrow task applicability, rather than advice valid regardless of context?
2. Are observed sources direct for this specific mechanism? Are WCAG/HTML normative only **within** their domains, APG informative/WIP, design-system docs version/rights-limited, and pinned React only version-specific source?
3. Are all source IDs qualified and observation IDs exact? Are internal links, C1 disputes, and counterexamples traceable? Does evidence quality justify confidence without implied pass tests?
4. Are legitimate modal-required cases, task continuation, keyboard special-exit guidance, path-dependent exception, hover/focus exceptions, native manual popover and tooltip nonessential use preserved?
5. Does W07-P02 overbundle too many lifecycle behaviors? Rework/split/defer if one actionable, verifiable mechanism is not coherent.
6. For W07-A01: does 'no keyboard exit' require separate conformance review in a particular task rather than blanket Escape requirement? Are properly nonmodal contexts protected?
7. For W07-A02: is critical-content-only scope sufficient or does WIP APG/UNKNOWN product revision justify lower confidence/defer? No premature universal tooltip ban.
8. Does C20's conditional aria-describedby reference need targeted runtime/AT inspection under a future authorization rather than labeling a current accessibility bug?
9. Confirm no unreviewed change to prior accepted W02–W06 patterns and deferred W02-P02/W03-A01.
10. Independently compare final committed branch/tree to exact C2 input `98f0eb7751ed8bb6919e93213ec6aa8a3883d1fa`, inspect only authorized paths, verify old checkpoint ledger exact prefix, test chosen candidates against schemas/source IDs and **explicitly ACCEPT, REWORK, REJECT or DEFER** one by one. Only then decide any K7 promotion; do not rely on worker self-report.

## 7. Hard stop

C2 creates review material, **not** K7 knowledge. No promotion, no Stage C self-close, no framework/library selection, no app files/assets/packages/tests, no GitHub issue status update or comment required, no PR and **no main merge**. K7 remains under the independent Maintainer acting with Kirch's Technical Authority.
