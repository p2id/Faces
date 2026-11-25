Button
- Anatomy: label, optional icon, focus ring, progress indicator.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, pressed, focus-visible, disabled, loading, success, error.
- Usage: provide one primary action per region; preserve label while loading.
- Anti-patterns: vague labels, unnamed icon-only controls, duplicate activation, color-only feedback.
- Accessibility: native button semantics, 44px target, keyboard activation, visible focus, announced busy state.

Field
- Anatomy: label, control, hint, error, optional count.
- Variants: text, search, multiline, numeric, read-only.
- States: empty, filled, focus, invalid, valid, disabled, read-only, loading.
- Usage: keep labels visible; validate near the field and on submission.
- Anti-patterns: placeholder-only labels, clearing values after errors, unexplained restrictions.
- Accessibility: associated label and description, autocomplete where applicable, linked errors, non-color validation.

Select
- Anatomy: label, trigger, value, option list, hint/error.
- Variants: single, searchable, multi-select.
- States: closed, open, highlighted, selected, invalid, disabled, loading.
- Usage: use for bounded choices; provide a clear default where appropriate.
- Anti-patterns: inaccessible custom controls, hidden options, excessive option lists.
- Accessibility: correct combobox/listbox semantics, keyboard navigation, announced selection, escape close, focus return.

Card/list row
- Anatomy: heading, description, status, metadata, action area.
- Variants: standard, selectable, actionable, compact.
- States: default, hover, selected, focus-visible, loading, disabled, error.
- Usage: maintain a clear scan order and one information hierarchy.
- Anti-patterns: nested interactive controls, truncated critical content, hover-only actions.
- Accessibility: semantic heading, complete accessible name, keyboard access, exposed status text.

Dialog
- Anatomy: title, description, content, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, success, error.
- Usage: reserve for focused decisions; offer a safe cancel action.
- Anti-patterns: stacked dialogs, destructive default action, silent value loss.
- Accessibility: modal semantics, labelled title, focus management, escape behavior, focus return, announced errors.

Toast/banner
- Anatomy: status icon or text, message, optional action, dismiss control.
- Variants: informative, positive, warning, negative.
- States: hidden, visible, dismissing.
- Usage: use banners for persistent context and toasts for transient feedback.
- Anti-patterns: important content only in a toast, auto-dismissed errors, message overload.
- Accessibility: appropriate live-region politeness, text status, labelled dismissal.