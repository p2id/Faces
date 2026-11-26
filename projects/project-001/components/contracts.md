Button
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, pressed, focus-visible, loading, disabled.
- Usage: one primary action per region; label the outcome.
- Anti-patterns: vague labels, unnamed icons, unexplained disabled actions.
- Accessibility: native button semantics, keyboard activation, 44px target, announced loading.

Text input
- Anatomy: label, input, hint, error, optional count.
- Variants: single-line, multiline, read-only.
- States: empty, filled, focus, valid, invalid, disabled, read-only.
- Usage: keep labels visible; use hints for format examples.
- Anti-patterns: placeholder-only labels, color-only errors, silent value loss.
- Accessibility: explicit label, hint/error description, announced validation.

Select
- Anatomy: label, trigger, value, list, hint, error.
- Variants: single, grouped, searchable.
- States: closed, open, empty, selected, focus, invalid, disabled.
- Usage: use for bounded choices; show the selected value.
- Anti-patterns: excessive lists, hidden values, unsupported custom controls.
- Accessibility: expose expanded state, controls relationship, keyboard navigation, Escape, focus.

List/table
- Anatomy: caption or heading, columns, rows, status, actions.
- Variants: compact, standard, card-converted.
- States: loading, populated, empty, filtered-empty, error, selected.
- Usage: align values by type; keep row actions consistent.
- Anti-patterns: inaccessible sorting, clipped values, color-only status.
- Accessibility: semantic structure, row/column relationships, sort state, responsive alternative.

Dialog
- Anatomy: title, description, content, close control, actions.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, validation-error, success, error.
- Usage: reserve for focused decisions or short tasks.
- Anti-patterns: nested dialogs, destructive default, accidental background dismissal.
- Accessibility: named dialog, focus trap, Escape, restoration, clear actions.