# W07 — RIGHTS, VERSIONS AND RETRIEVAL LIMITS (K2)

**Retrieval day:** 2026-10-08; sources inspected in current Stage A session. Source-record `retrieved_at`: `2026-10-08T15:16:33Z`. Search-engine crawl recency is **not** an immutable source revision/version.

| Family | Rights and storage classification | Version, reliability and legal caveats |
|---|---|---|
| S1 W3C WCAG 2.2 | `PUBLIC_REFERENCE_ONLY`, original `W02-S1` rights untouched; registry source cites W3C copyright/document-use | Dated W3C Recommendation 12 Dec 2024; no source copying |
| S2 W3C APG | `PUBLIC_REFERENCE_ONLY`; official W3C materials referenced, not copied | Live unpinned APG, separate requested dialog URL 404, tooltip non-consensus WIP |
| S3 WHATWG HTML Living Standard | `KNOWN_PERMISSIVE`; WHATWG IPR Policy §7.1.1 says Living Standards under **CC BY 4.0**, with different BSD 3-Clause treatment for portions incorporated into source code. Metadata only in this run; attribution required for reuse | Continuous living HTML spec: `interactive-elements.html#the-dialog-element`, `popover.html`, `interaction.html#inert-subtrees`; retrieved as-of time rather than claiming immutable commit |
| S4 USWDS Modal | `UNKNOWN`: permission to copy product docs not independently verified; reference-only by Forge law | Official USWDS current modal page accessible, no immutable build SHA tied to page in this run |
| S5 GitHub Primer product guidance | `UNKNOWN`: product-doc reuse unverified; reference-only | Four current accessible pages; live docs not tied to pinned React code |
| S6 pinned primer/react | `KNOWN_PERMISSIVE`: verified pinned root LICENSE **MIT**; preserve notice if future source copy authorized, but **no vendoring** in Stage A | Exact SHA `7f5303d803986887187d86dcebaeda22a4dc6823` and five file blob hashes in SOURCE_DISCOVERY, source and tests only; no tests executed |

## Source retrieval and provenance restrictions

- Only six pre-approved logical source families; official subpages within a family do not create a new independent source family.
- No bulk crawl; a few direct official URLs and five exact pinned file reads plus LICENSE.
- The WAI APG `/patterns/dialog/` request returned 404. This is **not** the same as the accessible `/patterns/dialog-modal/` page.
- APG tooltip describes itself as WIP/no consensus, a material source-capability restriction for later Stage B.
- WHATWG algorithms are normative platform specification statements; they are not a screen recording, real-browser result or guarantee of accessibility in a product.
- MIT code can be read for version-bound evidence; permission to **vendor** into this repository is separately gated and was not invoked.
- Document rights classification and copyright storage controls remain independent from source evidence authority.

**Content storage policy for all new qualified records:** `METADATA_ONLY`; no external docs, source files, examples, screenshots, binaries, designs, or broad quotations copied.
