Component inventory and states:
- Header/navigation: default, expanded, collapsed, active, focus-visible, unavailable.
- Page heading: default, loading, with-status, long-title-wrap.
- Search/filter: empty, focused, populated, filtered, no-results, invalid, disabled.
- List/table: loading, populated, empty, no-results, selected, focus-visible, partial-error, unavailable.
- Card/summary: default, hover, focus-visible, selected, disabled, expanded, collapsed.
- Form field: empty, filled, focused, valid, invalid, required, disabled, read-only.
- Select/menu: closed, open, highlighted, selected, empty, disabled.
- Checkbox/radio: unchecked, checked, indeterminate, focused, invalid, disabled.
- Button: default, hover, pressed, focus-visible, loading, success, disabled.
- Alert: info, success, warning, error, dismissible, persistent.
- Dialog: closed, opening, open, submitting, validation-error, success, closing.
- Progress: not-started, active, paused, complete, failed.
- Toast: queued, visible, paused, dismissed, action-available.
- Pagination: default, current, previous-disabled, next-disabled, loading.
- Footer: default, compact, expanded.

State rules:
- Preserve entered values after validation failure.
- Expose asynchronous changes through status messaging.
- Keep focus visible and predictable.
- Disable only unavailable actions; explain relevant limitations.
- Pair every error with affected content and recovery guidance.
- Provide text equivalents for visual state indicators.