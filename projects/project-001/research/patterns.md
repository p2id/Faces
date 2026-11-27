PROJECT_ID: project-001
DATE: 2026-11-27
CYCLE_LOCK: 01

DOMINANT: clear hierarchy; neutral surfaces; compact cards; persistent primary action; progressive disclosure; consistent spacing; responsive stacking.
EMERGING: contextual action bars; inline validation; density controls; adaptive navigation; semantic status labels; reduced-motion modes.
DEPRECATED: decorative gradients; hover-only information; modal-heavy flows; low-contrast text; color-only status; unexplained icon controls.
OUTLIER: timeline-first navigation; split-pane inspection; monochrome status systems; oversized section numerals; asymmetrical editorial modules.

VISUAL_DNA: neutral foundation; one restrained accent; high-contrast text; 8px spacing base; 12px radius; 1px borders; low-elevation surfaces.
INTERACTIONAL_DNA: one primary action per view; predictable focus order; reversible changes; inline feedback; progressive disclosure; keyboard-complete controls.
ACCESSIBILITY_DNA: WCAG AA contrast target; visible focus; semantic landmarks; descriptive labels; 44px minimum targets; reduced-motion support; no color-only meaning.
RESPONSIVE_DNA: 12-column wide layout; 4-column compact layout; fluid type; content-driven breakpoints; stacked cards below medium width; primary action remains reachable.

CANDIDATE_DOMAINS
Planning workspace: organizes objectives, phases, dependencies, and progress.
Knowledge library: supports searchable, categorized content and reading states.
Monitoring console: presents status, trends, thresholds, and exceptions.
Configuration studio: guides setup, preferences, rules, and previews.
Service catalog: supports browsing, comparison, detail, and selection.
Analysis dashboard: presents metrics, comparisons, annotations, and summaries.

WEIGHTED_MATRIX
Weights: clarity 25; accessibility 20; responsive fit 20; reuse 20; distinctiveness 15.
Planning workspace: 23+19+19+19+12=92
Knowledge library: 22+19+18+19+11=89
Monitoring console: 21+17+19+17+12=86
Configuration studio: 22+18+18+18+12=88
Service catalog: 21+18+18+17+13=87
Analysis dashboard: 21+17+18+18+13=87

SELECTED_DOMAIN: Planning workspace.
RATIONALE: Highest composite score with strong hierarchy, broad component reuse, responsive resilience, and neutral applicability.
CYCLE_LOCK: Preserve the selected domain, extracted DNA, accessibility baseline, and responsive rules for this cycle.
FALLBACK_RULE: If hierarchy, contrast, focus behavior, or compact layout fails validation, use Knowledge library while retaining the same DNA and accessibility baseline.