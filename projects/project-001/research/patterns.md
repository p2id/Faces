Date: 2026-11-01
Project ID: project-001

DOMINANT PATTERNS
- Clear hierarchy with one primary action per view.
- Modular cards, panels, tabs, filters, and status indicators.
- Neutral foundation, restrained accent, strong contrast.
- Responsive collapse from wide grid to narrow single-column priority.
- Persistent context through title, location cue, summary, and consistent controls.

EMERGING PATTERNS
- Quick actions with visible alternatives.
- Compact, comfortable, and expanded density modes.
- Inline validation and contextual guidance.
- Light, dark, and high-contrast tokenized themes.
- Motion limited to state, continuity, and completion feedback.

DEPRECATED PATTERNS
- Decorative gradients, blur, and excessive glass effects.
- Auto-advancing carousels and carousel-dependent discovery.
- Unlabeled icon-only controls.
- Stacked modals and irreversible actions without recovery.
- Low-contrast text and color-only status indicators.

OUTLIER PATTERNS
- Asymmetric emphasis for exceptional priority states.
- Geometric empty states without illustration.
- Split-view comparison for complex choices.
- Static reduced-motion transitions with explicit state labels.

EXTRACTED DNA
Visual: neutral base, one accent family, 8-point spacing, 10–14px radius, 1px separators, restrained elevation, concise labels, limited semantic colors.
Interactional: predictable focus order, one primary action per surface, reversible changes, inline feedback, explicit loading and completion states, keyboard-accessible controls.
Accessibility: semantic structure, visible focus, minimum 4.5:1 text contrast, non-color status cues, scalable text, 44px minimum touch targets, reduced-motion option, no time-critical interaction by default.
Responsive: 12-column wide grid and 4-column narrow grid; content-first collapse; fluid type within safe bounds; intentional overflow only for dense data; controls wrap before clipping.

CANDIDATE PRODUCT DOMAINS
1. Planning workspace — organizes priorities, schedules, and related materials in one adaptable view.
2. Learning library — supports structured discovery, progress tracking, and reference access.
3. Service directory — supports comparison, filtering, and selection of categorized offerings.
4. Resource dashboard — summarizes availability, status, trends, and next actions.
5. Configuration center — presents settings and safe, reversible changes.
6. Collection browser — supports scanning, sorting, saving, and comparing grouped items.

WEIGHTED SCORING MATRIX
Weights: clarity 30%, reuse 25%, responsive fit 20%, accessibility fit 15%, flexibility 10%. Scores use a 1–5 scale; total is normalized to 100.

Domain                  Clarity  Reuse  Responsive  A11y  Flexibility  Total
Planning workspace       5        5      5           5     4            96
Learning library         4        5      5           5     4            91
Service directory        4        5      5           4     5            89
Resource dashboard       5        4      4           5     4            88
Configuration center     4        4      5           5     3            84
Collection browser       4        5      4           4     5            86

SELECTED DOMAIN RATIONALE
Planning workspace ranks highest because it expresses hierarchy, modular composition, responsive behavior, reversible interaction, and accessible status communication without specialized visual assumptions.

CYCLE LOCK
Retain the selected domain, DNA, scoring weights, and primary direction for this cycle. Change only when documented evidence shows a structural or accessibility failure.

FALLBACK RULE
If the selected domain cannot support clear primary actions, responsive compression, or accessible status cues, use Learning library while retaining the same DNA and scoring weights.