Button
- Anatomy: label, optional icon, optional loading indicator.
- Variants: primary, secondary, quiet, destructive.
- States: default, hover, pressed, focus-visible, disabled, loading.
- Usage: use one primary action per region; label the result.
- Anti-patterns: vague labels, unnamed icon-only actions, unexplained disabled actions, competing primary actions.
- Accessibility: native button semantics; 44px target; retain accessible name while loading; show focus.

Input
- Anatomy: label, control, hint, error, optional icon.
- Variants: text, search, numeric, read-only.
- States: empty, focused, filled, invalid, disabled, read-only, loading.
- Usage: keep labels persistent; place concise guidance and errors near the control.
- Anti-patterns: placeholder-only labels, color-only errors, unexpected clearing.
- Accessibility: programmatic label and description; use aria-invalid when invalid; associate errors with the control.

Select
- Anatomy: label, trigger, value, option list, hint, error.
- Variants: single-select, grouped, compact.
- States: closed, open, selected, invalid, disabled, loading.
- Usage: use for bounded choices; provide a meaningful default or prompt.
- Anti-patterns: very long unsearchable lists, hidden options, ambiguous placeholders.
- Accessibility: expose expanded state and active option; support keyboard navigation and Escape; show focus.

Data table
- Anatomy: caption, header row, body rows, status, row actions, pagination.
- Variants: standard, compact, selectable, responsive.
- States: populated, sorted, filtered, loading, empty, error, unavailable.
- Usage: align comparable values; keep actions consistent; explain empty results.
- Anti-patterns: unlabeled icons, excessive columns, unclear merged cells.
- Accessibility: semantic table markup; sortable headers expose direction; row actions include row context.

Dialog
- Anatomy: title, description, content, action group, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, validation-error, closing.
- Usage: reserve for focused decisions and short tasks.
- Anti-patterns: nested dialogs, destructive default action, dismissal that loses entered content.
- Accessibility: modal semantics; labelled title; focus trap; Escape handling; focus restoration.