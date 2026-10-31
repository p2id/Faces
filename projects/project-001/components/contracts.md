# Component Contracts

## Button
- Anatomy: label, optional icon, optional loading indicator.
- Variants: primary, secondary, tertiary, destructive.
- States: default, hover, pressed, focus-visible, disabled, loading.
- Usage: use concise verb-first labels; limit primary actions per region.
- Anti-patterns: unlabeled icon-only control; competing primary actions; disabled-looking active control.
- Accessibility: native button semantics, keyboard activation, and announced busy state.

## Text Field
- Anatomy: label, input, hint, error, optional count.
- Variants: single-line, multiline, search.
- States: empty, filled, focused, disabled, read-only, invalid, valid.
- Usage: keep labels persistent and guidance concise.
- Anti-patterns: placeholder as sole label; silent validation; unexplained format rules.
- Accessibility: programmatic label, hint/error association, appropriate autocomplete.

## Select and Date Picker
- Anatomy: label, trigger or input, popup, options or calendar, hint, error.
- Variants: single-select, multi-select, date, date range.
- States: closed, open, selected, disabled, invalid, loading.
- Usage: use select for finite options; retain a readable date input.
- Anti-patterns: keyboard-inaccessible popup; ambiguous date format; excessive option lists.
- Accessibility: correct popup semantics, focused option, selected state, Escape handling.

## List/Table
- Anatomy: caption, toolbar, headers, rows, cells, selection, pagination.
- Variants: table, compact table, card list.
- States: loading, populated, sorted, filtered, selected, empty, error.
- Usage: expose active filters and sort direction.
- Anti-patterns: unreadable density; hover-only selection cue; hidden overflow actions.
- Accessibility: header associations, keyboard actions, and selection announcements.

## Modal
- Anatomy: title, description, content, actions, close control.
- Variants: confirmation, form, informational.
- States: opening, open, submitting, validation-error, closing.
- Usage: reserve for focused decisions and short tasks.
- Anti-patterns: nested modals; unexplained destructive action; silent data loss.
- Accessibility: dialog name, focus management, Escape behavior, focus restoration.

## Alert/Toast
- Anatomy: status label or icon, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: entering, visible, dismissing, persistent.
- Usage: use alerts for conditions and toasts for completed low-risk actions.
- Anti-patterns: toast-only critical errors; timed required instructions; color-only status.
- Accessibility: appropriate role, readable message, non-color indication, polite announcement.