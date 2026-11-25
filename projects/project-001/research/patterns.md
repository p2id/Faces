Project ID: project-001 | Date: 2026-11-25

DOMINANT PATTERNS
- Structured workspace with stable navigation, clear title, summary status, focused content, and persistent primary action.
- Neutral surfaces, one controlled accent, restrained borders, moderate density, and consistent spacing.
- Progressive disclosure through summaries, expandable details, inline validation, and reversible actions.
- Responsive cards, lists, and tables that preserve hierarchy across viewport sizes.

EMERGING PATTERNS
- Command-style search for navigation, filtering, and quick access.
- Preview-before-commit with visible change summaries.
- Semantic status tokens combining color, icon, and text.
- Content-driven layout adaptation using flexible containers.

DEPRECATED PATTERNS
- Decorative gradients without functional purpose.
- Deep navigation trees, modal stacking, and hover-only controls.
- Color-only status communication.
- Persistent animation, autoplay content, and ornamental illustration.

OUTLIER PATTERNS
- Split-pane comparison for review-heavy contexts.
- Timeline or dependency views where sequence is primary.
- Monochrome interfaces with a single high-salience exception state.
- Keyboard-first command surfaces for expert operation.

EXTRACTED DNA
Visual: neutral surfaces, 8px spacing base, 1px dividers, 10–14px radius, one accent family, high-contrast text, restrained elevation.
Interactional: direct manipulation, predictable focus order, explicit confirmation for consequential actions, undo or cancel where practical, and visible empty, loading, and error states.
Accessibility: WCAG 2.2 AA target, 4.5:1 body-text contrast, 3:1 large-text and graphical contrast, 44px minimum touch target, keyboard parity, reduced-motion support, semantic labels, and no color-only meaning.
Responsive: mobile-first priority, single-column layout below 720px, two-column composition from 960px, capped reading width, stacked replacement for wide tables, and persistent primary action.

CANDIDATE PRODUCT DOMAINS
- Operational planning: organizes time-bound items, priorities, dependencies, and progress.
- Resource inventory: tracks categorized records, availability, condition, and movement.
- Knowledge reference: structures indexed content, summaries, relationships, and revisions.
- Financial overview: presents categorized values, trends, thresholds, and period comparisons.
- Quality monitoring: surfaces measurements, deviations, thresholds, and review states.
- Configuration catalog: presents reusable settings, versions, validation, and publication states.

WEIGHTED SCORING MATRIX
Weights: clarity 25, reuse 25, responsive fit 20, accessibility fit 15, distinction 15. Scores 1–5; total = weighted score / 5.
Domain                    Clarity Reuse Responsive Access Distinction Total
Operational planning          5      5       5         5        4       4.85
Resource inventory            5      5       4         5        3       4.55
Knowledge reference           4      5       5         5        3       4.40
Financial overview            4      4       4         5        4       4.15
Quality monitoring            4      4       5         4        4       4.20
Configuration catalog         4      5       4         4        4       4.25

SELECTED DOMAIN RATIONALE
Operational planning offers the strongest combination of hierarchy, status visibility, filtering, chronology, responsive transformation, and reusable interaction patterns while remaining generic and neutral.

CYCLE LOCK
Lock operational planning as the reference domain for 2026-11-25 and project-001. Preserve the extracted DNA, scoring weights, and selected rationale for this cycle.

FALLBACK RULE
If the selected domain fails neutrality, accessibility, or responsive validation, use resource inventory without changing the extracted DNA.