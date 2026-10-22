# Component Contracts

## Button
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, tertiary, danger, icon-only.
- States: default, hover, focus-visible, pressed, disabled, loading.
- Usage: trigger one clearly labeled action; use one primary action per region.
- Anti-patterns: vague labels, unnamed icon-only controls, competing primary actions, unexplained disabled controls.
- Accessibility: native button semantics, keyboard activation, 44×44px target, announced loading state.

## Input
- Anatomy: label, control, hint, error, optional affordance.
- Variants: text, search, numeric, multiline, read-only.
- States: empty, filled, hover, focus-visible, invalid, valid, disabled, read-only.
- Usage: collect one clearly labeled value.
- Anti-patterns: placeholder-only labels, color-only errors, unexpected format rejection.
- Accessibility: associated label, hint, error, purpose, and format.

## Select
- Anatomy: label, trigger, value, menu, option, validation message.
- Variants: single, grouped, searchable.
- States: closed, open, hover, focus-visible, selected, invalid, disabled.
- Usage: choose from a bounded set.
- Anti-patterns: unstructured long menus, hidden selection, unsupported custom menus.
- Accessibility: exposed expanded and selected states, keyboard navigation, Escape close, focus restoration.

## Card
- Anatomy: container, heading, content, status, actions.
- Variants: summary, interactive, selectable, bordered, elevated.
- States: default, hover, focus-visible, selected, disabled.
- Usage: group related information or actions.
- Anti-patterns: unfocusable clickable cards, excessive nesting, hidden critical actions.
- Accessibility: heading hierarchy, clear target, text-based status.

## Data Table
- Anatomy: caption, headers, columns, rows, cells, actions, pagination.
- Variants: compact, standard, sortable, selectable, responsive.
- States: loading, populated, empty, filtered-empty, error, selected.
- Usage: compare structured values across consistent fields.
- Anti-patterns: missing headers, excessive columns, inaccessible row menus, layout-only tables.
- Accessibility: table semantics, scoped headers, labeled sort direction, keyboard actions, mobile alternative.

## Modal
- Anatomy: title, description, content, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, error, closing.
- Usage: interrupt only for focused decisions or required input.
- Anti-patterns: nested dialogs, unclear destructive action, lost input on dismissal.
- Accessibility: modal label, focus containment, Escape behavior, focus restoration, inert background.

## Alert and Toast
- Anatomy: status icon, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: entering, visible, paused, exiting, dismissed.
- Usage: communicate status and recovery.
- Anti-patterns: toast-only critical errors, auto-dismissed errors, motion-only notices.
- Accessibility: suitable live-region priority, persistent error recovery, keyboard dismissal.