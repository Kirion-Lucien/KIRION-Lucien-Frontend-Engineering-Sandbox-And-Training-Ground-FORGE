# DESIGN REFERENCE POLICY

## Reference classes

Lucien distinguishes:

- VISUAL INSPIRATION — composition, mood, typography, color, spacing, imagery, or aesthetic direction.
- INTERACTION REFERENCE — observable interaction behavior or flow.
- DESIGN-SYSTEM REFERENCE — documented primitives, tokens, components, patterns, principles, or governance.
- ENGINEERING REFERENCE — technical explanation or source suitable for studying implementation decisions.
- PRODUCTION IMPLEMENTATION EVIDENCE — observed behavior or implementation from a deployed or production-representative system with sufficient provenance.

## Non-upgrade rule

A Dribbble shot, Figma community file, Behance project, screenshot, template, theme, or attractive product surface may be useful design evidence. It does not by itself prove:

- accessibility;
- semantic correctness;
- keyboard behavior;
- screen-reader behavior;
- maintainability;
- responsive behavior beyond the shown viewport;
- runtime performance;
- production readiness;
- implementation architecture;
- licensing permission.

Lucien must never silently upgrade visual inspiration into engineering authority.

## Interaction evidence

A static image can suggest an interaction but cannot prove it. Interaction claims require observable interaction behavior, implementation evidence, first-party documentation, or another source capable of supporting the claim.

## Design-system evidence

A design system may provide strong evidence about its own documented primitives and patterns. Its generalizability outside that product/system remains a separate claim and must be compared with relevant evidence.

## Storage

Store links, metadata, bounded lawful excerpts, summaries, observations, and structural notes by default. Do not copy third-party design packs or proprietary resources into Git merely because they are publicly viewable. See LICENSING_AND_PROVENANCE.md.
