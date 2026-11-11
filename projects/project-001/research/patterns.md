PROJECT_ID: project-001
DATE: 2026-11-11
SCOPE: Generic, neutral, reusable product experience.

DOMINANT_PATTERNS
Clear hierarchy; modular cards, tables, filters, tabs, and summaries; restrained visual styling; visible status; controls adjacent to affected content.

EMERGING_PATTERNS
Density modes; inline reversible editing; contextual summaries; progressive disclosure; responsive tables that become prioritized record lists.

DEPRECATED_PATTERNS
Purpose-free gradients; hidden primary actions; equal-weight dashboard metrics; late validation; decorative motion; icon-only controls without labels.

OUTLIER_PATTERNS
Single-surface command layouts; text-first high-density views; persistent comparison panes; exception-focused views that elevate anomalies above routine content.

EXTRACTED_DNA
Visual: neutral canvas, one accent, semantic status colors, 8px spacing rhythm, moderate radius, clear borders, restrained elevation.
Interactional: predictable navigation, visible status, direct manipulation, inline validation, reversible actions, progressive disclosure, keyboard-complete controls.
Accessibility: strong contrast, visible focus, logical reading order, semantic labels, non-color status cues, reduced-motion support, 44px minimum touch targets.
Responsive: mobile-first priority order, single-column collapse, preserved primary action, adaptive tables, fluid type scale, content-driven breakpoints.

CANDIDATE_PRODUCT_DOMAINS
Analytics workspace — review trends, compare measures, and inspect exceptions in structured data.
Scheduling planner — arrange time-based items, resolve conflicts, and review upcoming commitments.
Inventory console — monitor quantities, identify thresholds, and update item records.
Learning library — browse structured material, track progress, and resume selected content.
Finance overview — inspect balances, categorize activity, and review period summaries.
Service operations board — prioritize requests, inspect states, and coordinate repeatable actions.

WEIGHTED_SCORING_MATRIX
Weights: Reusability 30, Clarity 25, Responsive fit 20, Accessibility 15, Distinctiveness 10. Scores 1–5; totals normalized to 100.
Analytics workspace: 5,5,5,4,4 = 94
Scheduling planner: 4,4,4,4,4 = 80
Inventory console: 5,4,5,4,3 = 87
Learning library: 4,4,4,5,3 = 80
Finance overview: 4,4,4,4,4 = 80
Service operations board: 5,4,4,4,4 = 86

SELECTED_DOMAIN_RATIONALE
Analytics workspace scores highest because it supports reusable information architecture, clear responsive transformations, accessible status communication, and multiple visual treatments without specialized assumptions.

CYCLE_LOCK
Lock the selected domain, hierarchy, semantic palette, type scale, responsive priorities, and accessibility baseline. Allow only content, spacing, component, and interaction refinements.

FALLBACK_RULE
If the selected domain cannot preserve clarity, responsiveness, or accessibility, switch to Service operations board while retaining the same visual DNA, accessibility baseline, and scoring criteria.