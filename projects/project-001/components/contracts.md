# Section D — Component Contracts

## Button
- Anatomy: label, optional icon, optional loading indicator.
- Variants: primary, secondary, tertiary, danger, icon-only.
- States: default, hover, focus-visible, pressed, disabled, loading, selected.
- Usage: trigger one clearly labeled action.
- Anti-patterns: vague labels, nested buttons, icon-only control without a name.
- Accessibility: native button semantics, keyboard operation, stable loading label and dimensions.

## Text Input
- Anatomy: label, field, hint, validation message, optional adornment.
- Variants: single-line, search, multiline, readonly.
- States: empty, filled, hover, focus, valid, invalid, disabled, readonly, loading.
- Usage: collect one clearly defined value.
- Anti-patterns: placeholder as label, detached errors, unlabeled adornments.
- Accessibility: associated label and description, exposed invalid state, autocomplete where applicable.

## Select
- Anatomy: label, trigger, value, option list, hint, validation message.
- Variants: single, multi-select, grouped.
- States: closed, open, empty, selected, focus, invalid, disabled, loading.
- Usage: select from a finite set.
- Anti-patterns: using for free text, hidden options, color-only status.
- Accessibility: native semantics where suitable; expose expanded, selected, disabled, and keyboard states.

## Data Table
- Anatomy: caption, headers, rows, cells, sorting, pagination.
- Variants: compact, standard, selectable, responsive-card fallback.
- States: loading, populated, sorted, filtered, selected, empty, error, paginated.
- Usage: compare structured values.
- Anti-patterns: clipped headings, ambiguous sorting, unannounced updates, unlabeled row actions.
- Accessibility: semantic headers, accessible caption, announced sorting/filter results, named row actions.

## Modal
- Anatomy: backdrop, title, description, content, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, success, error, closing.
- Usage: focused decisions or required information.
- Anti-patterns: nested modals, routine content in modals, destructive action without confirmation.
- Accessibility: dialog name, focus management, Escape support, focus restoration, usable backdrop contrast.

## Toast and Banner
- Anatomy: status indicator, message, optional action, dismissal control.
- Variants: informational, success, warning, error.
- States: hidden, visible, dismissing, persistent.
- Usage: toast for transient status; banner for persistent page-relevant status.
- Anti-patterns: critical content only in toast, auto-dismissed errors, competing notifications.
- Accessibility: suitable live-region behavior, sufficient duration, explicit dismissal, status beyond color.