# KIRION FORGE: MAINTAINER REVIEW PACKET
## W02 CONTROLLED PILOT — ACTION CONTROLS (K6)

## RUN ID

W02_ACTION_CONTROLS_PILOT

## EXACT LUCIEN SOURCE

- Canonical accepted source: main@9b4d291b15322afd46ee83ccb9a6dc40e31d3b06
- Verified governance source: forge/w02-controlled-pilot-action-controls@e430342aaf98c34f9505dbd248ba958aa334b731
- W02 worker candidate branch: forge/w02-controlled-pilot-action-controls
- Final candidate SHA: see exact GitHub branch/worker return; this packet is created before the commit object, so no SHA is invented here.
- Governing issue: #5
- Current authority: worker submission for independent Maintainer review only; **not accepted**.

## SOURCE SET

1. W02-S1 W3C WCAG 2.2 (official normative accessibility criteria).
2. W02-S2 GOV.UK Design System Button (official system reference).
3. W02-S3 Primer Product Button (official system reference).
4. W02-S4 primer/react@7f5303d803986887187d86dcebaeda22a4dc6823 (exact implementation snapshot).
5. W02-S5 Landbook landing-page listing (inspiration only).

## QUALIFICATION SUMMARY

Five qualified logical source records. W3C standard is normative within its criteria; GOV.UK and Primer docs describe their systems; primer/react proves only pinned code; Landbook listing supports only curation metadata. No sixth independent source. Details in SOURCE_QUALIFICATION.md.

## OBSERVATION COUNT

20: S1=6; S2=5; S3=4; S4=4; S5=1. IDs W02-O01 through W02-O20, all OBSERVED and individually recorded with evidence locations.

## HIGH-CONFIDENCE FINDINGS

- WCAG SC 2.1.1 (keyboard), 2.4.7 (focus visible), 2.4.11 (focus not fully obscured), 2.5.8 (pointer target size including exceptions), 4.1.2 (name/role/value) and 4.1.3 (status messages) have verified text and levels (S1/O01–O06).
- GOV.UK describes action-specific labels, a main default button, secondary and warning variants, and cautions against confusing disabled buttons (S2/O07–O11).
- Primer documents primary/default/invisible/danger roles, loading and inactive states (S3/O12–O15).
- Pinned implementation has native Button and LinkButton defaults and code paths for aria-disabled, loading announcements and toolbar-conditional horizontal arrows (S4/O16–O19). HIGH confidence that code exists, NOT proof of its runtime behavior.

## LOWER-CONFIDENCE FINDINGS

- User-comprehension benefits of single-primary hierarchy are described by design systems but not measured in this W02 run.
- Focus-preserving async action feedback is a plausible implementation pattern but was not tested with real users, browsers or assistive technologies.
- Landbook's gallery listing metadata is observable (S5/O20); no showcase CTA visual hierarchy was inspected.

## CONTRADICTIONS

- GOV.UK start-link example includes a role/button treatment; pinned LinkButton defaults to anchor. Potentially different conventions; not adjudicated as a violation.
- Native disabled, interactive inactive and aria-disabled loading are different states with different consequences; CONTEXTUAL TRADEOFF.
- Live Primer documentation release cannot be assumed identical to pinned code; VERSION SPLIT / UNRESOLVED.

## COUNTEREXAMPLES

- Multiple independent workflow regions may each have their own principal action.
- Equally important alternatives may warrant balanced visual treatment instead of one dominant button.
- Where an action is truly unavailable with no explanatory pathway, the full Primer loading strategy may be inappropriate.
- A simple link to a new page is not the same as a button launching asynchronous work.

## VERSION LIMITS

- S1 WCAG 2.2 Recommendation dated 12 December 2024.
- S4 exact immutable SHA 7f5303d803986887187d86dcebaeda22a4dc6823; not substituted by current main.
- S2, S3, S5 live unpinned pages; recency/version cannot be guaranteed. No version-to-version behavior generalization.

## LICENSE / STORAGE LIMITS

- S1 public reference, W3C copyright and document-use rules; bounded summaries/observations.
- S2 OGL v3.0 content except otherwise stated; attributed summaries/observations only.
- S3 docs license UNKNOWN; reference only.
- S4 MIT license verified; code inspection only, nothing vendored.
- S5 license UNKNOWN, metadata only; NO screenshots or templates/assets.

## PATTERN CANDIDATES

- W02-P01 Contextual dominant primary action — CANDIDATE; bounded by grouping and independent task counterexamples; supported by S2/S3 observations.
- W02-P02 Focus-preserving asynchronous button feedback — CANDIDATE; documented by S3 and pinned S4 source, framed by WCAG accessibility criteria, not certified as conformant.

## ANTI-PATTERN CANDIDATES

- W02-A01 Competing dominant primary controls — CANDIDATE; observable structure + asserted potential next-step confusion + legitimate counter-contexts, supported by S2/S3. No “looks AI-generated” judgement.

## WHAT WCAG ACTUALLY REQUIRES

SC 2.1.1: keyboard-operable functionality with exception (A).
SC 2.4.7: visible keyboard focus indicator mode (AA).
SC 2.4.11: focused component not entirely obscured by author-created content (AA).
SC 2.5.8: minimum 24×24 CSS px pointer targets with specified exceptions (AA).
SC 4.1.2: programmatic name/role and relevant states/properties/value exposure (A).
SC 4.1.3: programmatic status-message identification without focus (AA).

WCAG does NOT require one visually dominant primary button per page; it does not select a design system. No Lucien application conformance claim is made.

## WHAT DESIGN SYSTEMS RECOMMEND

GOV.UK uses action-specific labels, default/secondary/warning differentiation, few competing main calls to action, and cautions about disabled controls. Primer recommends sparse primary/danger variants, loading spinner and focus continuity, and an inactive explanatory state. These are system-specific recommendations, NOT WCAG requirements.

## WHAT IMPLEMENTATION CODE DEMONSTRATES

At the exact SHA S4, Button renders ButtonBase with a button default and type button; LinkButton defaults to anchor; ButtonBase renders loading aria-disabled, suppressed click handler, retained label and AriaStatus; ButtonGroup activates arrow-key focus-zone only for toolbar role. Tests were read, NOT EXECUTED; no runtime or AT behavior proven.

## WHAT LANDBOOK-CLASS INSPIRATION CAN AND CANNOT SUPPORT

Landbook's listing identifies showcase names, categories, creators and gallery actions. We inspected no individual gallery screenshot or webpage. This is inspiration/metadata only; it cannot substantiate showcased action hierarchy, semantics, keyboard/accessibility, responsive behavior, source architecture, performance, effectiveness or production readiness.

## UNRESOLVED QUESTIONS

Primer doc/code version alignment; actual AT/browser behavior; user research on action competition; inactive/loading recovery paths; unverified page licenses; context-specific WCAG evaluation; no available application runtime. Details in UNRESOLVED.md.

## WORKER RECOMMENDATION

READY_FOR_MAINTAINER_REVIEW — review the five-source corpus, 20 observations, two bounded pattern candidates, one anti-pattern candidate, schema/link validation, and explicit limits. **No candidate promotion or K7.** Return decision authority to Maintainer.