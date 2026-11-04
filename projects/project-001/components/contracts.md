Button
- Anatomy: label, optional icon, focus ring, loading indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, focus-visible, pressed, disabled, loading, success, error.
- Usage: provide one primary action per surface; use imperative labels.
- Anti-patterns: vague labels, competing primary actions, color-only meaning, unexplained disabled state.
- Accessibility: native button semantics, accessible name, 44px target, visible focus, announced loading.

Input
- Anatomy: label, control, hint, validation message, optional affordance.
- Variants: text, search, numeric, masked.
- States: empty, filled, focus, disabled, readonly, invalid, valid, loading.
- Usage: label every field and place examples in hint text.
- Anti-patterns: placeholder-only labels, disappearing errors, unexplained constraints.
- Accessibility: associated label, linked hint/error, exposed invalid state, keyboard access.

Select
- Anatomy: label, trigger, value, indicator, option list, validation message.
- Variants: single, multi, searchable.
- States: closed, open, selected, focus, disabled, invalid, loading, no-results.
- Usage: use for bounded choices and expose the current selection.
- Anti-patterns: unsupported custom keyboard behavior, excessive options, hidden selection.
- Accessibility: combobox or native select semantics, active option exposure, Arrow/Escape support.

Table
- Anatomy: caption, headers, rows, cells, status, row actions, pagination.
- Variants: standard, selectable, sortable, compact, responsive.
- States: default, hover-row, selected-row, focus-row, loading, empty, error, overflow.
- Usage: keep columns scannable and row actions predictable.
- Anti-patterns: layout tables, unlabeled icons, excessive columns, color-only status.
- Accessibility: table semantics, header associations, sort state, selection state, responsive alternative.

Dialog
- Anatomy: title, description, content, close action, action group.
- Variants: confirmation, form, information, destructive.
- States: closed, opening, open, submitting, validation-error, success, closing.
- Usage: interrupt only for important decisions; state consequences clearly.
- Anti-patterns: nested dialogs, irreversible default action, background interaction, missing close path.
- Accessibility: labelled dialog, focus containment, inert background, Escape handling, focus restoration.