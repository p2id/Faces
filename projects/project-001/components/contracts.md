Button
- Anatomy: label, optional icon, focus ring, progress indicator.
- Variants: primary, secondary, tertiary, destructive.
- States: default, hover, pressed, focus-visible, disabled, loading, success, error.
- Usage: one primary action per region; label states the result, such as “Save changes”.
- Anti-patterns: unlabeled icon-only control, vague “Submit”, unexplained disabled state, competing primary actions.
- Accessibility: native button semantics, keyboard activation, 44px target, visible focus, announced busy state.

Text field
- Anatomy: label, control, hint, required marker, error message.
- Variants: single-line, multiline, compact, read-only.
- States: empty, filled, hover, focus, invalid, valid, disabled, read-only.
- Usage: persistent label; hint states format; error states correction.
- Anti-patterns: placeholder-only label, color-only validation, clearing content after error.
- Accessibility: programmatic label and descriptions, appropriate autocomplete, associated error, logical tab order.

Card/list row
- Anatomy: heading, supporting text, metadata, status, action area.
- Variants: static, selectable, actionable, loading.
- States: default, hover, pressed, selected, focus-visible, disabled, loading, error.
- Usage: provide one clear destination or action and preserve content hierarchy.
- Anti-patterns: ambiguous nested controls, excessive decoration, clipped content.
- Accessibility: appropriate list and heading semantics; focus the actionable element; expose selected state.

Dialog
- Anatomy: title, description, content, primary action, secondary action, close control.
- Variants: confirmation, form, informational.
- States: opening, open, closing, blocked, error.
- Usage: reserve for focused tasks; preserve context and entered values.
- Anti-patterns: unexpected interruption, missing close path, destructive default action.
- Accessibility: modal semantics, accessible name, focus trap, Escape handling, focus restoration, inert background.

Alert/toast
- Anatomy: status icon, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: entering, visible, exiting, persistent.
- Usage: inline alerts for context; toasts for brief noncritical confirmation; persistent errors for critical information.
- Anti-patterns: critical content only in a toast, stacked interruptions, unexplained icon.
- Accessibility: suitable live-region politeness, text equivalent, dismissible control, adequate duration.