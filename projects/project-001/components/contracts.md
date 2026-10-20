AppShell
- Anatomy: header, navigation, main, optional complementary region.
- Variants: persistent, collapsible, compact.
- States: default, loading, degraded, offline.
- Usage: provide one consistent frame and landmark structure.
- Anti-patterns: nested shells, hidden navigation without a trigger, loading layout shift.
- Accessibility: landmarks, skip link, logical focus order, responsive reflow.

Button
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, pressed, focus-visible, loading, disabled.
- Usage: use a specific verb and one primary action per region.
- Anti-patterns: vague labels, unnamed icons, low-contrast disabled text.
- Accessibility: 44px target, keyboard operation, visible focus, announced busy state.

FormField
- Anatomy: label, control, hint, error, required indicator.
- Variants: text, select, date, checkbox, toggle.
- States: default, focused, filled, valid, invalid, disabled, read-only.
- Usage: keep labels visible and place errors beside the control.
- Anti-patterns: placeholder-only labels, color-only validation, clearing values after errors.
- Accessibility: label association, hint/error description, required and invalid semantics.

Table
- Anatomy: caption, headers, rows, sortable headers, empty/error region.
- Variants: compact, standard, priority-column, stacked.
- States: loading, populated, sorted, filtered, empty, error, selected.
- Usage: use for comparable structured values.
- Anti-patterns: unreadable density, hidden sorting, inaccessible horizontal overflow.
- Accessibility: semantic table markup, header associations, sort state, selection announcement.

Modal
- Anatomy: title, description, body, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, validation-error, error, closing.
- Usage: reserve for focused decisions or short tasks.
- Anti-patterns: stacked dialogs, destructive default action, routine navigation in a modal.
- Accessibility: name, focus trap, Escape support, inert background, focus restoration.

Toast
- Anatomy: status indicator, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: visible, dismissible, timed.
- Usage: confirm nonblocking outcomes.
- Anti-patterns: essential instructions in timed messages, competing message stacks.
- Accessibility: suitable status or alert role, dismissible timing, sufficient contrast.