Button
- Anatomy: label, optional leading/trailing icon, optional progress indicator.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, focus-visible, pressed, disabled, loading.
- Usage: one primary action per region; label states the result.
- Anti-patterns: vague labels, competing primary actions, unnamed icon-only controls.
- Accessibility: native button semantics, 44×44px target, loading text, non-color disabled indication.

Text field
- Anatomy: label, input, hint, error, optional leading icon.
- Variants: single-line, multiline, search, read-only.
- States: empty, filled, hover, focus, invalid, valid, disabled, read-only.
- Usage: persistent label, concise hint, inline validation.
- Anti-patterns: placeholder-only labels, silent clearing, errors shown only after submission.
- Accessibility: programmatic label, autocomplete where applicable, hint/error association, visible focus.

Select
- Anatomy: label, trigger, value, option list, hint, error.
- Variants: single-select, multi-select, compact.
- States: closed, open, selected, empty, hover, focus, invalid, disabled.
- Usage: bounded option sets with an explicit empty value when needed.
- Anti-patterns: excessive option lists, hidden selection, inconsistent keyboard behavior.
- Accessibility: name, expanded and selected states, keyboard operation, option count when useful.

Data table
- Anatomy: caption, header row, body rows, sortable headings, row actions, status region.
- Variants: compact, standard, responsive.
- States: loading, populated, sorted, selected-row, empty, error, narrow-viewport.
- Usage: align comparable values and expose sort direction.
- Anti-patterns: unreadable density, unnamed icon actions, color-only status.
- Accessibility: table semantics, headers, caption or accessible name, keyboard actions, announced sorting.

Modal
- Anatomy: backdrop, title, description, content, close action, footer actions.
- Variants: standard, confirmation, destructive, wide.
- States: closed, opening, open, closing, validation-error.
- Usage: focused decisions with clear completion and cancellation.
- Anti-patterns: nested modals, unstructured long forms, silent dismissal of entered data.
- Accessibility: dialog role, labelled title, focus containment, Escape support, focus return, inert background.

Toast
- Anatomy: status icon, message, optional action, dismiss action.
- Variants: success, info, warning, error.
- States: entering, visible, dismissing.
- Usage: brief non-blocking feedback; repeat essential information inline.
- Anti-patterns: essential instructions only in a toast, rapid stacking, unclear timeout.
- Accessibility: appropriate status or alert role, readable message, dismiss control, sufficient duration.