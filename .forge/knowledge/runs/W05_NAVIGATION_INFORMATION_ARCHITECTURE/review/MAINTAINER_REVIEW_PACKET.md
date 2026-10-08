# W05 MAINTAINER REVIEW PACKET — K6

## RUN ID
W05_NAVIGATION_INFORMATION_ARCHITECTURE

## EXACT LUCIEN SOURCE
Canonical main 5746b9412aa10333e7bc86ea54897f8be6b63267; exact starting worker branch forge/w05-navigation-information-architecture-intelligence@5cd7f152591ecbb4cd1b0a299446b3a0ff021b1d. GitHub issue #11. Final worker candidate SHA must be independently resolved from resulting branch/commit; this precommit packet does not fabricate it.

## SOURCE SET
Six families: WCAG 2.2 W02-S1; WAI Navigation Tutorials W05-S2; GOV.UK Service Navigation W05-S3; USWDS Header/Side/Breadcrumb W05-S4; Primer navigation guidelines W05-S5; pinned primer/react navigation implementation W05-S6.

## QUALIFICATION SUMMARY
1 reused source (same normative WCAG identity), 5 added navigation-specific identities. W05-S2 overlaps W03 WAI page-structure subpage but materially expands into menu semantics; W05-S3 differs from prior GOV button/layout; W05-S5 differs from Primer button/layout; W05-S6 covers distinct pinned navigation subtrees. Registry source qualification ≠ accepted guidance. GOV.UK header page direct retrieval failed; related official pattern covered role. Live docs unpinned.

## VOCABULARY SUMMARY
40 evidence-linked working terms in VOCABULARY.md, with hard distinctions: nav/action; hierarchy/history/transaction; breadcrumb/stepper; URL-backed related views/in-page panels; site nav/application commands; visual/programmatic current state.

## OBSERVATION COUNT
40, all OBSERVED: WCAG 10, WAI 5, GOV.UK 8, USWDS 6, Primer docs 5, pinned primer/react 6. Each individual JSON has precise evidence URL, source/version/class/limitations.

## NORMATIVE NAVIGATION REQUIREMENTS
WCAG 2.4.1 A Bypass Blocks; 2.4.2 A Page Titled; 2.4.3 A Focus Order; 2.4.4 A Link Purpose (In Context); 2.4.5 AA Multiple Ways with process-page exception; 2.4.6 AA Headings and Labels; 2.4.8 AAA Location; 3.2.3 AA Consistent Navigation with user-initiated exception; 3.2.4 AA Consistent Identification; 4.1.2 A Name Role Value. None mandates breadcrumbs, side nav, sitemap or fixed depth. O01–O10.

## WAI EXPLANATORY GUIDANCE
Ordinary site nav typically uses lists and links (O11); aria-current identifies current page in menu (O12); application menus add desktop-like menu roles/special arrow-key handling (O13); distinguish navigation landmarks by name (O14); heading structure aids page section navigation (O15). Tutorials are explanatory, not new WCAG criteria.

## DESIGN-SYSTEM NAVIGATION GUIDANCE
GOV.UK distinguishes site header/service links and linear task flow (O16/O17), current vs active section (O18), hierarchical breadcrumbs (O19), back link (O20), in-page tabs (O21), skip link (O22), mobile menu collapse (O23). USWDS basic/extended header, 1–3-level side nav convention, current orientation, hierarchy-tested breadth/depth, breadcrumb direct-entry and mobile variant (O24–O29). Primer location/current-context NavList, breadcrumb ancestry, URL-backed nonsequential UnderlineNav and accessible overflow expectations (O30–O34).

## PINNED IMPLEMENTATION FINDINGS
Exact primer/react 7f5303d803986887187d86dcebaeda22a4dc6823. NavList nav landmark and aria-labelled-by handling (O35), nested current/expanded state (O36); UnderlineNav named navigation/current one-item invariant and overflow menu (O37); item focusability change when clipped (O38); Breadcrumbs ordered list, menu overflow and labelled control (O39); nav test-file intent (O40). **SOURCE INSPECTED; TESTS NOT RUN.** No claim of runtime, keyboard or AT conformance.

## GLOBAL / LOCAL / CONTEXTUAL NAVIGATION FINDINGS
Global major destinations differ from service sections and local/peer views. Scope-specific labels and task role matter (O16/O24/O26/O31/O33).

## LOCATION / ORIENTATION FINDINGS
Titles, headings, visual state and programmatic current state are separate cues; WCAG 2.4.8 Location is AAA. Use appropriately named nav landmarks; no single component guarantees comprehension (O02/O06/O07/O12/O14/O18/O35–O37).

## HIERARCHY FINDINGS
Parent/child/sibling and ancestry differ from linear task sequence. USWDS side-nav 1–3 levels is local product preference and cannot become a universal depth law (O26/O27/O28).

## BREADCRUMB FINDINGS
GOV.UK trail may end at parent (O19), USWDS and Primer may include current page (O29/O32). They convey hierarchy, not visited history or wizard steps. Flat or redundant sites may omit them.

## TABS / UNDERLINE NAV FINDINGS
GOV.UK Tabs reveals in-page sections (O21); Primer UnderlineNav links dedicated URL-backed nonsequential views (O33/O37), distinct from steppers. Neither choice is automatic or universal.

## MENU SEMANTICS FINDINGS
Ordinary site nav links/list (O11/O14) do not automatically satisfy application menubar/menuitem behavior (O13). A visual dropdown is not sufficient reason for ARIA menu roles.

## LABELING FINDINGS
WCAG link-purpose-in-context and headings/labels scopes (O04/O06); WAI region labels (O14); USWDS current-page and short meaningful labels/test-depth advice (O27); Primer descriptive link and counter accessibility guidance (O34).

## RESPONSIVE NAVIGATION FINDINGS
Use accepted W04-P01/P02/P03 and W04-A01/A02 as boundaries; necessary routes remain reachable, meaningful focus/source order preserved where relevant. GOV collapsed service menu (O23) and pinned Primer overflow (O37–O39) establish options, not runtime results.

## MULTIPLE-WAYS FINDINGS
WCAG SC 2.4.5 AA is a set-of-pages finding requirement with a process-step/result exception (O05), not a fixed number/type of navigation widgets.

## FAILURE-MODE HYPOTHESES
Twelve named cases documented with observed structure, harm, direct and inferred support, counter-context and candidate decision (FAILURE_MODE_ANALYSIS.md).

### SUPPORTED
Bounded W05-A01 breadcrumb relationship confusion; W05-A02 improper application-menubar roles for site nav. Both CANDIDATE; harm to real users is inferred, not measured.

### WEAK / INSUFFICIENT
Depth without cues, duplicative navigation, org-chart navigation, active-only-by-color in untested product, location ambiguity without actual context and overall navigation/action ambiguity are hypothesis-level or addressed by more specific candidate patterns.

### REJECTED / MISFRAMED
Every deep navigation is bad; all navigation must be global; every page needs breadcrumbs; breadcrumbs equal browser back/history; URL tabs equal in-place tab panels; all dropdowns are application menubars; every site must have three discovery mechanisms; all visible current states guarantee programmatic state.

## CONTRADICTIONS
GOV.UK in-page tabs vs Primer URL links: contextual model split. GOV breadcrumb parent-only vs USWDS/Primer current-inclusive: implementation variant. USWDS depth count vs other sites: local guidance only. WAI ordinary nav vs desktop command menu: semantic/keyboard model split. WCAG AAA Location versus broader usability advice: authority split.

## COUNTEREXAMPLES
Flat page where breadcrumb is redundant; lawful history list named as history; stepper for transactional sequence; deep expert site with robust discovery; application editor with authentic menubar and keys; global plus labelled local navigation; hidden mobile routes restored via accessible menu.

## VERSION LIMITS
WCAG 2.2 Recommendation Dec 2024. WAI/GOV.UK/USWDS/Primer live doc pages unpinned; USWDS banner v3.13.0 not an exact docs SHA. Primer implementation immutably pinned 7f5303d803986887187d86dcebaeda22a4dc6823. No cross-version equivalence assumed.

## LICENSE / STORAGE LIMITS
W3C document use/public reference; GOV OGL 3.0 except exceptions; USWDS and Primer docs UNKNOWN reference only; pinned primer/react MIT. Summaries and structured records only; no source/files/screenshots vendored.

## PATTERN CANDIDATES
W05-P01 Current-location multi-cue orientation — MEDIUM / CANDIDATE.
W05-P02 Relationship-matched navigation mechanisms — MEDIUM / CANDIDATE.
W05-P03 URL-backed related-view navigation with semantic separation — MEDIUM / CANDIDATE.

## ANTI-PATTERN CANDIDATES
W05-A01 Breadcrumb relationship confusion — MEDIUM / CANDIDATE.
W05-A02 Ordinary site navigation miscast as application menubar — MEDIUM / CANDIDATE.

## WHAT MUST NOT BE GENERALIZED
No universal sitemap, depth ceiling, breadcrumb obligation, default app-menu roles, prescribed router, universal active-state scheme or measured IA success. WCAG AAA not AA. Third-party component examples are not normative standards. Pinned code/test intent not runtime proof.

## PRIOR KNOWLEDGE INTEGRITY
W02-P01/A01 ACCEPTED; W02-P02 CANDIDATE; W03-P01/P02/P03 ACCEPTED and A01 CANDIDATE; W04-P01/P02/P03/A01/A02 ACCEPTED. W05 work does not modify these records; independent byte-integrity check required in worker validation.

## UNRESOLVED QUESTIONS
Real user tasks, IA mapping, actual routes, labels, nav-depth usability tests, keyboard/AT/browser behavior, GOV header direct access, documentation version/lawful reuse and mobile overflow interaction. See UNRESOLVED.md.

## WORKER RECOMMENDATION
READY_FOR_MAINTAINER_REVIEW for independent K7 disposition. No worker acceptance, W06, application code or main merge.
