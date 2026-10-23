Button
- Anatomy: label, optional icon, focus ring, loading indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, focus-visible, active, disabled, loading, success, error.
- Usage: use for actions with concise imperative labels.
- Anti-patterns: multiple competing primary actions; unexplained disabled controls; unnamed icon-only controls.
- Accessibility: native button semantics, keyboard activation, 44px target, visible focus, announced status.

Input
- Anatomy: label, control, hint, error or success message, optional affordance.
- Variants: text, search, numeric, multiline.
- States: empty, filled, hover, focus-visible, disabled, read-only, invalid, valid, loading.
- Usage: provide a persistent label and concise instructions.
- Anti-patterns: placeholder-only labels; unexpected clearing; color-only errors.
- Accessibility: programmatic label and description, associated errors, logical focus order.

Select
- Anatomy: label, trigger, value, indicator, option list, status.
- Variants: standard, compact, multi-select.
- States: closed, open, hover, focus-visible, disabled, invalid, loading.
- Usage: use for bounded options and show the current value.
- Anti-patterns: long unstructured content; hidden selection; open-on-focus behavior.
- Accessibility: expose expanded and selected states; support arrows and Escape.

Dialog
- Anatomy: backdrop, title, description, content, actions, close control.
- Variants: standard, confirmation, form, destructive.
- States: closed, opening, open, submitting, success, error, closing.
- Usage: reserve for focused tasks requiring interruption.
- Anti-patterns: nested dialogs; essential content only in a dialog; missing cancel path.
- Accessibility: modal semantics, accessible name, focus trap, Escape, focus restoration, announced errors.

Table
- Anatomy: caption, header row, body rows, status, pagination.
- Variants: compact, standard, selectable, responsive.
- States: loading, empty, populated, row-hover, row-selected, error.
- Usage: use for comparable values with consistent columns.
- Anti-patterns: paragraph-heavy cells; critical values hidden by truncation; hover-only actions.
- Accessibility: semantic table structure, accessible name, identified sortable headers, announced selection, responsive alternative.