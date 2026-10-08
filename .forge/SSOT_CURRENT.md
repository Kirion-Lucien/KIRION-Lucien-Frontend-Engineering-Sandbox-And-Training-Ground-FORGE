# SSOT CURRENT

## Repository

`Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE`

## Program

`W05 — NAVIGATION & INFORMATION ARCHITECTURE INTELLIGENCE`

## Status

`ACCEPTED / NAVIGATION & IA KNOWLEDGE ACTIVE`

W00 through W04 remain accepted and active as governing prior authority.

W05 Maintainer acceptance is recorded in GitHub issue #11 and `.forge/ACCEPTANCE.md`.

## Canonical source before W05

`main@5746b9412aa10333e7bc86ea54897f8be6b63267`

## Exact reviewed W05 worker candidate

`forge/w05-navigation-information-architecture-intelligence@cebe0abd78e8806deef8af7f3f94ed0a17c44416`

## Accepted W05 corpus

Six logical source families:

1. W3C WCAG 2.2
2. W3C WAI menus / page-structure navigation guidance
3. GOV.UK navigation / service-navigation family
4. U.S. Web Design System navigation family
5. GitHub Primer navigation guidance
6. `primer/react@7f5303d803986887187d86dcebaeda22a4dc6823` navigation implementation

WCAG reused the existing `W02-S1` source identity.

Five W05-specific qualified source identities were appended:

```text
W05-S2
W05-S3
W05-S4
W05-S5
W05-S6
```

Registry qualification remains distinct from claim acceptance.

## Accepted W05 vocabulary

W05 establishes evidence-linked working terminology for information architecture, navigation scope, hierarchy/ancestry, current location, breadcrumbs, side/header/tabbed navigation, URL-backed views, tab panels, menus/menubars, wayfinding, multiple ways, routes, linear processes, hierarchical relationships, and task flow.

Working terminology is analytical guidance, not a universal sitemap or route architecture.

## Accepted bounded patterns

### W05-P01 — Current-location multi-cue orientation

`ACCEPTED / MEDIUM CONFIDENCE`

Where repeated or nested navigation makes current location meaningful, coherent location cues should be available as appropriate.

This does not mandate breadcrumbs or every possible cue, and WCAG 2.4.8 Location remains AAA.

### W05-P02 — Relationship-matched navigation mechanisms

`ACCEPTED / MEDIUM CONFIDENCE`

Navigation mechanisms should reflect the actual relationship being represented: global scope, local section, hierarchy/ancestry, related peer destination, or sequential task flow.

No universal sitemap, component set, or hierarchy depth is accepted.

### W05-P03 — URL-backed related-view navigation with semantic separation

`ACCEPTED / MEDIUM CONFIDENCE`

Independently addressable non-sequential peer views may use link/navigation semantics with current-state indication, while in-place tab panels and sequential workflow stages remain distinct interaction models.

No universal URL requirement, router, or component library is selected.

## Accepted bounded anti-patterns

### W05-A01 — Breadcrumb relationship confusion

`ACCEPTED / MEDIUM CONFIDENCE`

Hierarchical breadcrumbs should not represent visit history or sequential transaction stages as though they were ancestors.

### W05-A02 — Ordinary site navigation miscast as application menubar

`ACCEPTED / MEDIUM CONFIDENCE`

Ordinary destination links should not receive desktop-application menu roles solely because they visually resemble a dropdown/menu without the corresponding interaction and keyboard model.

## Prior deferred knowledge preserved

```text
W02-P02 — CANDIDATE / DEFERRED
W03-A01 — CANDIDATE / DEFERRED
```

## Navigation / IA law

No universal:

- sitemap;
- hierarchy-depth ceiling;
- breadcrumb requirement;
- URL-backed-tab requirement;
- application-menu-role default;
- router/framework;
- product taxonomy without user/task evidence.

## Application implementation authority

`BLOCKED`

No frontend application Code Writer lane exists.

## Current work gate

`W06 — NEXT KNOWLEDGE LANE`

State:

`INPUT REQUIRED / REVIEW`

W06 is not yet defined or authorized.

## Active handoff

NONE.

The completed W05 handoff is historical evidence and is not executable authority.

## Next gate

Human / Maintainer selects the next bounded knowledge objective.

No W06 acquisition or frontend implementation begins until an exact handoff is issued.
