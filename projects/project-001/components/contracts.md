Button
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, tertiary, destructive.
- States: default, hover, focus-visible, active, disabled, loading.
- Usage: use one primary action per region and specific verbs such as “Create item”.
- Anti-patterns: vague labels, unnamed icon-only controls, unexplained disabled controls.
- Accessibility: native button semantics, visible focus, keyboard activation, loading status, 44x44px target.

Text field
- Anatomy: label, input, hint, validation message, optional action.
- Variants: single-line, multiline, search.
- States: empty, filled, focus, valid, invalid, disabled, read-only.
- Usage: keep labels persistent and place examples in hint text.
- Anti-patterns: placeholder-only labels, clearing entered content, color-only errors.
- Accessibility: programmatic label and description, error association, logical tab order, autocomplete where applicable.

Select
- Anatomy: label, trigger, selected value, option list, hint, validation message.
- Variants: single-select, multi-select.
- States: closed, open, selected, focused, disabled, invalid.
- Usage: use for bounded option sets; order options predictably.
- Anti-patterns: using select for two choices, hidden selected state, viewport overflow.
- Accessibility: prefer native select; expose expanded and selected states; support keyboard navigation and Escape.

Dialog
- Anatomy: title, description, content, close control, action group.
- Variants: confirmation, form, alert.
- States: closed, open, submitting, validation-error, error.
- Usage: reserve for focused decisions or short tasks.
- Anti-patterns: nested dialogs, irreversible default actions, dismissal with data loss.
- Accessibility: accessible name and description, focus management, Escape support, focus restoration, blocked background interaction.

Table
- Anatomy: caption, header row, body rows, status, row actions.
- Variants: compact, standard, selectable.
- States: loading, populated, empty, filtered-empty, error, selected.
- Usage: align comparable values and keep headings concise.
- Anti-patterns: layout tables, unnamed icon actions, excessive narrow-screen columns.
- Accessibility: table semantics, scoped headers, selection state, responsive alternative.

Alert and toast
- Anatomy: status icon, message, optional action, dismiss control.
- Variants: info, success, caution, error.
- States: entering, visible, action-available, dismissing, expired.
- Usage: place alerts near affected content; use toasts for brief non-blocking feedback.
- Anti-patterns: critical errors only in toasts, auto-dismissed essential information, alarmist wording.
- Accessibility: suitable live-region priority, text plus visual status, keyboard-accessible dismissal.