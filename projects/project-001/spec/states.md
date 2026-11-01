Component inventory and complete states:
- Header/navigation: default, compact, expanded, active, focus-visible, disabled.
- Page title: default, supporting-text, loading, error.
- Search field: empty, focused, filled, loading, no-results, invalid, disabled.
- Filter/select: closed, open, selected, keyboard-highlighted, invalid, disabled.
- Button: default, hover, pressed, focus-visible, disabled, loading, success, error.
- Content card: default, hover, pressed, selected, focus-visible, loading, unavailable.
- Detail panel: default, loading, empty, error, read-only.
- Text field: empty, focused, filled, valid, invalid, disabled, read-only.
- Text area: empty, focused, filled, valid, invalid, disabled, read-only.
- Checkbox/toggle: unchecked, checked, indeterminate, focused, invalid, disabled.
- Dialog: closed, opening, open, submitting, success, error.
- Banner/toast: info, success, warning, error, dismissing, persistent.
- Progress indicator: determinate, indeterminate, complete, error.
- Empty state: default, filtered, error, action-enabled.
- Pagination: default, current, previous-disabled, next-disabled, loading.
- Divider: default, strong, hidden-at-compact.

State rules:
- Focus-visible has a persistent high-contrast outline.
- Disabled controls remain legible and non-interactive.
- Loading preserves layout and prevents duplicate submission.
- Errors identify the affected control and provide recovery guidance.
- Success feedback is brief unless confirmation is required.
- Open dialogs trap focus, support Escape, and restore focus on close.