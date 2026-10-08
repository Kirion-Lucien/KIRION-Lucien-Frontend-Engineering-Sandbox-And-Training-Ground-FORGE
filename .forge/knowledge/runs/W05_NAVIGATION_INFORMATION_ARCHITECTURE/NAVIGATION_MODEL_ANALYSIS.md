# W05 NAVIGATION MODEL ANALYSIS

All decisions below are **working comparative analysis**, not a proposed universal product architecture. Each evidence reference maps to a W05 OBSERVED JSON record and official location.

## 1. Global navigation
Communicates entry into major site/product areas, brand/scope and discoverable principal destinations (GOV O16; USWDS O24/O25). It need not enumerate every deep descendant.

## 2. Local navigation
Communicates immediate section/object neighbors and relevant children, often through a NavList/side rail (USWDS O26/O27; Primer O31).

## 3. When side navigation is useful
A section has enough nested local destinations to benefit from persistent hierarchy/current-section context. USWDS prefers 1–3 levels for its component and cautions about already duplicated rails (O26/O27). This is not a universal maximum.

## 4. When breadcrumbs are useful
Multi-level ancestry, especially direct entry into an interior page where parent location is not obvious (GOV O19; USWDS O28; Primer O32).

## 5. When breadcrumbs should be omitted
Flat structures, home/landing contexts, transaction steps mistaken for hierarchy, or environments with already adequate location signals (GOV O19; USWDS O28). Decision depends on user need.

## 6. URL-backed UnderlineNav
Choose in the Primer product model for related non-sequential, independently addressable views with a dedicated URL (Primer O33; pinned link O37). No routing framework selected.

## 7. In-place tab panels
Choose when sections are related *within the same page* and one section can be read at a time without necessary cross-tab comparison, per GOV.UK Tabs (O21). It is a disclosure/panel switch, not required separate URL navigation. Avoid tabs for mandatory linear reading.

## 8. Back link versus hierarchy
GOV.UK Back link is task-journey flow support (O20). A hierarchy parent/breadcrumb differs from the previously visited or transaction-step page. Do not infer browser history traversal from the word “Back.”

## 9. When a basic header suffices
Modest primary breadth/shallow structure; USWDS basic variant (O24) is one reference, not all web requirements.

## 10. When complexity needs another mechanism
USWDS extended header supports additional sections/utilities; section subnav and breadcrumb can supply location (O24/O26/O28). Test whether added navigation is redundant; no fixed threshold established beyond product-specific examples.

## 11. Communicating current location
Use descriptive page title/heading, location-aware nav labels, visual selected/current indication and appropriate programmatic current state (WCAG O02/O06/O07; WAI O12/O14; GOV O18; Primer O31/O35–O39). No one cue is a universal substitute for real task testing.

## 12. Width overflow
GOV service nav supports mobile collapse (O23); pinned UnderlineNav transfers clipped links into an overflow menu while retaining current semantics (O37/O38); breadcrumbs can wrap/overflow by variant (O39). Overflow interaction safety remains unproven without runtime verification.

## 13. Responsive critical routes
Follow ACCEPTED W04-P01/W04-P02 and W04-A01: relocating/collapsing navigation must preserve reachable required destinations and meaningful reading/focus routes. Changing visible geometry is not permission to delete task paths. No browser test performed.

## 14. Site menu versus application command menu
A normal site menu is usually a list of links in a nav landmark (WAI O11/O14). Desktop-style application menus add menubar/menuitem roles, arrow-key conventions and scripted command behavior (WAI O13). Similar visual dropdowns do not imply equivalent roles.

## 15. Multiple navigation landmarks
Provide distinguishable purpose labels for multiple nav regions (WAI O14); pinned NavList forwards aria-label or heading-based aria-labelledby (O35). Labels should reflect actual scope, not just “navigation.”

## 16. Visual highlight alone
A highlight does not establish accessible current page, heading/title quality, ancestry, programmatic state, keyboard route or discoverability. GOV current/active semantics (O18), WAI aria-current (O12), and pinned source forwarding (O35–O37) are observable *mechanisms*, not end-to-end conformance.

## Decision matrix, not implementation choice

Classify a requirement first as: global/site route, local section route, hierarchical ancestor, URL-backed peer view, in-page disclosure, linear process step, or command. Then evaluate language, programmatic role, current-state signal, redundant paths and responsive reachability. This is K5 analysis for Maintainer review, not application IA adoption.
