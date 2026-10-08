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
