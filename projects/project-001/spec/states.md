# Section C — Component Inventory and States

- App shell: loading, ready, offline, degraded, error.
- Navigation: default, active, hover, focus-visible, expanded, collapsed, disabled.
- Button: default, hover, focus-visible, pressed, loading, disabled, destructive, success.
- Link: default, hover, focus-visible, visited, disabled.
- Text input: empty, filled, hover, focus-visible, invalid, valid, disabled, read-only.
- Search field: empty, typing, populated, loading, no-results, invalid, disabled.
- Select: closed, open, focused, selected, invalid, disabled.
- Checkbox: unchecked, checked, indeterminate, focused, disabled.
- Radio group: unselected, selected, focused, invalid, disabled.
- Toggle: off, on, focused, disabled, pending.
- Tabs: inactive, active, hover, focus-visible, disabled.
- Filter chip: inactive, active, removable, focused, disabled.
- Card: default, hover, focused, selected, loading, disabled.
- Data row: default, hover, focused, selected, expanded, loading, disabled.
- Badge: neutral, informative, positive, warning, negative.
- Banner: informative, success, warning, error, dismissible.
- Toast: queued, visible, exiting, dismissed.
- Dialog: opening, open, submitting, validation-error, success, closing.
- Detail panel: closed, opening, open, loading, error, saving, success, closing.
- Pagination: default, current, hover, focus-visible, disabled.
- Skeleton: visible, resolved, failed.
- Empty state: no-content, no-results, filtered-empty.
- Error state: recoverable, blocking, offline.
- Tooltip: hidden, visible, delayed, dismissed.

## State Rules
- Every interactive state has a keyboard-accessible equivalent.
- Loading preserves structure and communicates progress.
- Errors state impact and recovery action.
- Disabled controls remain legible.
- Destructive actions require explicit confirmation.