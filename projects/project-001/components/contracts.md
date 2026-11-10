Button
- Anatomy: label, optional icon, loading indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, pressed, focus-visible, loading, disabled.
- Usage: use explicit verbs such as “Apply filters” and “Save changes”.
- Anti-patterns: unlabeled icon-only control, invisible disabled text, destructive styling for routine actions.
- Accessibility: native button semantics, 44px target, announced loading state.

Text field
- Anatomy: label, input, hint, error, optional action.
- Variants: search, single-line, compact.
- States: empty, filled, hover, focus, invalid, valid, disabled, read-only.
- Usage: keep label visible; use placeholder as example only.
- Anti-patterns: placeholder-only label, color-only error, clearing valid input unexpectedly.
- Accessibility: associated label, hint, and error; clear purpose and recovery text.

Select/filter
- Anatomy: label, trigger, selected value, option list, status.
- Variants: single-select, filter-select, compact.
- States: closed, open, selected, option hover, focus-visible, invalid, disabled.
- Usage: provide a meaningful “All” option where applicable.
- Anti-patterns: inaccessible custom listbox, ambiguous empty selection, excessive options without search.
- Accessibility: expose expanded and selected states; support keyboard navigation and Escape.

Table/list
- Anatomy: heading/caption, headers, rows, status, actions.
- Variants: table, responsive cards, selectable rows.
- States: loading, populated, empty, filtered empty, selected, error.
- Usage: place useful columns first; preserve reading order.
- Anti-patterns: unlabeled icon actions, silent row replacement, essential text hidden by truncation.
- Accessibility: semantic headers, row context, keyboard selection, announced updates.

Dialog
- Anatomy: title, description, content, actions, close control.
- Variants: confirmation, form, detail.
- States: closed, opening, open, submitting, validation error, success.
- Usage: reserve for focused decisions or short tasks.
- Anti-patterns: nested dialogs, destructive default, dismissal that loses input.
- Accessibility: modal semantics, labelled title, focus containment, safe Escape, focus restoration.

Alert/toast
- Anatomy: message, optional status icon, action, dismiss control.
- Variants: info, success, warning, error, persistent.
- States: visible, dismissing.
- Usage: state outcome and next step concisely.
- Anti-patterns: transient form errors, disappearing critical errors, excessive simultaneous alerts.
- Accessibility: use status/alert semantics appropriately; do not steal focus for passive feedback.