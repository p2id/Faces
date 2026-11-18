Button
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, focus-visible, pressed, disabled, loading, success, destructive.
- Usage: use explicit verbs; limit each region to one primary action.
- Anti-patterns: vague labels, unnamed icons, unexplained disabled actions, competing primaries.
- Accessibility: native button semantics, accessible name, visible focus, 44×44px target, announced loading.

Input
- Anatomy: label, field, hint, error, optional icon.
- Variants: text, search, date, numeric.
- States: empty, filled, hover, focus, invalid, valid, disabled, read-only.
- Usage: persistent visible label; preserve values on error.
- Anti-patterns: placeholder-only labels, color-only validation, unexpected clearing.
- Accessibility: associated label, purpose/autocomplete, error relationship, keyboard support.

Select
- Anatomy: label, trigger, value, listbox, option, hint/error.
- Variants: single, grouped, compact.
- States: closed, hover, focus, open, selected, invalid, disabled.
- Usage: bounded choices; include an explicit unfiltered option.
- Anti-patterns: excessive options, nested scrolling, silent selection changes.
- Accessibility: correct combobox/listbox semantics, keyboard navigation, active option, Escape handling.

Table
- Anatomy: caption, headers, sortable headers, rows, status, actions.
- Variants: compact, comfortable, responsive overflow.
- States: loading, populated, sorted, filtered, row-hover, row-selected, empty, error.
- Usage: comparable records with stable columns.
- Anti-patterns: hidden relationships, unnamed row actions, loading layout shift.
- Accessibility: caption or name, header associations, announced sort direction, named actions, mobile overflow strategy.

Dialog
- Anatomy: title, description, content, close action, footer actions.
- Variants: confirmation, form, alert.
- States: closed, opening, open, submitting, success, error, closing.
- Usage: focused decisions or short tasks; one primary action.
- Anti-patterns: nested dialogs, destructive default focus, context loss on dismissal.
- Accessibility: modal semantics, accessible name, focus containment, Escape behavior, focus restoration.

Toast and banner
- Anatomy: status indicator, message, optional action, dismiss action.
- Variants: info, success, warning, error.
- States: hidden, visible, dismissing.
- Usage: toast for transient confirmation; banner for persistent context or recovery.
- Anti-patterns: critical information only in toast, auto-dismissed errors, duplicate messages.
- Accessibility: suitable live-region priority, text alternative, keyboard dismissal, sufficient duration.

Tabs
- Anatomy: tab list, tab, active indicator, associated panel.
- Variants: standard, scrollable.
- States: inactive, hover, focus-visible, active, disabled.
- Usage: peer views with stable context.
- Anti-patterns: unrelated actions, excessive tabs, color-only active state.
- Accessibility: tablist relationships, arrow-key navigation, selected state, logical focus order.