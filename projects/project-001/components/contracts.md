Button
- Anatomy: label, optional icon, focus ring, progress indicator.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, focus-visible, pressed, disabled, loading, success.
- Usage: use one primary action per region; label the result, such as “Create item”.
- Anti-patterns: vague labels, unnamed icon-only controls, unexplained disabled actions.
- Accessibility: native button semantics, preserved label while loading, exposed busy state.

TextInput
- Anatomy: label, field, hint, error, optional affordance.
- Variants: text, search, compact, read-only.
- States: empty, filled, focus, disabled, read-only, invalid, valid, loading.
- Usage: provide a persistent label and concise hint.
- Anti-patterns: placeholder-only labels, delayed error context, clearing entered values.
- Accessibility: programmatic label and description; associated error; keyboard support.

Select
- Anatomy: label, trigger, value, indicator, listbox, options.
- Variants: single, grouped, compact.
- States: closed, open, focused, selected, disabled, invalid, loading.
- Usage: use for bounded choices and show the current value.
- Anti-patterns: excessive options, nested scrolling, unannounced value changes.
- Accessibility: correct combobox/listbox semantics, keyboard navigation, expanded state.

Dialog
- Anatomy: title, description, content, close control, action group.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, success, error, closing.
- Usage: reserve for focused tasks or consequential decisions.
- Anti-patterns: stacked dialogs, dismiss-only critical content, escaped focus.
- Accessibility: labeled modal, focus containment, safe Escape dismissal, focus restoration.

Card
- Anatomy: container, heading, metadata, status, action area.
- Variants: content, selectable, interactive, loading.
- States: default, hover, focus, selected, disabled, loading, error.
- Usage: group related information; make the whole card interactive only when needed.
- Anti-patterns: nested interactive controls, ambiguous click area, decorative text-as-action.
- Accessibility: logical heading, clear action name, keyboard access when interactive.

Alert
- Anatomy: tone indicator, title, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: visible, dismissible, persistent.
- Usage: explain status and next step near affected content.
- Anti-patterns: color-only messaging, auto-dismissed errors, vague messages.
- Accessibility: suitable status or alert role, readable contrast, named actions.