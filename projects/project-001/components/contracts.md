Button
- Anatomy: label, optional icon, loading indicator.
- Variants: primary, secondary, quiet, destructive.
- States: default, hover, pressed, focus-visible, disabled, loading, success, error.
- Usage: use one primary action per region and verb-led labels.
- Anti-patterns: unlabeled icon-only controls, vague labels, disabled-only error explanation.
- Accessibility: native button semantics, 44px target, visible focus, announced loading and completion.

Field
- Anatomy: label, control, hint, error, optional count.
- Variants: input, text area, select, checkbox.
- States: empty, focused, filled, valid, invalid, disabled, read-only.
- Usage: keep labels visible; provide guidance before entry and recovery text after errors.
- Anti-patterns: placeholder-only labels, color-only validation, clearing valid values after errors.
- Accessibility: explicit label association, hint/error description, keyboard operation, applicable autocomplete.

Dialog
- Anatomy: title, description, content, action row, close control.
- Variants: alert, confirmation, form.
- States: closed, opening, open, submitting, success, error.
- Usage: interrupt only for consequential decisions or focused tasks.
- Anti-patterns: nested dialogs, destructive default action, accidental close with unsaved changes.
- Accessibility: labelled dialog, focus trap, Escape support, focus restoration, status announcement.

ContentCard
- Anatomy: title, summary, metadata, optional status, action.
- Variants: compact, standard, featured.
- States: default, hover, pressed, selected, loading, unavailable.
- Usage: keep the target coherent and expose relevant metadata only.
- Anti-patterns: competing primary actions, truncating essential text, unnamed click targets.
- Accessibility: semantic heading, descriptive control name, visible selection, non-color status.

Banner/Toast
- Anatomy: status icon, message, optional action, dismiss control.
- Variants: info, success, warning, error.
- States: visible, dismissing, persistent.
- Usage: place field errors inline; use toast for brief non-blocking feedback.
- Anti-patterns: timed critical information, excessive stacking, vague failure text.
- Accessibility: appropriate status or alert semantics, readable message, keyboard dismissal.