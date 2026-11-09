Shared anatomy:
- Layout: shell, container, region, stack, grid, divider.
- Content: eyebrow, heading, description, label, value, metadata, helper text.
- Controls: button, field, select, checkbox, tabs, pagination.
- Feedback: status text, recovery action, progress indicator.
- Navigation: skip link, breadcrumb, primary and contextual navigation.

Variants:
- Density: comfortable, compact.
- Emphasis: default, highlighted, critical.
- Layout: single-column, split-column, table, card-list.
- Interaction: static, interactive, selectable, expandable.
- Width: fluid, constrained, full-bleed.

States:
- Availability: loading, ready, empty, unavailable, error.
- Interaction: hover, focused, pressed, selected, expanded, collapsed, disabled.
- Validation: pristine, invalid, submitting, success.
- Communication: info, success, warning, danger.

Usage:
- Compose each region from one clear heading, purpose, and predictable actions.
- Use semantic tokens for color, type, spacing, radius, elevation, motion, and state styling.
- Keep actions adjacent to the content they affect.
- Preserve structure across loading, populated, empty, and error states.
- Use progressive disclosure for secondary detail.

Anti-patterns:
- Do not use color, animation, iconography, or position as the only carrier of meaning.
- Do not mix interaction models for equivalent controls.
- Do not hide essential actions in inaccessible overflow menus.
- Do not use excessive elevation, all-caps body copy, unexplained abbreviations, or placeholder-only labels.
- Do not change control position when state changes.
- Do not imply unsupported completion, status, urgency, or availability.

Accessibility:
- Use semantic HTML and explicit accessible names.
- Maintain WCAG 2.2 AA contrast and visible keyboard focus.
- Provide keyboard equivalents for pointer actions.
- Support zoom, reflow, reduced motion, and 44×44px touch targets.
- Announce validation, loading completion, selection, and errors without stealing focus.
- Relate headings, landmarks, tables, dialogs, and form descriptions programmatically.
- Test default, focused, invalid, loading, empty, and error states.