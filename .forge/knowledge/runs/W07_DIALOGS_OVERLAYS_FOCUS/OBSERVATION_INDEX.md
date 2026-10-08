# W07 — STAGE B1 WCAG 2.2 OBSERVATION INDEX

> **Status: B1 CANDIDATE / READY_FOR_REVIEW ONLY.** This index is six raw K3 observations. It neither releases B2 nor proposes K4/K5/K6 patterns.

- Source family S1 only: W3C WCAG 2.2 W3C Recommendation, 12 December 2024.
- Registry source identity: `W02-S1` (reused, unchanged). No `W07-S1`.
- Stable dated version: https://www.w3.org/TR/2024/REC-WCAG22-20241212/
- Read/attribution date: 2026-10-08; `observed_at` 2026-10-08T15:58:21Z.
- Authority: `OFFICIAL_STANDARD / PRIMARY_NORMATIVE` limited to actual success-criterion scope.
- Evidence kind: `NORMATIVE_TEXT`; status: `OBSERVED`; no application, browser, keyboard, screen-reader or usability tests.

| Observation | WCAG criterion | Level | Primary domain | Exact dated-WCAG anchor |
|---|---|---|---|---|
| `W07-O01` | 2.1.1 Keyboard | A | `KEYBOARD_ACCESS` | [#keyboard](https://www.w3.org/TR/2024/REC-WCAG22-20241212/#keyboard) |
| `W07-O02` | 2.1.2 No Keyboard Trap | A | `KEYBOARD_ACCESS` | [#no-keyboard-trap](https://www.w3.org/TR/2024/REC-WCAG22-20241212/#no-keyboard-trap) |
| `W07-O03` | 2.4.3 Focus Order | A | `FOCUS_MANAGEMENT` | [#focus-order](https://www.w3.org/TR/2024/REC-WCAG22-20241212/#focus-order) |
| `W07-O04` | 2.4.7 Focus Visible | AA | `FOCUS_MANAGEMENT` | [#focus-visible](https://www.w3.org/TR/2024/REC-WCAG22-20241212/#focus-visible) |
| `W07-O05` | 2.4.11 Focus Not Obscured (Minimum) | AA | `FOCUS_MANAGEMENT` | [#focus-not-obscured-minimum](https://www.w3.org/TR/2024/REC-WCAG22-20241212/#focus-not-obscured-minimum) |
| `W07-O06` | 1.4.13 Content on Hover or Focus | AA | `OVERLAYS` | [#content-on-hover-or-focus](https://www.w3.org/TR/2024/REC-WCAG22-20241212/#content-on-hover-or-focus) |

## Conditions and non-upgrades
- O01: underlying function's path-dependent exception, not an exception for all pointer techniques; other input methods remain permitted.
- O02: keyboard exit remains possible; non-standard method requires instruction; no universal Escape key rule.
- O03: focus-order requirement applies when sequential navigation affects meaning or operation.
- O04: visible-focus **mode**, not the separate AAA focus-appearance numerical threshold.
- O05: AA not-entirely-obscured minimum, with two user-position/user-opened-content notes; **not** AAA 2.4.12.
- O06: dismissible/hoverable/persistent requirements only under the stated hover/focus trigger, with input-error, non-obscuring and user-agent exceptions.

## Source and rights
`W02-S1` has `PUBLIC_REFERENCE_ONLY` and `SUMMARIES_AND_OBSERVATIONS` storage policy. Records paraphrase the bounded normative conditions and cite precise anchors; no bulk W3C text, screenshots, or artifacts are stored.

## Batch control
- Records created: exactly six, `W07-O01` to `W07-O06`.
- No K4 comparison, K5 candidate, K6 review packet, K7 promotion or Stage B2 activity.
- Individual record `confidence: HIGH` refers to traceability to the identified normative source, **not** implementation correctness or conformance test results.
- B1 review gate remains independent Maintainer review of the committed exact SHA. Next downstream K3 batch **BLOCKED** without separate release.
