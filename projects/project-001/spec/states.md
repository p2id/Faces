Component inventory:
- Button: default, hover, focus-visible, active, disabled, loading, confirmation
- Icon button: default, hover, focus-visible, active, disabled, loading
- Text input: empty, filled, hover, focus, invalid, valid, disabled, readonly
- Select: closed, hover, focus, open, selected, invalid, disabled
- Checkbox: unchecked, checked, indeterminate, focus-visible, disabled
- Radio group: unselected, selected, focus-visible, disabled, invalid
- Tabs: inactive, hover, focus-visible, active, disabled
- Card: default, hover, focus-visible, selected, disabled
- Badge: neutral, informational, positive, warning, negative
- List row: default, hover, focus-visible, selected, disabled, loading
- Menu: closed, open, focused, selected, disabled
- Pagination: default, hover, focus-visible, current, disabled
- Dialog: closed, opening, open, submitting, error, closing
- Toast/alert: informational, success, warning, error, dismissing
- Tooltip: hidden, delayed, visible
- Skeleton: loading, loaded, error
- Empty state: visible, action-ready
- Progress indicator: idle, active, complete, error

State rules:
- Interactive states provide visible focus, hover or active feedback, and disabled treatment.
- Loading prevents duplicate activation and exposes text or status semantics.
- Errors identify the issue and provide recovery guidance.
- Empty states explain the condition and provide a relevant next action.
- Destructive actions require clear confirmation.
- Selection and status remain distinguishable without color alone.