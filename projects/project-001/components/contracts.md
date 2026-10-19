Button
- Anatomy: label, optional leading icon, optional trailing icon, focus ring.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, pressed, focus-visible, loading, success, disabled.
- Usage: one primary action per region; use verb-led labels such as “Continue”.
- Anti-patterns: vague labels, multiple competing primary buttons, icon-only without a name, disabled without explanation.
- Accessibility: native button semantics, 44px minimum target, accessible loading status, visible focus.

Form field
- Anatomy: label, control, hint, required indicator, error message.
- Variants: text, search, select, checkbox, radio, textarea.
- States: empty, filled, focused, valid, invalid, disabled, read-only.
- Usage: keep labels persistent; show guidance before input and correction after error.
- Anti-patterns: placeholder as label, color-only validation, clearing valid input on error.
- Accessibility: programmatic label and description, required state, error association, keyboard operation.

Alert
- Anatomy: status icon, title or message, optional action, optional dismiss control.
- Variants: info, success, warning, error, inline, toast.
- States: visible, dismissed, persistent, action available.
- Usage: place near the affected content; use plain recovery guidance.
- Anti-patterns: alarming language, stacking duplicates, auto-dismissal of critical errors.
- Accessibility: appropriate live-region behavior, text plus non-color cue, dismiss control with name.

Dialog
- Anatomy: title, description, content, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, validation error, success, closing.
- Usage: reserve for focused decisions; make the safest action clear.
- Anti-patterns: nested dialogs, hidden close control, destructive action as default, excessive content.
- Accessibility: modal semantics, labelled title, trapped focus, Escape support, focus restoration.