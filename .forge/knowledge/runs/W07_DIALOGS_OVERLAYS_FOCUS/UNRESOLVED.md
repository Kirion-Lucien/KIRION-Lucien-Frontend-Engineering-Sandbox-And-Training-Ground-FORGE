# W07 — STAGE A UNRESOLVED / MAINTAINER REVIEW

1. **WAI APG non-modal direct page:** `https://www.w3.org/WAI/ARIA/apg/patterns/dialog/` returned HTTP 404; no current standalone non-modal page independently qualified. Later Stage B must either use the modal page's explicit non-modal contextual statements with clear caveat or obtain a *separately authorized* scope update. Do not invent contents.
2. **WAI APG tooltip consensus:** official tooltip page declares work in progress and lacks task-force consensus. Stage B cannot elevate it to stable normative or consensus authority.
3. **WHATWG recency:** living standard is mutable; no immutable revision was pinned. Preserve retrieval timestamp and revalidate actual wording at Stage B.
4. **USWDS Modal and Primer product docs versions:** pages were reachable, but exact site build/release SHAs were not established. Do not assume agreement with pinned React code.
5. **Documentation reuse:** USWDS Modal and Primer product text licenses have `UNKNOWN` reuse status. Reference metadata only until rights clarified. No copying performed.
6. **Potential later investigation boundaries:** native dialog/popover/inert vs ARIA patterns vs design-system convention may differ by platform/version/task; this is a source-authority boundary, **not** a completed K4 contradiction comparison.
7. **K3 launch:** blocked until Maintainer independently reviews the exact Stage A Git candidate and records an explicit checkpoint SHA release on the issue and in governing handoff/SSOT.
8. **Stage B planning only:** provisional overall 24–36 observations (hard 42) and 5–8/batch default do not authorize a single observation at this stage.
9. **App/runtime evidence:** no keyboard focus, screen-reader speech, browser showModal/popover behavior, mobile sizing, nested overlay flow or close/recovery path tested.
10. **Prior authority:** W02-P02 and W03-A01 remain deferred; all 22 pre-W07 W02–W06 pattern/anti-pattern records must be preserved.
11. **Input SHA:** `64a292f24938e94ecc48f0379ad92ac72a037389`; current main baseline `61987e3de3ff85426e293dd15e596200ad272103`. No self-referential output SHA in tracked checkpoint.

**Maintainer decision requested:** review qualifications with stated gaps, validate exact branch candidate/rights/source identities and explicitly ACCEPT/REWORK/REJECT the Stage A checkpoint. This is a request for Stage A review, **not** worker release to Stage B.


---

# W07 C1 — APPEND-ONLY K4 UNRESOLVED EXTENSION

**Worker status READY_FOR_REVIEW.** Original Stage A unresolved material above is preserved as an exact prefix; the old Stage A launch items are historical, superseded by Stage B independent acceptance (issue #23 comment 6076211658) and C1 release at exact SHA 5a93297bea6cfa2267e1f775ff95781a6f989986 (issue #24). See [CROSS_SOURCE_COMPARISON.md](CROSS_SOURCE_COMPARISON.md) for 36 source-linked observations and [CONTRADICTIONS_AND_CONTEXT.md](CONTRADICTIONS_AND_CONTEXT.md) for 20 categorized comparison questions. No confirmed same-context DIRECT_CONFLICT, but no browser/app contradiction audit was performed.

1. **C01/C02:** Forced acknowledgment can differ from APG Escape while still requiring a viable keyboard-only path and real-task review; no concrete application/UI exists here.
2. **C05/C20:** Pinned default Dialog root aria-describedby references a conditional subtitle node; rendered DOM and assistive-technology outcome unknown, custom header could differ.
3. **C07/C08/C09/C17:** Imported focus, Escape and outside-click hooks, Portal top-layer and caller state not inspected/observed; WHATWG native close/popover behavior cannot be mapped automatically to Primer callbacks.
4. **C10/C11:** Tooltip APG is WIP/no consensus; pinned Tooltip v1 deprecation is version-bound, not contemporary Primer policy. Label/description/trigger relationships remain unverified across versions.
5. **C13/C18:** Keyboard focus visibility/exit, zoom, mobile, scroll, pointer and screen-reader behavior not tested. WCAG criteria apply with their actual scope and exceptions, not generic overlay requirements.
6. **C14/C19:** USWDS 14 publisher WCAG 2.1 AA checks last-tested v3.8.2 (13 PASS/1 CONDITIONAL), separate v3.13.0 site banner; no equivalence to WCAG 2.2 or Kirion tests. Pinned O33 is TEST_INTENT, not TEST_RESULT.
7. **C03/C04/C12/C15:** Native dialog, popover, inert, APG patterns and design-system components are different authority/interaction mechanisms. APG standalone nonmodal URL remained unavailable/404.
8. **C16 and gate:** Ordinary page vs modal choice depends on context, not decided in K4. **Zero patterns, zero anti-patterns, zero K6 packets created.** C2 requires separate Maintainer exact-SHA release; K7, application code and main merge blocked.

Source provenance: WHATWG living unpinned, APG tooltip provisional, USWDS/Primer product rights UNKNOWN, Primer pinned MIT 7f5303d803986887187d86dcebaeda22a4dc6823. No new external documents consulted.
