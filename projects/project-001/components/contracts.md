Button
- Anatomy: label, optional leading/trailing icon, focus ring, progress indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, focus, pressed, disabled, loading.
- Usage: use one clear primary action per section; label with a verb.
- Anti-patterns: vague labels, icon-only without an accessible name, disabled without explanation, multiple competing primary actions.
- Accessibility: native button semantics; 44px target; preserve focus; announce loading and completion.

Text input
- Anatomy: label, control, hint, error, optional affordance.
- Variants: single-line, search, password-like masked value, read-only.
- States: empty, filled, focus, invalid, valid, disabled, read-only.
- Usage: keep labels visible; provide format guidance before entry.
- Anti-patterns: placeholder-only labels, silent validation, irreversible clearing.
- Accessibility: programmatic label and description; error association; input purpose and status exposed.

Select
- Anatomy: label, trigger, value, option list, selected indicator.
- Variants: single-select, grouped, compact.
- States: closed, open, selected, focus, invalid, disabled.
- Usage: use for bounded choices; show current value.
- Anti-patterns: excessive options, hidden selected value, custom behavior that breaks keyboard input.
- Accessibility: expose expanded and selected states; support Arrow keys, Enter, Escape, and type-ahead.

Dialog
- Anatomy: backdrop, title, description, content, action group, close control.
- Variants: confirmation, form, alert.
- States: closed, opening, open, submitting, success, error.
- Usage: reserve for focused decisions or short tasks.
- Anti-patterns: nested dialogs, destructive action as default, dismissal without preserving context.
- Accessibility: dialog role and accessible name; focus trap; Escape support; restore focus; no background interaction.

Toast
- Anatomy: status icon, message, optional action, dismiss control.
- Variants: neutral, positive, caution, negative.
- States: entering, visible, dismissing, persistent.
- Usage: communicate brief non-blocking status.
- Anti-patterns: critical errors only in toast, auto-dismiss of essential information, multiple simultaneous toasts.
- Accessibility: polite live region by default; assertive only for urgent failure; sufficient duration and dismiss action.