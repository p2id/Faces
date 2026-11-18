Component inventory and complete state sets
- Button: default, hover, focus-visible, pressed, disabled, loading, success, destructive.
- Input: empty, filled, hover, focus, invalid, valid, disabled, read-only.
- Select: closed, hover, focus, open, selected, invalid, disabled.
- Checkbox: unchecked, checked, indeterminate, hover, focus-visible, disabled, invalid.
- Radio: unselected, selected, hover, focus-visible, disabled, invalid.
- Tabs: inactive, hover, focus-visible, active, disabled.
- Navigation item: inactive, hover, focus-visible, active, disabled.
- Card: default, hover, focus-visible, selected, disabled.
- Table: loading, populated, sorted, filtered, row-hover, row-selected, empty, error.
- Pagination: default, current, hover, focus-visible, disabled, loading.
- Dialog: closed, opening, open, submitting, success, error, closing.
- Popover: closed, opening, open, closing.
- Tooltip: hidden, delayed, visible, dismissed.
- Toast: hidden, visible, success, info, warning, error, dismissing.
- Banner: informational, success, warning, error, dismissible.
- Badge: neutral, informative, success, warning, error.
- Date range picker: closed, open, partial, complete, invalid, disabled.
- Skeleton: visible, resolved, failed.
- Empty state: default, filtered.
- Error state: recoverable, persistent, retrying.
- Spinner: hidden, active, paused.
- Divider: default, emphasized, vertical.

State requirements
- Every interactive component has visible focus-visible, disabled, and loading behavior where applicable.
- Invalid states include adjacent explanatory text.
- Selected states use text, shape, or icon in addition to color.
- Loading preserves layout and communicates progress.
- Success and error states communicate completion and recovery.