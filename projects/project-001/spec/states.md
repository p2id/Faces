Component inventory and states:
- Shell: default, narrow, loading, offline notice, reduced motion.
- Header/navigation: default, active, hover, focus-visible, expanded, collapsed, disabled.
- Heading: default, with supporting text, loading.
- Summary card: default, hover, focus-visible, loading, unavailable, error.
- Text field: empty, filled, hover, focus, focus-visible, invalid, valid, disabled, read-only.
- Select/filter: closed, open, selected, option hover, focus-visible, invalid, disabled.
- Button: default, hover, pressed, focus-visible, loading, disabled, destructive, quiet.
- Tabs: default, active, hover, focus-visible, disabled.
- Badge/status: neutral, informative, positive, caution, negative, disabled.
- Table/list: loading, populated, empty, filtered empty, row hover, selected, focus-visible, error, truncated.
- Pagination: default, current, hover, focus-visible, disabled first, previous, next, last.
- Detail panel: closed, opening, open, loading, populated, empty, error, unsaved changes.
- Dialog: closed, opening, open, submitting, validation error, success, dismissible, non-dismissible.
- Alert/toast: info, success, warning, error, dismissing, persistent.
- Tooltip: hidden, visible, delayed, dismissing.
- Progress: idle, active, complete, failed, indeterminate.
- Empty state: default, filtered, limited, retryable.
- Error state: inline, page-level, retrying, unrecoverable.
- Skeleton/divider: visible, loading, hidden at narrow widths.

All interactive states expose name, role, value/state, focus, and available action. Unavailable states explain recovery when applicable.