Date: 2026-10-20
Project: project-001

Dominant patterns: Calm neutral surfaces; strong hierarchy; compact navigation; grouped cards; progressive disclosure; explicit status; one primary action per region.
Emerging patterns: Semantic design tokens; inline validation; contextual empty states; split panes that collapse into staged views; reduced-motion parity.
Deprecated patterns: Equal-weight dashboards; decorative gradients; hidden navigation; icon-only actions without labels; modal-heavy flows; continuous animation.
Outlier patterns: Monochrome interfaces with one accent; command-style search surfaces; sparse editorial layouts for structured content.

Visual DNA: Neutral base, one functional accent, 8px spacing rhythm, 12px radius, thin borders, restrained elevation, sentence-case labels.
Interactional DNA: Predictable focus order, progressive disclosure, inline feedback, reversible actions, visible status, no dead-end states.
Accessibility DNA: WCAG 2.2 AA target; visible focus; minimum 4.5:1 text contrast; 3:1 large-text and non-text contrast; keyboard parity; semantic headings; labeled status; reduced-motion support.
Responsive DNA: Fluid content-first grid; 12 columns on wide screens and 4 on narrow screens; 44px minimum targets; panel collapse before type reduction; primary actions remain visible; no horizontal scrolling.

Candidate domains:
1. Planning workspace — Organizes goals, stages, dependencies, and next actions in a flexible surface.
2. Resource library — Supports discovery, filtering, preview, saving, and retrieval of reusable materials.
3. Configuration console — Presents settings, validation, status, and safely staged changes.
4. Insight explorer — Supports comparison, trends, annotations, and focused detail views.
5. Request center — Guides intake, progress tracking, supporting context, and resolution states.
6. Learning catalog — Arranges sequential content, progress, prerequisites, and optional exploration.

Weighted scoring matrix; weights: clarity 25, reuse 20, responsive fit 20, accessibility fit 20, visual range 15; scale 1–5.
Domain                       Clarity Reuse Responsive Access Visual Weighted
Planning workspace              5      5       5        5      4      4.80
Resource library                4      5       5        5      4      4.60
Configuration console           5      4       4        5      3      4.25
Insight explorer                4      4       4        4      5      4.05
Request center                  4      4       4        5      3      4.00
Learning catalog                4      4       5        4      4      4.20

Selected domain rationale: Planning workspace leads in clarity, reuse, responsive fit, and accessibility while supporting a broad reusable component vocabulary.
Cycle lock: Lock selected domain, DNA, weights, and evaluation criteria for 2026-10-20 under project-001.
Fallback rule: If the selected domain falls by more than 0.40 points after review, use Resource library; if its score falls below 4.00, use Configuration console.