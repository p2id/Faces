Date: 2026-11-22
Project ID: project-001

Dominant patterns:
- Clear hierarchy, compact headers, grouped content, persistent navigation, and visible state.
- List, table, card, split-pane, and detail-drawer structures with consistent alignment.
- Neutral surfaces, restrained accent color, semantic status colors, and high-contrast text.
- Search, filter, sort, selection, inline edit, and reversible actions.

Emerging patterns:
- Compact, comfortable, and expanded density modes.
- Contextual action bars that reduce repeated navigation.
- Progressive disclosure for advanced options.
- Responsive reflow from multi-column views to prioritized stacks.
- User-configurable columns, filters, and view preferences.

Deprecated patterns:
- Low-contrast decorative gradients.
- Deep navigation without location context.
- Unlabeled icon-only controls.
- Auto-advancing panels, persistent popups, and irreversible primary actions.

Outlier patterns:
- Split views preserving overview while exposing detail.
- Instructional empty states without decorative illustration.
- Inline validation with reserved space to prevent layout shift.
- Dense data views with explicit overflow and density controls.

Extracted DNA:
Visual: neutral canvas, limited elevation, 8px spacing rhythm, 1px borders, medium-radius geometry, one primary accent, semantic color reserved for state.
Interactional: predictable focus order, explicit selection, visible hover and pressed states, keyboard-complete actions, reversible destructive operations, immediate non-blocking feedback.
Accessibility: strong contrast, visible focus, semantic headings and landmarks, text labels for controls, minimum 44px targets, reduced-motion support, no color-only meaning.
Responsive: fluid containers, mobile-first priority, readable minimum widths, stacked content below tablet width, controlled overflow for dense data, persistent primary action where practical.

Candidate domains:
- Planning calendar: organizes dates, schedules, and related details in a time-based workspace.
- Knowledge library: structures searchable reference items with metadata, filters, and detail views.
- Metrics dashboard: presents values, trends, comparisons, and status summaries.
- Asset catalog: manages browsable records with previews, attributes, and batch controls.
- Preference console: groups configurable options with explicit state and validation.
- Workflow board: presents ordered items across states with filtering and movement.

Weighted scoring matrix:
Weights: clarity 25%, task fit 20%, responsive behavior 20%, accessibility 20%, extensibility 15%. Scores: 1–5.

Domain                 Clarity  Fit  Responsive  Access  Extensibility  Total
Planning calendar      4.6      4.5  4.5         4.4     4.3            4.47
Knowledge library      4.5      4.4  4.3         4.5     4.6            4.46
Metrics dashboard      4.2      4.3  4.1         4.2     4.4            4.24
Asset catalog          4.1      4.0  4.0         4.2     4.3            4.10
Preference console     4.4      4.1  4.4         4.6     4.1            4.32
Workflow board         4.3      4.5  3.9         4.1     4.5            4.27

Selected domain rationale: Planning calendar scores highest and provides reusable patterns for time, grouping, filtering, detail, status, and responsive prioritization.
Cycle lock: Planning calendar, extracted DNA, scoring weights, and Direction B are fixed for 2026-11-22.
Fallback rule: If calendar assumptions fail validation, use Knowledge library while preserving the extracted DNA, accessibility rules, responsive rules, and scoring weights.