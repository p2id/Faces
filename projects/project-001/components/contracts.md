Button
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, focus-visible, pressed, disabled, loading.
- Usage: one primary action per region; use verb-led labels.
- Anti-patterns: vague labels, competing primaries, unexplained disabled state, unlabeled icon-only action.
- Accessibility: native button semantics, keyboard activation, 44px target, exposed busy state, persistent accessible name.

Text input
- Anatomy: label, input, hint, error, optional icon.
- Variants: text, search, date, numeric.
- States: empty, filled, hover, focus-visible, invalid, valid, disabled, read-only.
- Usage: provide a visible label and concise guidance.
- Anti-patterns: placeholder-only labels, clearing entered values, color-only errors.
- Accessibility: associated label and description, required and invalid states, announced errors, suitable autocomplete.

Select
- Anatomy: label, trigger, value, indicator, menu, option, helper or error.
- Variants: single-select, grouped-select, compact.
- States: closed, open, selected, focus-visible, invalid, disabled.
- Usage: use for bounded choices and show the current value.
- Anti-patterns: excessive options, hidden selection, inconsistent keyboard behavior.
- Accessibility: prefer native select; otherwise provide combobox/listbox semantics and arrow-key navigation.

Table
- Anatomy: accessible name, header row, sortable headers, body rows, status cells, pagination.
- Variants: compact, comfortable, selectable, responsive.
- States: loading, populated, sorted, filtered, selected-row, empty, error, overflow.
- Usage: keep headings stable and row actions predictable.
- Anti-patterns: unlabeled icon columns, hover-only actions, inaccessible truncation, color-only meaning.
- Accessibility: semantic table markup, caption or name, announced sort direction, preserved headers, small-screen equivalent.

Modal
- Anatomy: backdrop, title, body, close action, action group.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, success, error, closing.
- Usage: reserve for focused decisions and state consequences clearly.
- Anti-patterns: nested modals, destructive-only emphasis, dismissal that loses input.
- Accessibility: dialog name, focus transfer and restoration, focus containment, Escape handling, labeled actions.

Alert and toast
- Anatomy: status icon, message, optional action, dismiss action.
- Variants: info, success, warning, error.
- States: queued, visible, persistent, dismissible, exiting.
- Usage: inline alerts for context; toasts for transient confirmation.
- Anti-patterns: critical errors only in toasts, auto-dismissed important content, repeated duplicates.
- Accessibility: appropriate status or alert semantics, non-color cues, labeled dismissal, non-disruptive announcements.