Component inventory and states:
- Header/navigation: default, expanded, collapsed, active item, keyboard focus, unavailable.
- Page heading: default, loading, with status, long-title wrap.
- Search/filter: empty, focused, populated, filtered, no results, invalid, disabled.
- List/table: loading, populated, empty, no results, partial error, fully unavailable, selected, keyboard focus.
- Card/summary: default, hover, focus, selected, disabled, expanded, collapsed.
- Form field: empty, filled, focused, valid, invalid, required, disabled, read-only.
- Select/menu: closed, open, highlighted option, selected option, empty, disabled.
- Checkbox/radio: unchecked, checked, indeterminate, focused, disabled, invalid.
- Button: default, hover, pressed, focus-visible, loading, success, disabled.
- Inline alert: info, success, warning, error, dismissible, persistent.
- Dialog: closed, opening, open, validation error, submitting, success, closing.
- Progress indicator: not started, active, paused, complete, failed.
- Toast: queued, visible, paused, dismissed, action available.
- Pagination: default, previous disabled, next disabled, current page, loading.
- Footer: default, compact, expanded links.

State rules:
- Preserve entered values when validation fails.
- Provide a visible focus indicator for every interactive state.
- Announce asynchronous status changes without stealing focus.
- Disable only actions that cannot currently operate; explain why when useful.
- Error states identify the field or action and provide a recovery step.