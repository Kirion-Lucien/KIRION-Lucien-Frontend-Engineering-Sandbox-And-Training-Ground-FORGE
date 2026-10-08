# SSOT CURRENT

## Repository

`Kirion-Lucien/KIRION-Lucien-Frontend-Engineering-Sandbox-And-Training-Ground-FORGE`

## Program

`W04 — RESPONSIVE LAYOUT & MOBILE ADAPTATION INTELLIGENCE`

## Status

`ACCEPTED / RESPONSIVE KNOWLEDGE ACTIVE`

W00 through W03 remain accepted and active as governing prior authority.

W04 Maintainer acceptance is recorded in GitHub issue #9 and `.forge/ACCEPTANCE.md`.

## Canonical source before W04

`main@c9acd923b11d8695ab5ba41569599fc9165f5b97`

## Exact reviewed W04 worker candidate

`forge/w04-responsive-mobile-adaptation-intelligence@9aef7979d2c247f555e6b89d481270a4de19d4a1`

## Accepted W04 corpus

Six logical source families:

1. W3C WCAG 2.2
2. W3C WAI Mobile Accessibility / responsive guidance
3. GOV.UK Layout / Type Scale
4. IBM Carbon 2x Grid / responsive guidance
5. GitHub Primer responsive foundations / PageLayout guidance
6. `primer/react@7f5303d803986887187d86dcebaeda22a4dc6823` responsive/PageLayout implementation

The source registry was reused without mutation.

## Accepted W04 vocabulary

W04 establishes evidence-linked working terminology for responsive/adaptive/fluid layout, viewport/range/breakpoint distinctions, reflow, stacking, wrapping, collapse, disclosure, overflow, horizontal scrolling, intrinsically two-dimensional content, source/visual/focus order, content priority, responsive density, target size, orientation, pane relocation, and progressive reduction.

These are analytical terms, not universal breakpoint or device-class laws.

## Accepted bounded patterns

### W04-P01 — Recoverable responsive reduction

`ACCEPTED / MEDIUM CONFIDENCE`

Task-required content/actions remain reachable when constrained layouts reduce concurrent regions.

### W04-P02 — Meaningful source and focus order through responsive relocation

`ACCEPTED / MEDIUM CONFIDENCE`

Meaning-bearing source/reading and keyboard-focus sequences must remain meaningful and operable where applicable when visual layout changes.

### W04-P03 — Task-justified horizontal overflow

`ACCEPTED / MEDIUM CONFIDENCE`

Horizontal navigation may be appropriate for genuinely two-dimensional task content; ordinary linear content should reflow where possible.

## Accepted bounded anti-patterns

### W04-A01 — Unrecoverable task-critical control disappearance

`ACCEPTED / MEDIUM CONFIDENCE`

Removing the only required action/navigation path for a task without equivalent access is an accepted responsive anti-pattern.

### W04-A02 — Unjustified horizontal overflow for ordinary content

`ACCEPTED / MEDIUM CONFIDENCE`

Preserving desktop-width geometry for ordinary reflowable content, causing unnecessary two-dimensional navigation under applicable conditions, is an accepted anti-pattern.

## Prior deferred knowledge preserved

```text
W02-P02 — CANDIDATE / DEFERRED
W03-A01 — CANDIDATE / DEFERRED
```

## Responsive law

No universal:

- phone/tablet/desktop breakpoint table;
- one-column mobile mandate;
- ban on hiding/collapse/reordering;
- ban on horizontal scrolling;
- ban on high-density professional interfaces;
- claim of WCAG conformance from source inspection.

## Application implementation authority

`BLOCKED`

No frontend application Code Writer lane exists.

## Current work gate

`W05 — NEXT KNOWLEDGE LANE`

State:

`INPUT REQUIRED / REVIEW`

W05 is not yet defined or authorized.

## Active handoff

NONE.

The completed W04 handoff is historical evidence and is not executable authority.

## Next gate

Human / Maintainer selects the next bounded knowledge objective.

No W05 acquisition or frontend implementation begins until an exact handoff is issued.
