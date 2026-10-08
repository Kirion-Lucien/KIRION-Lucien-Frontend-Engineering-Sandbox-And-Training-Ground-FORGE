# W05 CROSS-SOURCE NAVIGATION COMPARISON (K4)

## A. Navigation versus action

Links go to destinations, including URL-backed related views (W05-O11/O33/O38). A local disclosure reveals/hides subordinate content (O36). Buttons may run application commands, such as a menu action; WAI application menus with menubar/menu/menuitem roles carry specialized desktop-style keyboard expectations (O13). A horizontal visual strip alone does not justify ARIA tabs, menubar or menuitem roles. The specific target action model remains unknown.

## B. Global/local/contextual navigation

GOV.UK separates government site-wide identity/utility header from service-level destinations (O16/O18). USWDS places global main sections in a header and local sub-navigation in a side rail (O24–O27). Primer NavList represents current object/section context, while UnderlineNav represents related sibling destination views (O30/O31/O33). Utility navigation can coexist with either; scope naming matters (WAI O14).

## C. Current location and orientation

WCAG titles (O02), headings (O06), AAA Location (O07) and predictable repeated navigation (O08) provide separate normative dimensions. WAI describes aria-current=page and named navigation landmarks (O12/O14). GOV.UK distinguishes current page from active containing group (O18); USWDS highlights current side destination (O27); pinned Primer controls render aria-current attributes and active/overflow semantics (O35–O39). Visual color-only state is insufficient as the only accessible signifier; code markup alone does not prove live AT output.

## D. Hierarchy

Breadcrumbs communicate ancestry; side navigation exposes local parent/child/sibling routes; UnderlineNav primarily exposes related URL-backed views; service header communicates service bounds. A hierarchy is not visit history or ordered task stages (GOV O17/O19/O20; USWDS O26/O28; Primer O31/O32/O33). More levels may demand context-appropriate navigation rather than an arbitrary depth rule; USWDS 1–3 side-nav-level preference is system guidance only (O26/O27).

## E. Multiple ways and discoverability

WCAG 2.4.5 Level AA (O05) concerns a *set of pages*, and explicitly excludes pages that are a result of or step in a process. It requires more than one way to locate the other in-scope pages, **not** three fixed navigation widgets per page. Search, navigation hierarchy and contextual links are potential choices when appropriate. No actual W05 product pages tested.

## F. Breadcrumbs

GOV.UK recommends breadcrumbs for multilevel websites but says they are inappropriate for flat sites or transaction progress; its breadcrumb examples stop at the parent (O19). USWDS examples include a current-page item and indicate possible redundant breadcrumbs with side navigation (O28/O29). Primer describes ancestor links and current page (O32). These are CONTEXTUAL VARIANTS, not a single mandated breadcrumb ending. A browser back-stack or wizard stepper records a different relationship.

## G. Tabs / UnderlineNav

GOV.UK Tabs groups related in-page information and explicitly discourages using that component for page navigation, sequential reading and difficult cross-tab comparison (O21). Primer UnderlineNav guidelines favor discrete, URL-addressable, non-sequential views (O33), separate from its UnderlinePanels/in-place content model. Pinned UnderlineNav renders link items and current marker (O37/O38). Labeling both “tabs” does not make them the same interaction/semantic category.

## H. Menu semantics

WAI regular site nav can use lists of links and labelled nav landmarks (O11/O14). Application menus require specialized roles and scripting for arrow-key behaviors (O13). Primer UnderlineNav uses an ActionMenu for its *overflow* representation (O37); this does not transform every site nav element into a menu-role interface. Current implementation behavior not certified.

## I. Labels

WCAG 2.4.4 Level A link purpose may be determined in programmatic context (O04), and 2.4.6 Level AA demands descriptive headings/labels (O06). USWDS recommends short link labels derived from page titles and usability testing of breadth/depth (O27). Primer docs support descriptive link labels and accessible counters (O34). GOV.UK service naming distinguishes page/service scopes (O16/O18). Neither code nor references measures actual end-user label recognition.

## J. Responsive preservation

Accepted W04-P01/P02/P03 and W04-A01/A02 govern recoverable necessary routes, meaning-bearing source/focus order and task-justified overflow. GOV.UK Service navigation provides a mobile collapse mechanism (O23); WAI describes consistent menu wording/order across displays (O12); pinned UnderlineNav moves overflow links into accessible alternate paths in code (O37/O38); Breadcrumbs has configurable responsive menu variants (O39). These are source mechanics/guidelines only; real keyboard and screen-reader access remain UNTESTED.

## Contradictions and bounded resolutions

1. GOV.UK in-place Tabs vs Primer URL-backed UnderlineNav: **TERM / COMPONENT SPLIT**, not contradiction.
2. GOV.UK breadcrumb ends at parent vs USWDS/Primer current item: **SYSTEM VARIANT**, either can express hierarchy.
3. Navigation links vs transaction task lists: **RELATIONSHIP DIFFERENCE**, not interchangeable.
4. USWDS side-nav 1–3 levels vs complex real sites: **PRODUCT LIMIT**, not universal depth.
5. WAI ordinary site nav list vs ARIA application menubar: **ROLE/BEHAVIOR DISTINCTION**, not visual-style preference.
6. WCAG Level AAA location vs WAI/Primer recommended location cues: **AUTHORITY/SCOPE**, no conversion from AAA to AA.
7. Responsive hiding vs accepted W04 recoverability: **USAGE CHECK**, not proof that every disclosure is safe.

No majority vote; context and normative scope govern. K5 records remain candidates only.
