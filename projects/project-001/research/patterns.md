Project: project-001
Date: 2026-11-19

Dominant patterns:
- Structured cards, panels, tables, and summary bands.
- Neutral surfaces with one restrained functional accent.
- Persistent navigation, contextual actions, and progressive disclosure.
- Clear loading, empty, validation, error, and success states.
- Responsive grids that become prioritized stacks.

Emerging patterns:
- Searchable command surfaces.
- Adaptive density and configurable views.
- Semantic tokens paired with text or icon status cues.
- Container-aware layouts.
- Motion focused on spatial continuity.

Deprecated patterns:
- Decorative gradients competing with content.
- Hidden gesture-only navigation.
- Color-only status communication.
- Excessive modal interruption.
- Fixed-width layouts without narrow-screen adaptation.

Outlier patterns:
- Monochrome interfaces with one high-contrast action color.
- Split panes preserving overview during detail inspection.
- Reversible inline editing.
- Timeline or matrix views for dense comparison.

Visual DNA:
- Warm or cool neutral surfaces, slate text, restrained semantic colors.
- One functional accent, 8-point spacing, 10–14px radii, subtle borders.
- Strong contrast, compact controls, consistent icon geometry.

Interaction DNA:
- Direct, reversible actions with nearby feedback.
- Explicit focus, hover, pressed, loading, empty, error, and success states.
- Progressive disclosure and preserved context.
- Predictable keyboard order and visible primary actions.

Accessibility DNA:
- WCAG-aligned contrast and non-color status cues.
- Visible focus indicators and semantic heading structure.
- Approximately 44px minimum touch targets where practical.
- Reduced-motion alternative.
- Associated labels, descriptions, and error messages.

Responsive DNA:
- 12-column wide grid, 6-column medium grid, prioritized narrow stack.
- Fluid spacing and typography within bounded containers.
- Side navigation transforms into compact top or bottom navigation.
- Dense tables transform into prioritized cards or scroll regions.
- Primary actions remain visible without fixed viewport assumptions.

Candidate product domains:
- Operations dashboard — Monitors status, trends, exceptions, and prioritized actions.
- Planning workspace — Organizes milestones, dependencies, resources, and progress.
- Knowledge browser — Finds, filters, compares, and organizes structured content.
- Quality review console — Inspects records, applies decisions, and tracks resolution states.
- Configuration studio — Composes settings and reusable modules with immediate validation.
- Analytics explorer — Examines metrics through filters, comparisons, and segments.

Weighted scoring matrix, 1–5; weights: clarity 25%, reuse 20%, accessibility 20%, responsive fit 15%, distinction 10%, interaction depth 10%:
- Operations dashboard: 5,5,5,5,4,5 = 4.85
- Knowledge browser: 5,5,5,5,3,4 = 4.65
- Planning workspace: 4,5,4,4,4,5 = 4.35
- Quality review console: 4,4,5,4,4,5 = 4.35
- Configuration studio: 4,4,4,4,5,5 = 4.15
- Analytics explorer: 4,4,4,5,4,4 = 4.10

Selected domain rationale:
Operations dashboard provides the strongest reusable combination of hierarchy, status communication, filtering, responsive density, accessibility states, and interaction depth without requiring specialized styling.

Cycle lock:
2026-11-19; project-001; operations dashboard; foundation tokens, responsive rules, accessibility requirements, and primary interaction model are fixed for this cycle.

Fallback rule:
If the selected domain cannot support the required hierarchy or responsive behavior, use knowledge browser while preserving the extracted DNA.