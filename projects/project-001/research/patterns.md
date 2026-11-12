Project: project-001
Date: 2026-11-12
Dominant patterns:
- Clear hierarchy, compact headers, grouped panels, restrained borders, and progressive disclosure.
- Task-first navigation with persistent primary actions and contextual secondary actions.
- Structured views with aligned columns, filtering, sorting, visible status, and stable labels.
- Neutral surfaces with one accent reserved for action, selection, and emphasis.

Emerging patterns:
- Command search for rapid navigation across structured content.
- Inline editing with reversible confirmation and preserved context.
- Adaptive layouts that move from comparison views to prioritized single-column review.
- Tokenized themes with contrast checks and reduced-motion support.

Deprecated patterns:
- Decorative gradients without semantic purpose.
- Hover-only navigation or actions.
- Dense tables without responsive fallback or focus treatment.
- Color-only status communication and ambiguous icon-only controls.

Outlier patterns:
- Split-pane review with synchronized summary and detail.
- Persistent comparison tray for selected records.
- Collapsible utility rail that becomes an explicit drawer.
- Structured empty states with direct next actions and minimal decoration.

Visual DNA:
- Soft-neutral canvas, high-contrast text, one controlled accent, subtle elevation, 8px spacing rhythm, 10–14px radius, 1px separators, consistent icon geometry.
- Emphasis scale: primary action, current state, supporting metadata.

Interactional DNA:
- Immediate feedback, predictable focus order, reversible changes, stable navigation, explicit loading and error states, keyboard-complete controls, minimal modal interruption.
- Filtering, sorting, selection, and pagination preserve context.

Accessibility DNA:
- WCAG-aligned contrast, visible focus, semantic headings, labeled controls, non-color state cues, 44px minimum touch targets, logical reading order, reduced-motion support, and zoom-safe layouts.

Responsive DNA:
- Desktop supports comparison and parallel context; tablet reduces secondary density; mobile prioritizes one task, stacks content, and moves utilities into drawers or sheets.
- Breakpoints follow content needs; essential structured data may use controlled horizontal overflow.

Candidate product domains:
1. Data review workspace — Inspect, filter, compare, and annotate structured information.
2. Schedule planning surface — Arrange time-based activities, dependencies, and capacity views.
3. Reference library — Search, organize, and retrieve reusable knowledge assets.
4. Catalog configuration surface — Browse, compare, configure, and review item attributes.
5. Resource monitoring console — Observe trends, thresholds, exceptions, and historical summaries.

Weighted scoring matrix:
Weights: clarity 25, recurring value 20, responsive fit 20, accessibility fit 20, extensibility 15.
Data review workspace: 5/5/5/5/5 = 100
Schedule planning surface: 4/4/4/4/4 = 80
Reference library: 4/4/5/5/4 = 87
Catalog configuration surface: 4/4/4/4/5 = 82
Resource monitoring console: 4/5/4/4/4 = 84

Selected domain rationale:
Data review workspace ranks highest because its inspect-and-decide loop directly supports hierarchy, comparison, filtering, accessibility, and responsive patterns without specialized assumptions.

Cycle lock:
Lock project-001, date 2026-11-12, selected domain, visual DNA, interactional DNA, accessibility DNA, and responsive DNA for this cycle.

Fallback rule:
If the selected domain lacks a coherent primary task, accessible state model, or responsive layout, use Reference library, Resource monitoring console, Catalog configuration surface, then Schedule planning surface in score order.