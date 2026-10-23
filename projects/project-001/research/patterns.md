Project ID: project-001
Date: 2026-10-23

DOMINANT PATTERNS
- Modular cards, structured lists, persistent navigation, clear hierarchy.
- Neutral surfaces, one restrained accent, semantic status colors.
- Search, filter, sort, save, undo, and explicit empty/loading/error states.
- Dense wide layouts with progressive stacking on narrow screens.

EMERGING PATTERNS
- Quick actions with visible labels and limited scope.
- Inline editing with validation and reversible confirmation.
- Shared tokens for color, spacing, typography, density, and motion.
- Accessibility-first focus, contrast, keyboard order, and reduced-motion support.

DEPRECATED PATTERNS
- Excessive gradients, decorative glass effects, and low-contrast text.
- Hidden navigation, unlabeled icon-only controls, irreversible destructive actions.
- Color-only status indicators and hover-only information.

OUTLIER PATTERNS
- Editorial long-form layouts inside utility products.
- Display typography in dense operational interfaces.
- Full-screen visual canvases where compact lists improve scanning.

EXTRACTED DNA
Visual: neutral base, high-contrast text, one primary accent, 8-point spacing, medium-radius containers, restrained borders.
Interactional: predictable navigation, direct manipulation, progressive disclosure, inline validation, reversible actions, explicit feedback.
Accessibility: WCAG AA contrast target, visible focus, logical reading order, keyboard-complete controls, labeled icons, reduced-motion alternative, non-color status cues.
Responsive: wide layouts use columns; medium layouts collapse secondary panels; narrow layouts stack sections and retain visible primary actions.

CANDIDATE PRODUCT DOMAINS
1. Project planning: Organizes tasks, milestones, priorities, and progress in a structured workspace.
2. Knowledge library: Classifies, searches, annotates, and retrieves reference material.
3. Inventory catalog: Tracks items, categories, availability, and condition in compact records.
4. Travel planning: Arranges destinations, schedules, reservations, and preparation details.
5. Habit tracking: Presents recurring activities, targets, streaks, and trends with low cognitive load.
6. Content calendar: Coordinates draft states, dates, channels, and review checkpoints.

WEIGHTED SCORING MATRIX
Weights: clarity 25, reuse 20, responsive fit 20, accessibility fit 20, visual flexibility 15. Scores are 1-5; result is out of 5.
Project planning: 5, 5, 5, 5, 4 = 4.80
Knowledge library: 5, 5, 4, 5, 4 = 4.60
Inventory catalog: 4, 5, 5, 4, 4 = 4.45
Travel planning: 4, 4, 4, 4, 5 = 4.10
Content calendar: 4, 4, 4, 4, 4 = 4.00
Habit tracking: 4, 3, 4, 5, 4 = 3.95

SELECTED DOMAIN RATIONALE
Project planning supports the broadest reusable pattern set: navigation, filters, statuses, timelines, lists, cards, forms, dashboards, responsive density, and accessible progress communication.

CYCLE LOCK
Lock the selected domain, visual DNA, interaction principles, and accessibility baseline for this cycle. Permit only copy, spacing, component-state, and responsive refinements unless evidence shows a fundamental usability conflict.

FALLBACK RULE
If project planning requires specialized assumptions that reduce reuse, select knowledge library while preserving the same DNA, scoring criteria, and accessibility baseline.