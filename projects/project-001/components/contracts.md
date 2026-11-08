# Section D — Component Contracts

## Button
- Anatomy: label, optional icon, optional loading indicator.
- Variants: primary, secondary, tertiary, danger, icon-only.
- States: default, hover, focus-visible, pressed, loading, disabled.
- Usage: use one primary action per region; use explicit verbs.
- Anti-patterns: vague labels, unnamed icon-only controls, competing primary actions.
- Accessibility: native button semantics, accessible name, visible focus, busy state during loading.

## Text Input
- Anatomy: label, control, hint, error or success message.
- Variants: single-line, multiline, search, compact.
- States: empty, filled, hover, focus-visible, invalid, valid, disabled, read-only.
- Usage: label every field; place instructions before entry.
- Anti-patterns: placeholder as label, color-only validation, clearing values after failure.
- Accessibility: explicit label association, described-by hint/error, suitable autocomplete, announced validation.

## Select
- Anatomy: label, trigger, option list, selected value, hint or error.
- Variants: single-select, multi-select, grouped.
- States: closed, open, focused, selected, invalid, disabled.
- Usage: use for bounded choices; provide a clear default where appropriate.
- Anti-patterns: pointer-only custom control, excessive options, hidden selected state.
- Accessibility: correct expanded and controls relationships, keyboard navigation, visible focus and selection.

## Card
- Anatomy: heading, summary, metadata, status, action area.
- Variants: standard, selectable, featured, compact.
- States: default, hover, focused, selected, loading, disabled.
- Usage: group related content; make the whole card interactive only with one clear destination.
- Anti-patterns: nested interactive controls, decorative overload, truncating essential content.
- Accessibility: semantic heading, logical order, clear name, non-color selection cue.

## Dialog
- Anatomy: title, description, content, action group, close control.
- Variants: confirmation, form, alert, informational.
- States: opening, open, submitting, validation-error, success, closing.
- Usage: reserve for consequential decisions or focused tasks.
- Anti-patterns: routine information in dialogs, unclear destructive consequences, accidental backdrop closure.
- Accessibility: named dialog, focus management, Escape support, focus restoration, announced purpose.

## Banner and Toast
- Anatomy: status indicator, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: queued, visible, exiting, dismissed.
- Usage: banners persist; toasts communicate brief non-blocking feedback.
- Anti-patterns: toast-only critical errors, premature dismissal, overlapping notices.
- Accessibility: suitable live-region priority, text status, named dismiss control.