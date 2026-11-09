Project: project-001
Date: 2026-11-09

Dominant patterns: Modular cards, structured lists, compact tables, progressive disclosure, persistent primary action, visible status, and complete empty/loading/error states.
Emerging patterns: Contextual quick actions, inline editing, adaptive density, summary-first layouts, reduced-motion defaults, and reversible changes.
Deprecated patterns: Unstructured dense dashboards, hidden navigation, decorative gradients, color-only status, auto-advancing motion, and placeholder-only fields.
Outlier patterns: Spatial canvases, timeline-first navigation, and monochrome interfaces; use only when they materially improve comprehension.

Visual DNA: Neutral layered surfaces, one functional accent, 8-point spacing rhythm, moderate corner radius, thin borders, restrained icons, and high text contrast.
Interactional DNA: One dominant action per view, predictable navigation, reversible operations, inline validation, visible state feedback, and complete keyboard operation.
Accessibility DNA: Semantic hierarchy, minimum 4.5:1 normal-text contrast, 3:1 large-text and control-boundary contrast, visible focus, minimum 44px targets, non-color status cues, labels independent of placeholders, and reduced-motion support.
Responsive DNA: Content-first stacking, fluid columns, density reduction before truncation, persistent critical actions, labeled-row transformation for tables, and no horizontal scrolling for primary tasks.

Candidate domains:
- Scheduling: Organizes time-based items, availability, conflicts, and reminders.
- Resource planning: Coordinates capacity, allocation, dependencies, and priorities.
- Knowledge organization: Structures reference material through collections, search, filters, and details.
- Progress tracking: Shows milestones, status, trends, blockers, and completion history.
- Content review: Supports inspection, annotation, approval, comparison, and revision states.

Weighted scoring matrix; scale 1–5. Weights: clarity 20%, repeatability 25%, accessibility 20%, responsive fit 20%, extensibility 15%.
Domain                  Clarity  Repeatability  Accessibility  Responsive  Extensibility  Score
Scheduling               4        5               4               5           4              4.45
Knowledge organization   4        4               4               4           5              4.15
Progress tracking        4        4               4               4           4              4.00
Resource planning        4        4               3               4           4              3.80
Content review           3        4               4               3           4              3.60

Selected domain rationale: Scheduling most effectively tests hierarchy, recurring actions, state visibility, conflict handling, responsive transformation, and accessible time-based presentation.
Cycle lock: Lock Scheduling and the extracted DNA for this cycle; evaluate all directions against clarity, accessibility, responsive fit, and extensibility.
Fallback rule: If scheduling density or responsive complexity reduces comprehension, switch to Knowledge organization while retaining the locked DNA.