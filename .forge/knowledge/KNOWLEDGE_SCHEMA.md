# FRONTEND KNOWLEDGE DOMAIN MODEL

## Purpose

Lucien uses a stable, stack-neutral vocabulary so evidence can be compared without prematurely choosing a framework, language, component library, state library, build tool, or deployment platform.

## Domain vocabulary

### Structure and presentation

INFORMATION_ARCHITECTURE
NAVIGATION
LAYOUT
RESPONSIVE_DESIGN
TYPOGRAPHY
SPACING
COLOR
VISUAL_HIERARCHY
CONTENT_DESIGN

### Components and interaction

COMPONENT_ARCHITECTURE
DESIGN_SYSTEMS
FORM_DESIGN
DATA_DISPLAY
TABLES
SEARCH
FILTERING
EMPTY_STATES
LOADING_STATES
ERROR_STATES
FEEDBACK
MODALS
OVERLAYS
MOTION
INTERACTION

### Semantics and accessibility

SEMANTIC_HTML
KEYBOARD_ACCESS
FOCUS_MANAGEMENT
SCREEN_READER_BEHAVIOR
COLOR_CONTRAST
ACCESSIBILITY

### Runtime and data concerns

RENDERING
STATE_MANAGEMENT
SERVER_STATE
FORM_STATE
VALIDATION
DATA_FETCHING
API_BOUNDARIES
ERROR_HANDLING
CACHING

### Performance

PERFORMANCE
BUNDLE_STRATEGY
IMAGE_STRATEGY
FONT_STRATEGY
CORE_WEB_VITALS

### Quality and sustainability

TESTING
OBSERVABILITY
SECURITY
MAINTAINABILITY
CODE_ORGANIZATION

## Classification rules

1. Classify evidence by the problem actually observed, not by the technology name that happened to implement it.
2. A record may carry one primary domain and additional domain tags when evidence genuinely crosses concerns.
3. Do not force evidence into a wrong domain. If no domain fits, record UNRESOLVED and propose a vocabulary extension for review.
4. Domain membership does not imply authority, correctness, generality, or acceptance.
5. Framework-specific evidence remains version-bound implementation evidence unless broader authority supports generalization.

## Knowledge states

Lucien distinguishes source metadata, observations, pattern candidates, anti-pattern candidates, accepted knowledge, rejected knowledge, deprecated knowledge, and unresolved questions.

Accepted knowledge must remain traceable to source IDs and observation IDs. Summarization must not erase provenance, version context, counterexamples, or licensing constraints.

## No context-free best practice law

Recurring fashion is not universal doctrine. “Always”, “never”, “professional apps”, and “industry standard” claims require applicable accepted authority and explicit context. Otherwise record observed context, evidence, tradeoffs, and uncertainty.
