# Component Contracts

## Button
- Anatomy: label, optional icon, optional loading indicator.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, pressed, focus-visible, disabled, loading, selected.
- Usage: use one primary action per region; use specific verbs.
- Anti-patterns: vague labels, competing primary actions, unlabeled icon-only controls, unexplained disabled actions.
- Accessibility: native button semantics, 44px target, visible focus, announced busy state.

## Field
- Anatomy: label, control, hint, required marker, error.
- Variants: input, textarea, select, checkbox, radio, switch.
- States: empty, filled, focused, invalid, valid, disabled, read-only.
- Usage: label every control; explain constraints; place errors near controls.
- Anti-patterns: placeholder-only labels, color-only errors, premature validation.
- Accessibility: programmatic label and description, exposed required/error state, keyboard operation.

## Card
- Anatomy: container, heading, supporting text, content, status, optional action.
- Variants: informational, interactive, selected, compact.
- States: default, hover, focus-visible, selected, disabled, loading.
- Usage: group related content; make interaction explicit.
- Anti-patterns: unclear nested interactions, decorative density, truncated essential content.
- Accessibility: semantic heading, logical order, named action, visible selection.

## Collection
- Anatomy: heading, controls, count, headers, items, pagination, feedback.
- Variants: table, list, grouped list, dense collection.
- States: loading, empty, populated, filtered, sorted, selected, error.
- Usage: expose labels, filters, sort status, and result count.
- Anti-patterns: clipped essential data, hover-only actions, unlabeled icons.
- Accessibility: native semantics, announced sort/filter changes, keyboard actions.

## Dialog
- Anatomy: title, description, content, close control, actions.
- Variants: modal, confirmation, form, drawer.
- States: closed, opening, open, submitting, validation-error, success, error.
- Usage: reserve for focused tasks; state consequences clearly.
- Anti-patterns: unexpected opening, nested dialogs, destructive default action.
- Accessibility: labelled container, focus trap, Escape support, focus restoration, inert background.

## Feedback
- Anatomy: status symbol, message, detail, action, dismiss control.
- Variants: inline, alert, toast, progress, empty state.
- States: informative, positive, caution, negative, persistent, dismissible.
- Usage: explain outcome and next action.
- Anti-patterns: vague messages, auto-dismissed critical errors, color-only status.
- Accessibility: appropriate live-region priority, readable contrast, accessible dismissal.