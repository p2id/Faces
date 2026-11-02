Component contracts:
- Page shell
  - Anatomy: skip link, header, navigation, main, optional aside, footer, feedback region.
  - Variants: desktop, tablet, mobile, constrained.
  - States: loading, ready, empty, error, offline.
  - Usage: provide stable landmarks and preserve content order.
  - Anti-patterns: nested main landmarks, clipped content, layout shift.
  - Accessibility: landmark labels, skip link, logical heading order.

- Button
  - Anatomy: label, optional icon, optional progress indicator.
  - Variants: primary, secondary, tertiary, destructive, icon-only.
  - States: default, hover, focus-visible, pressed, disabled, loading, success.
  - Usage: trigger an action or explicitly confirmed outcome.
  - Anti-patterns: vague labels, unnamed icon-only controls, disabled-as-validation.
  - Accessibility: native button semantics, 44px target, loading announcement.

- Field
  - Anatomy: label, control, hint, error, required indicator.
  - Variants: input, textarea, select, combobox, date.
  - States: empty, filled, focus, invalid, valid, disabled, readonly.
  - Usage: keep labels visible and associate messages.
  - Anti-patterns: placeholder-only labels, color-only errors, silent validation.
  - Accessibility: label, description, error association, applicable autocomplete.

- Dialog
  - Anatomy: backdrop, title, description, content, actions, close control.
  - Variants: confirmation, form, information, destructive.
  - States: closed, opening, open, submitting, success, error.
  - Usage: interrupt only for focused decisions or required input.
  - Anti-patterns: stacked dialogs, lost input, hidden close control.
  - Accessibility: dialog name, focus trap, escape behavior, focus restoration.

- Data list
  - Anatomy: heading, controls, list or table, row actions, pagination.
  - Variants: list, grid, table, compact.
  - States: loading, populated, empty, filtered-empty, error, selected.
  - Usage: show result count and recovery paths.
  - Anti-patterns: inaccessible custom grids, ambiguous row actions, unbounded scrolling.
  - Accessibility: correct list/table semantics and keyboard row actions.

- Feedback
  - Anatomy: semantic icon, title, message, optional action, dismiss control.
  - Variants: info, success, warning, error, toast, inline.
  - States: entering, visible, dismissing, persistent.
  - Usage: communicate status, consequence, and next step.
  - Anti-patterns: auto-dismissed critical errors, technical-only text, alert overload.
  - Accessibility: suitable live-region priority, contrast, non-color cue.