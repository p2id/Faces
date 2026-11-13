Button
- Anatomy: label, optional icon, focus ring, loading indicator.
- Variants: primary, secondary, tertiary, destructive.
- States: default, hover, focus-visible, pressed, disabled, loading, success.
- Usage: use one primary action; label the outcome, such as “Apply changes”.
- Anti-patterns: unnamed icon-only control, vague “Submit”, competing primary actions, unexplained disabled state.
- Accessibility: native button semantics, keyboard activation, 44px target, announced busy state.

Field
- Anatomy: label, control, helper text, validation text.
- Variants: text, select, checkbox, radio, toggle.
- States: empty, filled, focused, valid, invalid, disabled, read-only, loading.
- Usage: keep labels persistent and corrective guidance adjacent.
- Anti-patterns: placeholder-only labels, color-only errors, detached validation text.
- Accessibility: programmatic label, description and error association, logical tab order.

Panel
- Anatomy: heading, description, content, actions.
- Variants: outlined, raised, compact, interactive.
- States: default, hover, focus-visible, selected, disabled, loading, error, empty.
- Usage: group related content with clear hierarchy.
- Anti-patterns: excessive nesting, elevation-only grouping, hidden required actions.
- Accessibility: meaningful heading level, logical landmark, no unnecessary focus trap.

Dialog
- Anatomy: title, description, content, actions, close control.
- Variants: alert, confirmation, form.
- States: closed, opening, open, submitting, success, error.
- Usage: reserve for focused decisions and state consequences clearly.
- Anti-patterns: unexpected opening, destructive default action, click-outside-only dismissal.
- Accessibility: dialog semantics, labelled title, focus containment, Escape handling, focus restoration.

Status message
- Anatomy: status text, optional icon, action, dismiss control.
- Variants: info, success, warning, error.
- States: hidden, visible, dismissible, action-required.
- Usage: state what happened and the next available action.
- Anti-patterns: auto-dismissed critical errors, vague failure copy, duplicate alerts.
- Accessibility: suitable live-region priority, text alternatives, sufficient display time.