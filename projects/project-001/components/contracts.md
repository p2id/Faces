Button
- Anatomy: label, optional icon, focus ring, loading indicator.
- Variants: primary, secondary, tertiary, danger.
- States: default, hover, focus-visible, active, disabled, loading, confirmation.
- Usage: use for actions; start labels with verbs; provide one primary action per context.
- Anti-patterns: vague labels, unlabeled icon-only controls, competing primary actions, unexplained disabled actions.
- Accessibility: native button semantics, 44px target, keyboard activation, announced loading state.

Text input
- Anatomy: label, input, hint, error, optional affordance.
- Variants: standard, compact, search.
- States: empty, filled, hover, focus, invalid, valid, disabled, readonly.
- Usage: keep labels visible and provide guidance before entry.
- Anti-patterns: placeholder-only labels, silent validation, clipped essential values.
- Accessibility: programmatic label, appropriate autocomplete, error association, visible focus.

Select
- Anatomy: label, trigger, value, menu, option, status.
- Variants: standard, compact, multi-select.
- States: closed, hover, focus, open, selected, invalid, disabled.
- Usage: use for bounded choices; provide a meaningful default when appropriate.
- Anti-patterns: use for long searchable collections, hide selected values, use color-only options.
- Accessibility: prefer native select; expose expanded, selected, disabled, and invalid semantics.

Checkbox
- Anatomy: box, label, description, error.
- Variants: standard, indeterminate.
- States: unchecked, checked, indeterminate, focus-visible, disabled, invalid.
- Usage: use for independent or multiple choices.
- Anti-patterns: use for mutually exclusive choices, omit clickable labels, use ambiguous grouping.
- Accessibility: expose checked state, group related controls, provide 44px target.

Card
- Anatomy: container, heading, supporting text, metadata, action region.
- Variants: static, interactive, selected, metric.
- States: default, hover, focus-visible, selected, disabled.
- Usage: group related information and keep actions predictable.
- Anti-patterns: multiple nested click targets, excessive nesting, low-contrast metadata.
- Accessibility: maintain heading hierarchy; use one semantic control for interactive cards.

Dialog
- Anatomy: backdrop, dialog, title, content, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, error, closing.
- Usage: interrupt only for focused decisions or short tasks.
- Anti-patterns: routine browsing in dialogs, stacked dialogs, destructive actions without context.
- Accessibility: accessible name, focus containment, Escape handling, background inertness, focus return.

Toast/alert
- Anatomy: status label, message, optional action, dismiss control.
- Variants: informational, success, warning, error.
- States: visible, dismissing, persistent.
- Usage: confirm completed actions or report recoverable issues.
- Anti-patterns: critical information only in a transient toast, unclear cause, excessive stacking.
- Accessibility: suitable live-region politeness, readable duration, dismissal control, status beyond color.