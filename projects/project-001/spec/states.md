# Component Inventory and States
| Component | States |
|---|---|
| App shell | default, compact, navigation-expanded, navigation-collapsed |
| Header | default, scrolled, action-focused |
| Navigation | default, active, hover, focus-visible, expanded, collapsed, disabled |
| Breadcrumb | default, current, focus-visible, truncated |
| Page title | default, with-description, with-actions |
| Tabs | default, active, hover, focus-visible, disabled |
| Card | default, hover, focus-visible, selected, disabled, loading |
| Text field | empty, filled, hover, focus-visible, disabled, read-only, invalid, valid |
| Select | closed, open, hover, focus-visible, disabled, invalid, selected |
| Date picker | closed, open, date-selected, range-selected, invalid, disabled |
| Checkbox | unchecked, checked, mixed, hover, focus-visible, disabled, invalid |
| Radio group | unselected, selected, hover, focus-visible, disabled, invalid |
| Toggle | off, on, hover, focus-visible, disabled |
| Button | default, hover, pressed, focus-visible, disabled, loading, destructive |
| Alert | info, success, warning, error, dismissible |
| Toast | entering, visible, dismissing, success, error |
| List/table | loading, populated, sorted, filtered, empty, error, selected |
| Pagination | default, current, hover, focus-visible, disabled |
| Modal | closed, opening, open, submitting, validation-error, closing |
| Tooltip | hidden, visible, focus-visible |
| Progress | idle, active, complete, error |
| Skeleton | loading, resolved |
| Empty state | default, actionable, filtered |
| Icon action | default, hover, pressed, focus-visible, disabled |

# State Rules
- Focus-visible uses a persistent high-contrast outline.
- Disabled controls remain perceivable and non-interactive.
- Invalid controls include adjacent text guidance.
- Loading controls preserve dimensions and prevent duplicate submission.
- Empty, error, and success states include a clear next action where useful.
- Dynamic changes use an appropriate live region.