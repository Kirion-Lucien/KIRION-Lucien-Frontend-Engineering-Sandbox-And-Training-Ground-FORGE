# W07 — K1 SOURCE DISCOVERY AND RETRIEVAL LOG

**Evidence class:** source identity/access discovery only. No K3 observation or generalizable dialog rule is recorded here. **Retrieval:** 2026-10-08 (Philippines, approx 23:16); exact source-record ISO timestamp `2026-10-08T15:16:33Z`. Web retrieval reports source crawling dates separately, which are **not** equivalent to immutable page revisions.

| Family | Requested exact URL(s) and access status | Approved contribution / boundary |
|---|---|---|
| S1 WCAG | https://www.w3.org/TR/WCAG22/ — **RETRIEVED**, first-party W3C Recommendation 12 Dec 2024 | Normative accessibility criteria, not a UI component implementation; registry reuse W02-S1 |
| S2 WAI APG | https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/ — **RETRIEVED**; https://www.w3.org/WAI/ARIA/apg/patterns/dialog/ — **404 NOT FOUND**; https://www.w3.org/WAI/ARIA/apg/patterns/tooltip/ — **RETRIEVED WITH WIP/NO TASK-FORCE CONSENSUS FLAG**; https://www.w3.org/WAI/ARIA/apg/patterns/disclosure/ — **RETRIEVED** | Official **explanatory**, non-normative patterns; standalone current `/dialog/` target unqualified; no invented redirect/non-modal guidance |
| S3 WHATWG | https://html.spec.whatwg.org/multipage/interactive-elements.html#the-dialog-element — **RETRIEVED**; https://html.spec.whatwg.org/multipage/popover.html — **RETRIEVED**; https://html.spec.whatwg.org/multipage/interaction.html#inert-subtrees — **RETRIEVED** | Normative HTML Living Standard platform semantics/algorithms within actual scope; living revision not pinned; no browser-implementation proof |
| S4 USWDS | https://designsystem.digital.gov/components/modal/ — **RETRIEVED** | Official first-party Modal component guidance; product-specific, live docs exact source SHA unpinned |
| S5 Primer docs | https://primer.style/product/components/dialog/ — **RETRIEVED**; https://primer.style/product/components/tooltip/ — **RETRIEVED**; https://primer.style/product/components/popover/ — **RETRIEVED**; https://primer.style/product/components/overlay/ — **RETRIEVED** | Official first-party design-system pages; no indication of immutable match to pinned `primer/react` |
| S6 pinned Primer source | `primer/react@7f5303d803986887187d86dcebaeda22a4dc6823` — **READ ONLY VERIFIED**, see exact file list below | Precise implementation/test-intent source; not runtime evidence |

## Exact pinned file existence and provenance
All five handoff-bounded files were independently fetched from the exact commit:
- `packages/react/src/Dialog/Dialog.tsx` — blob `ef7b8d888d43b695ca4b8ba75b19945ba3c6ca13`
- `packages/react/src/Dialog/Dialog.test.tsx` — blob `21f1fc2447c21db55b2a28b0fea5644ea5174189`
- `packages/react/src/Overlay/Overlay.tsx` — blob `31ee7ebcf5d87cdee65f6b23795e47a5ef6bce91`
- `packages/react/src/Tooltip/Tooltip.tsx` — blob `0869b05538331c43900743d22d1560bf5d061d29`
- `packages/react/src/Popover/Popover.tsx` — blob `2acaec9c0f77f089c5d32b3ecbff85adab546e29`
- `LICENSE` — blob `7a22bf3f7a261e32e9552915a45032fd8b2cc746`, MIT.

These file identities were checked only; no component tests executed and no code copied into the Lucien repository.

## Known retrieval gaps
The specific requested WAI APG non-modal `/patterns/dialog/` target returns HTTP 404. An unrelated search result is **not** a permitted replacement. The official modal APG page can support bounded later discussion where it explicitly discusses non-modal differences, but not a new nonexistent standalone page. Tooltip APG page states the pattern is work in progress and lacks task-force consensus: qualification is **qualified with caveat**, not an acceptance claim.

No seventh logical family and no source-family substitution.
