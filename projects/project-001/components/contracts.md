Global contract:
- Anatomy: container, heading or label, content, optional description, action area, status region.
- Variants: default, compact, emphasized, disabled, responsive.
- States: loading, empty, populated, success, warning, error, unavailable.
- Usage: compose with semantic tokens; maintain hierarchy; preserve content during transitions.
- Anti-patterns: ambiguous labels, nested interactive controls, color-only status, layout shift, hidden primary action.
- Accessibility: semantic HTML, keyboard operation, visible focus, reflow, announced status changes.

Form control contract:
- Anatomy: label, control, hint, validation message, optional required indicator.
- Variants: text, search, select, checkbox, radio, switch; single or grouped.
- States: empty, filled, focused, disabled, read-only, invalid, valid, loading.
- Usage: associate labels and messages programmatically; validate near the control; retain values.
- Anti-patterns: placeholder as label, premature errors, unexplained disabled control, unlabeled icon.
- Accessibility: native semantics, 44px target, name/value/state exposure, error association.

Action contract:
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, pressed, focus-visible, disabled, loading, success, error.
- Usage: use one primary action per region; use verbs; explain disabled actions where useful.
- Anti-patterns: competing primary actions, vague labels, changing loading width, unnamed icon-only action.
- Accessibility: keyboard activation, visible focus, busy state, accessible name, non-color status.

Collection contract:
- Anatomy: heading, filters, labels, items, empty/loading/error region, pagination.
- Variants: table, grid, list, compact, selectable.
- States: loading, empty, filtered-empty, populated, selected, sorted, error.
- Usage: show count and context; preserve filters; provide recovery action.
- Anti-patterns: unreadable density, sort without state, pagination without current-page indication.
- Accessibility: headings, labels, item relationships, announced updates, keyboard-operable sorting and selection.

Overlay and feedback contract:
- Anatomy: title, message, content, action area, close control, status role.
- Variants: modal, toast, tooltip, inline message.
- States: opening, open, submitting, success, warning, error, closing.
- Usage: reserve overlays for focused decisions; keep feedback near its cause.
- Anti-patterns: modal for simple information, toast for required action, auto-dismissed critical error, tooltip-only instruction.
- Accessibility: focus management, escape behavior where appropriate, live-region discipline, contrast, reduced-motion alternative.