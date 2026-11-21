Project: project-001
Date: 2026-11-21

Dominant patterns: clear hierarchy, neutral surfaces, one primary action, modular cards, persistent filtering, progressive disclosure, inline status feedback.
Emerging patterns: adaptive density, contextual actions, content-aware empty states, preference-based motion reduction, split-view comparison.
Deprecated patterns: low-contrast text, color-only status, stacked dialogs, hidden navigation, decorative animation, fixed-width layouts.
Outlier patterns: asymmetric entry panels, oversized summary metrics, edge action rails, monochrome themes with one semantic accent.

Visual DNA: calm neutral base, single controlled accent, moderate radius, restrained elevation, consistent icon scale, four-tier spacing.
Interactional DNA: predictable navigation, reversible changes, immediate state visibility, inline validation, one dominant action, complete keyboard operation.
Accessibility DNA: semantic structure, visible focus, 4.5:1 minimum text contrast, non-color status cues, logical order, scalable text, reduced-motion mode, 44px minimum touch targets.
Responsive DNA: mobile-first reflow, grid-to-stack transition, persistent primary action, readable measure, safe comparison overflow, no essential content hidden.

Candidate domains:
1. Planning workspace: organizes objectives, steps, dates, dependencies, and progress.
2. Knowledge library: supports browsing, filtering, comparing, and revisiting reference content.
3. Subscription manager: summarizes recurring services, renewal timing, status, and cost.
4. Booking coordinator: supports availability review, selection, confirmation, and changes.
5. Inventory console: presents item states, quantities, thresholds, and grouped actions.
6. Analytics reader: presents measures, trends, comparisons, and exceptions.

Weighted criteria: reuse 25%, clarity 20%, accessibility 15%, responsive fit 15%, visual flexibility 15%, interaction depth 10%.
Scores, 1–5; weighted total:
Planning workspace: 5,5,5,5,5,4 = 4.80
Knowledge library: 5,4,5,5,5,4 = 4.65
Subscription manager: 4,4,4,5,4,4 = 4.10
Booking coordinator: 4,4,4,4,4,5 = 4.05
Inventory console: 4,4,4,4,4,5 = 4.05
Analytics reader: 4,4,4,4,5,4 = 4.10

Selected domain rationale: Planning workspace provides the broadest reusable combination of hierarchy, progress, grouping, status, responsive composition, and accessible state handling.
Cycle lock: planning workspace; calm, structured, adaptive, content-first; neutral base with one semantic accent.
Fallback rule: retain the locked DNA; switch to Knowledge library only if planning-workspace reuse or accessibility fit falls below 4/5.