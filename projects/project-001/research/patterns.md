Project: project-001 | Date: 2026-10-26 | Cycle: 01 | State: stable

DOMINANT
- Clear hierarchy with one primary action and visible state.
- Modular cards, lists, tabs, filters, and progressive disclosure.
- Neutral foundations, restrained accents, consistent spacing.
- Responsive prioritization that preserves essential content.

EMERGING
- Summary-first layouts above detailed records.
- Inline validation, reversible actions, and persistent filter state.
- Tokenized visual systems with compact command areas.
- Content-aware transformation from tables to stacked records.

DEPRECATED
- Decorative gradients without semantic purpose.
- Hover-only navigation or actions.
- Equal emphasis across dense panels.
- Motion used as the only confirmation.

OUTLIERS
- Highly compressed expert-oriented data views.
- Single-surface layouts combining summary, status, and action.
- Nearly monochrome systems with one semantic accent.
- Progressive disclosure with unusually deep detail layers.

EXTRACTED DNA
Visual: neutral base, one accent family, semantic status colors, 8-point spacing, 10–12px radius, restrained elevation, consistent icon geometry.
Interactional: explicit primary action, predictable focus order, persistent active filters, inline state changes, reversible actions where practical, no hover-only meaning.
Accessibility: WCAG AA contrast target, visible focus, semantic labels, 44px minimum touch targets, text-plus-icon status cues, readable errors, reduced-motion support.
Responsive: mobile-first hierarchy, fluid gutters, single-column default, priority-based reduction, stacked records replacing wide tables, no required horizontal scrolling.

CANDIDATE DOMAINS
1. Planning workspace — organizes dates, tasks, dependencies, and progress.
2. Resource catalog — supports discovery, filtering, comparison, and structured details.
3. Monitoring console — presents status, exceptions, trends, and response actions.
4. Learning library — organizes modules, completion states, search, and references.
5. Budget planner — presents categories, limits, forecasts, and review actions.
6. Service request center — tracks requests, required details, status, and resolution history.

WEIGHTED SCORING MATRIX
Weights: Reusability 25, Clarity 20, Responsive fit 15, Accessibility fit 15, Visual scalability 15, Neutrality 10; total /100.
Planning workspace: 23+18+14+14+14+9 = 92
Resource catalog: 24+18+15+14+14+9 = 94
Monitoring console: 22+17+13+13+15+8 = 88
Learning library: 23+18+14+14+13+9 = 91
Budget planner: 21+17+13+13+14+8 = 86
Service request center: 24+18+14+14+14+9 = 93

SELECTED DOMAIN RATIONALE
Resource catalog is selected at 94 because discovery, filtering, comparison, detail, status, and responsive transformation patterns generalize broadly without specialized assumptions.

CYCLE LOCK
Locked domain: resource catalog. Locked DNA: neutral visual system, modular hierarchy, explicit states, responsive priority reduction, accessible interaction defaults.

FALLBACK RULE
If later evidence shows browse-and-compare is not central, switch to planning workspace, retain the extracted DNA, and re-score before replacing the lock.