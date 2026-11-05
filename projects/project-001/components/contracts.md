## Button
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, tertiary, destructive, compact.
- States: default, hover, focus-visible, pressed, disabled, loading.
- Usage: one primary action per region; use verb-first labels.
- Anti-patterns: unnamed icon-only control; competing primary actions; low-contrast disabled text.
- Accessibility: native button semantics, keyboard activation, announced loading.

## Text input
- Anatomy: label, input, hint, validation message, optional icon.
- Variants: single-line, multiline, search, compact.
- States: empty, filled, focus-visible, disabled, read-only, invalid, valid.
- Usage: persistent label; concise hint; preserve entered value after validation.
- Anti-patterns: placeholder-only label; unclear format; validation with no correction guidance.
- Accessibility: programmatic label, hint/error association, autocomplete where relevant, invalid state exposed.

## Select
- Anatomy: label, trigger, value, indicator, menu, option, message.
- Variants: standard, compact, multi-select.
- States: closed, open, selected, focus-visible, disabled, invalid.
- Usage: bounded choices; include an all-values option when applicable.
- Anti-patterns: hover-only selection; ambiguous empty option; long unsearchable menu.
- Accessibility: labelled trigger, expanded and selected states, keyboard navigation, Escape close.

## Tabs
- Anatomy: tab list, tab, active indicator, panel.
- Variants: underline, contained, scrollable.
- States: inactive, hover, focus-visible, active, disabled.
- Usage: peer views with short stable labels.
- Anti-patterns: unrelated actions; excessive tabs; hidden active state.
- Accessibility: tablist/tab/tabpanel semantics and selected-controls relationships.

## Card
- Anatomy: heading, supporting text, metadata, content, action area.
- Variants: static, interactive, metric, selectable.
- States: default, hover, focus-visible, selected, disabled, loading.
- Usage: group related content; make interactive only for a singular action.
- Anti-patterns: nested interactive controls; truncated critical values; decorative excess.
- Accessibility: semantic heading, logical reading order, keyboard access, visible selection.

## Banner and toast
- Anatomy: status icon, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: visible, dismissible, entering, exiting.
- Usage: banner for persistent context; toast for brief confirmation.
- Anti-patterns: toast-only error; auto-dismissed critical message; simultaneous notice overload.
- Accessibility: suitable status or alert role; text equivalent to color and icon.

## Dialog
- Anatomy: backdrop, title, description, content, action group, close control.
- Variants: confirmation, form, alert.
- States: closed, opening, open, submitting, validation-error, success, closing.
- Usage: consequential decisions or focused entry.
- Anti-patterns: nested dialogs; unclear destructive consequence; lost entered content.
- Accessibility: labelled dialog, focus containment, safe Escape close, focus return.