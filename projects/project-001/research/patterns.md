Project: project-001
Date: 2026-11-05

DOMINANT PATTERNS
- Clear hierarchy with one primary task per view.
- Modular cards, tables, filters, tabs, drawers, and progressive disclosure.
- Neutral surfaces, restrained accents, consistent spacing, and visible system status.
- Responsive layouts that reduce density without removing task context.

EMERGING PATTERNS
- Contextual actions near the active content.
- Inline validation, reversible changes, and persistent filter state.
- Semantic design tokens and user-selectable density.
- Motion used for orientation, confirmation, and state change only.

DEPRECATED PATTERNS
- Low-contrast text, excessive gradients, decorative glass effects, and visual clutter.
- Modal interruptions for routine actions.
- Unlabeled icon-only controls and hidden navigation.
- Auto-advancing content without pause or control.

OUTLIER PATTERNS
- Spatial relationship canvases.
- Timeline-first layouts.
- Synchronized split-pane inspection.
- Keyboard-first command layers.

EXTRACTED DNA
- Visual: warm-neutral canvas, dark text, one restrained accent, 8-point spacing, medium-radius surfaces, shallow elevation, 1px dividers.
- Interactional: direct manipulation, predictable focus order, inline feedback, visible selection, reversible actions, explicit confirmation for irreversible actions.
- Accessibility: semantic structure, minimum 4.5:1 normal-text contrast, visible focus, keyboard parity, reduced-motion support, text-plus-symbol status, scalable type.
- Responsive: fluid columns, priority-based hiding, preserved reading order, minimum 44px touch targets, stacked narrow layouts, horizontal overflow only for dense structured data.

CANDIDATE PRODUCT DOMAINS
- Operational dashboard: summarizes changing information and prioritizes next actions.
- Inventory workspace: supports search, filtering, comparison, quantity, and detail inspection.
- Schedule planner: organizes time-based items, dependencies, and exceptions.
- Document review: supports structured reading, comparison, annotations, and state tracking.
- Energy monitor: presents measurements, trends, thresholds, and period comparisons.
- Dataset catalog: supports metadata discovery, filtering, quality indicators, and structured inspection.

WEIGHTED SCORING MATRIX
Weights: hierarchy 25, responsive fit 20, accessibility value 20, reuse potential 20, visual range 15; scores 1–5.
- Operational dashboard: 5, 5, 5, 5, 4 = 4.80/5
- Inventory workspace: 5, 4, 5, 5, 4 = 4.60/5
- Schedule planner: 4, 4, 4, 4, 5 = 4.20/5
- Document review: 4, 4, 5, 4, 4 = 4.20/5
- Energy monitor: 4, 5, 4, 4, 5 = 4.40/5
- Dataset catalog: 4, 4, 5, 5, 4 = 4.40/5

SELECTED DOMAIN RATIONALE
Operational dashboard is selected because it provides the strongest balance of hierarchy, responsive behavior, accessibility value, component reuse, and generic applicability.

CYCLE LOCK
Lock the selected domain, extracted DNA, accessibility baseline, and responsive rules for project-001 on 2026-11-05.

FALLBACK RULE
If hierarchy or accessibility fails review, use Inventory workspace. If responsive comprehension fails, use Dataset catalog. Preserve locked DNA unless a documented usability issue requires correction.