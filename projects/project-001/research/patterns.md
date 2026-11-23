Project: project-001 | Date: 2026-11-23

DOMINANT PATTERNS
- Clear hierarchy with one primary action and grouped secondary actions.
- Modular cards, lists, filters, and compact metadata blocks.
- Progressive disclosure for secondary detail.
- Persistent orientation through section labels and active states.
- Responsive stacking with preserved action order.

EMERGING PATTERNS
- Semantic design tokens for color, spacing, radius, type, and motion.
- Contextual actions that reduce navigation depth.
- Inline validation, reversible changes, and explicit status feedback.
- Density controls for scanning and focused reading.
- Content-aware empty, loading, and error states.

DEPRECATED PATTERNS
- Decorative gradients without functional purpose.
- Equal-weight dashboards with excessive visual density.
- Gesture-only navigation and hidden controls.
- Auto-advancing content and non-dismissible motion.
- Status communicated by color alone.

OUTLIER PATTERNS
- Edge-to-edge command surfaces for frequent actions.
- Split-pane detail views preserving list context.
- Monochrome status systems reinforced by labels and shapes.
- Timeline layouts for strictly sequential information.

EXTRACTED DNA
- Visual: neutral surfaces, one accent color, high-contrast text, 8-point spacing rhythm, medium radii, restrained dividers.
- Interactional: predictable navigation, direct manipulation, visible state changes, explicit confirmation for consequential actions, undo where practical.
- Accessibility: semantic structure, keyboard parity, visible focus, minimum 44px targets, WCAG AA contrast, reduced-motion support, labels independent of color.
- Responsive: mobile-first flow, 16px minimum side padding, 4-column small-screen grid, 12-column wide-screen grid, fluid type, controlled overflow.

CANDIDATE PRODUCT DOMAINS
1. Content library: discover, organize, filter, save, and resume informational material.
2. Learning planner: structure topics, milestones, references, and completion states.
3. Commerce catalog: browse, compare, filter, and review item information.
4. Travel planner: coordinate places, dates, reservations, and sequential plans.
5. Personal finance: organize balances, transactions, budgets, and summaries.
6. Wellness tracker: present routines, measurements, trends, and reminders without clinical claims.

WEIGHTED SCORING MATRIX
Weights: Reusability 30; clarity 25; responsive fit 20; accessibility fit 15; visual flexibility 10.
- Content library: 5,5,5,5,5 = 5.00
- Learning planner: 5,4,5,5,4 = 4.65
- Commerce catalog: 4,4,5,4,5 = 4.35
- Personal finance: 4,4,4,4,4 = 4.00
- Wellness tracker: 4,4,4,4,3 = 3.95
- Travel planner: 4,3,4,4,4 = 3.85

SELECTED DOMAIN RATIONALE
Content library offers the broadest reusable information model for browse, search, filtering, detail, saving, resuming, metadata, and responsive density without requiring specialized claims.

CYCLE LOCK
Lock the selected domain, core hierarchy, token baseline, accessibility requirements, and primary interaction model. Allow only refinements that preserve these constraints.

FALLBACK RULE
If content density, evidence, or viewport constraints conflict, retain accessibility and action clarity; use a single-column layout, one accent color, static motion, explicit labels, and progressive disclosure.