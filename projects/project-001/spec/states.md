Component inventory and states:
- App shell: default, navigation-collapsed, narrow-viewport, loading, error.
- Header: default, scrolled, action-hover, action-focus, action-disabled.
- Navigation: expanded, collapsed, selected, hover, focus, disabled.
- Breadcrumbs: default, truncated, hover, focus.
- Page heading: default, loading, with-action, without-action, error.
- Button: default, hover, focus-visible, pressed, disabled, loading, destructive.
- Icon button: default, hover, focus-visible, pressed, disabled, loading.
- Text field: empty, filled, hover, focus, invalid, valid, disabled, read-only.
- Select: closed, open, selected, empty, hover, focus, invalid, disabled.
- Tabs: default, selected, hover, focus, disabled.
- Filter bar: default, active-filters, expanded, collapsed, disabled.
- Metric card: default, hover, focus, loading, unavailable.
- Data table: default, loading, populated, sorted, selected-row, empty, error, narrow-viewport.
- List/card: default, hover, focus, selected, loading, empty, error.
- Pagination: default, current, hover, focus, disabled, single-page.
- Modal: closed, opening, open, closing, validation-error, destructive-confirmation.
- Toast: entering, success, info, warning, error, dismissing.
- Inline message: info, success, warning, error.
- Empty state: default, filtered, error-recovery.
- Divider: default, muted.

State rules:
- Disabled controls remain perceivable and explain unavailable actions when useful.
- Loading preserves layout and exposes progress text.
- Errors identify the affected field or region and provide recovery.
- Empty states distinguish no data from no matching results.
- Focus-visible treatment remains available in every interactive state.