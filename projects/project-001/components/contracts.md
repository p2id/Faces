Button
- Anatomy: label, optional leading or trailing icon, focus ring.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, pressed, focus-visible, loading, success, disabled.
- Usage: one primary action per region; use labels such as “Continue”.
- Anti-patterns: vague labels, competing primary actions, unnamed icon-only controls, unexplained disabled state.
- Accessibility: native button semantics, 44px target, visible focus, announced loading state.

Form field
- Anatomy: label, control, hint, required indicator, error message.
- Variants: text, search, select, checkbox, radio, textarea.
- States: empty, filled, focused, valid, invalid, disabled, read-only.
- Usage: keep labels persistent; show guidance before input and correction after error.
- Anti-patterns: placeholder-only labels, color-only validation, clearing recoverable input.
- Accessibility: associated label and description, required state, error association, keyboard support.

Alert
- Anatomy: status cue, message, optional title, action, dismiss control.
- Variants: info, success, warning, error, inline, toast.
- States: visible, dismissed, persistent, action-available.
- Usage: place beside affected content and provide recovery guidance.
- Anti-patterns: alarming language, duplicate alerts, auto-dismissed critical errors.
- Accessibility: suitable live-region behavior, text plus non-color cue, named dismiss control.

Dialog
- Anatomy: title, description, content, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, validation-error, success, closing.
- Usage: reserve for focused decisions; make the safest action clear.
- Anti-patterns: nested dialogs, hidden close control, destructive default, excessive content.
- Accessibility: modal semantics, labelled title, focus trap, Escape support, focus restoration.