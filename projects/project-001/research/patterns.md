Date: 2026-11-17
Project ID: project-001

Dominant patterns: clear hierarchy; modular cards and lists; one primary action per context; explicit status feedback; restrained semantic color; mobile-first reflow.
Emerging patterns: contextual actions; density modes; persistent state summaries; tokenized themes; reduced-motion defaults; split overview/detail layouts.
Deprecated patterns: equal-weight dashboards; hover-only actions; low-contrast text; stacked routine modals; decorative gradients; autoplay motion.
Outlier patterns: synchronized split panes; sequence timelines; large decision summaries; offline-readable empty states; keyboard-first command surfaces.

Visual DNA: warm-neutral canvas, cool-neutral surfaces, graphite text, one focused accent, medium radius, thin dividers, restrained elevation, consistent icon geometry.
Interactional DNA: predictable navigation, immediate local feedback, reversible changes, safe defaults, progressive disclosure, preserved input after recoverable errors.
Accessibility DNA: WCAG 2.2 AA target, visible focus, logical tab order, semantic grouping, minimum 44px targets, non-color status cues, scalable text, reduced motion, explicit error guidance.
Responsive DNA: content-driven breakpoints, priority-first stacking, retained primary action, progressive navigation compression, stacked or scrollable data views, stable readable spacing.

Candidate domains
Planning workspace — organizes priorities, sequences, statuses, and progress in a focused planning surface.
Resource library — supports browsing, filtering, comparison, and saving of structured reference material.
Status center — presents conditions, notices, changes, and resolution states with clear prioritization.
Finance overview — summarizes budgets, transactions, trends, and threshold states with careful emphasis.
Learning hub — organizes modules, completion states, practice activity, and next actions.
Checklist board — supports repeatable checks, exceptions, completion states, and compact evidence.

Weighted scoring: clarity 30%, responsive fit 20%, accessibility leverage 20%, component reuse 15%, neutral suitability 15%; scores 1–5; total weighted score out of 5.

Domain                 Clarity Responsive Access Reuse Neutral Total
Planning workspace        5        5         5      5      5    5.00
Resource library          4        5         5      5      5    4.70
Status center             5        4         5      4      5    4.65
Finance overview          4        4         4      5      4    4.10
Learning hub              4        5         5      4      4    4.45
Checklist board           5        4         5      5      4    4.65

Selected domain rationale: Planning workspace provides the broadest neutral coverage of hierarchy, lists, filters, summaries, statuses, timelines, forms, empty states, and responsive transformations without specialized assumptions.
Cycle lock: lock Planning workspace, warm-neutral visual DNA, one-primary-action rule, WCAG 2.2 AA targets, and mobile-first responsive behavior for 2026-11-17 and project-001.
Fallback rule: if domain fit fails, use Resource library, then Status center, while retaining all locked accessibility, responsive, and interaction principles.