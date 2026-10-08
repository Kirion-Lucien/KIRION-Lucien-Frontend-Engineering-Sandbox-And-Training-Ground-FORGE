# W05 INFORMATION ARCHITECTURE / HIERARCHY ANALYSIS

## Breadth and depth

Breadth means count of options at a given level; depth counts ancestor/descendant transitions. USWDS basic versus extended header and local side-nav 1–3-level convention provide contextual examples (O24/O26/O27), not a universal upper bound. Complexity tradeoff requires target IA/tree usability research (NOT RUN).

## User-task language vs organizational structure

USWDS asks for short, clear destination labels and tests when nested options become difficult to find (O27); Primer emphasizes clarity and orientation (O30). A navigation tree based only on internal departmental structure may diverge from user goals. This harm is INFERRED, not measured in W05; no independent organizational IA study was performed.

## Parent / child / sibling

- Parent is the containing higher-level destination.
- Child is nested within it.
- Siblings share a local parent or related peer destination context.
- Breadcrumbs can expose parent/ancestors (GOV O19, Primer O32).
- Side navigation exposes nearby section children (USWDS O26, Primer O31).
- URL-backed UnderlineNav expresses peer destination views, not necessarily strict ancestor-child structure (Primer O33).

## Ancestry, current section and cross-links

GOV.UK Service Navigation distinguishes current page from active containing group (O18). WAI recommends aria-current in navigation when appropriate (O12). Cross-links to related content can create discovery pathways beyond direct ancestry; cross-links do not automatically redefine the hierarchy. WCAG 2.4.5 provides a bounded multi-way requirement (O05).

## Hierarchical vs sequential relationships

Breadcrumb trails describe information organization (O19/O28/O32). Back links can support a previous process page (O20), and a task list can express prescribed transaction steps (O17). A history trail is neither route ancestry nor wizard progress.

## Duplicate navigation

USWDS warns that an existing horizontal+vertical nav system may be redundant (O26/O28). Two different-role nav regions may still be useful (global vs local). WAI advises naming multiple nav landmarks (O14). Redundancy cannot be judged from a count of nav elements alone.

## Discoverability

WCAG 2.4.5 AA mandates multiple locating paths within a set except process pages (O05). GOV service navigation supports reusable multiple tasks (O17); Primer navigation cues communicate where users are and where they can go (O30). No user IA/tree testing means no empirical completion claims.

## Site vs service boundaries

GOV.UK national site header vs named Service navigation (O16) is a documented government-specific distinction. USWDS header communicates whole-site main areas, side nav communicates a section (O24–O26). Other product ecosystems can have different scopes. Label regions according to actual information ownership.

## URL-backed structure

Primer UnderlineNav encourages distinct related URLs (O33), while GOV.UK Tabs toggles sections in-place (O21). Neither requires adopting a specific router; dedicated URLs and panel visibility are different semantic models.

## Non-generalization

No universal depth count, one-size-fits-all menu pattern, sitemap shape, department-to-taxonomy equivalence, or breadcrumb count was established. Test actual user language and IA when a product context exists.
