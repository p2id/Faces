## Component inventory and states
- Button: default, hover, focus-visible, pressed, disabled, loading, destructive.
- Icon button: default, hover, focus-visible, pressed, disabled, loading.
- Text input: empty, filled, hover, focus-visible, disabled, read-only, invalid, valid.
- Select: closed, hover, focus-visible, open, selected, disabled, invalid.
- Checkbox: unchecked, checked, indeterminate, hover, focus-visible, disabled.
- Radio: unselected, selected, hover, focus-visible, disabled.
- Switch: off, on, hover, focus-visible, disabled.
- Tabs: inactive, hover, focus-visible, active, disabled.
- Card: default, hover, focus-visible, selected, disabled, loading.
- Banner: info, success, warning, error, dismissible, persistent.
- Toast: entering, visible, exiting, success, warning, error.
- Dialog: closed, opening, open, submitting, validation-error, success, closing.
- Table/list: loading, populated, empty, filtered-empty, error, refreshing, selected.
- Pagination: available, current, disabled, first-page, last-page.
- Tooltip: hidden, visible, delayed, unavailable.
- Skeleton: visible, resolved, failed.
- Navigation: expanded, collapsed, active, focus-visible, disabled.

## State rules
- Every interactive control exposes visible focus-visible and disabled states.
- Selected, pressed, invalid, and loading states use text, icon, structure, or announcement in addition to color.
- Loading preserves dimensions and prevents duplicate submission.
- Empty, filtered-empty, and error states provide a concise next action.
- Destructive actions require explicit confirmation.