Button
- Anatomy: label, optional icon, optional loading indicator.
- Variants: primary, secondary, tertiary, destructive.
- States: default, hover, focus-visible, pressed, disabled, loading.
- Usage: one primary action per region; use explicit verbs.
- Anti-patterns: vague labels, unnamed icon-only controls, competing primary actions.
- Accessibility: native button semantics, keyboard activation, 44px target, announced loading.

Text field
- Anatomy: label, input, hint, error, optional icon.
- Variants: text, search, date.
- States: empty, filled, focused, disabled, read-only, invalid, valid.
- Usage: persistent visible label and format guidance.
- Anti-patterns: placeholder-only labels, silent validation, clearing values after errors.
- Accessibility: label association, hint/error description, appropriate autocomplete, announced errors.

Select
- Anatomy: label, trigger, value, option list, helper/error text.
- Variants: single-select, filter-select.
- States: closed, open, selected, empty, focused, disabled, invalid.
- Usage: bounded option sets; include “All” for filtering.
- Anti-patterns: excessive options, hidden selection, keyboard-incomplete custom control.
- Accessibility: expanded/controls relationships, arrow-key navigation, escape to close, visible focus.

Data table
- Anatomy: caption, header row, body rows, status indicator, pagination.
- Variants: compact, standard, responsive.
- States: loading, populated, empty, no-results, error, row-hover, row-selected.
- Usage: align comparable values; keep actions in a consistent column.
- Anti-patterns: unreadable density, unnamed icon actions, color-only status.
- Accessibility: semantic table markup, header associations, announced selection, preserved responsive relationships.

Dialog
- Anatomy: title, description, content, close control, actions.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, success, error.
- Usage: interrupt only for focused decisions or required input.
- Anti-patterns: nested dialogs, destructive default action, silent loss of unsaved input.
- Accessibility: modal semantics, labelled title, focus containment, escape behavior, focus restoration.

Alert/snackbar
- Anatomy: status icon, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: queued, visible, dismissing; alert may persist.
- Usage: place errors beside their source; use snackbar for brief completion feedback.
- Anti-patterns: critical information only in transient feedback, excessive stacking, alarmist wording.
- Accessibility: suitable live region, readable duration, text plus non-color cue.