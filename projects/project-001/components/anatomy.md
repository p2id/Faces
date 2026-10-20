Global shell
- Anatomy: header, navigation, breadcrumbs, main content, optional footer.
- Variants: persistent desktop, collapsible tablet, overlay mobile.
- States: default, loading, degraded, offline.
- Usage: keep navigation and context stable.
- Anti-patterns: changing navigation order, inaccessible collapsed menu, duplicate titles.
- Accessibility: landmarks, skip link, focus restoration, zoom and reflow support.

Overview
- Anatomy: page title, description, date range, summary cards, activity summary, primary action.
- Variants: full, compact, loading.
- States: default, empty, error, partial.
- Usage: present context, high-level status, then detail.
- Anti-patterns: excessive cards, unlabeled metrics, visual summaries without text.
- Accessibility: heading hierarchy and text equivalents for visual information.

Records
- Anatomy: search, filters, result count, table or list, pagination, empty/error region.
- Variants: table, stacked list, filtered, read-only.
- States: loading, populated, sorted, filtered, empty, error.
- Usage: preserve filters and make result changes clear.
- Anti-patterns: hidden active filters, missing current-page state, inaccessible overflow.
- Accessibility: labeled controls, live result count, sortable headers, keyboard pagination.

Configuration form
- Anatomy: section heading, field groups, hints, validation messages, save/cancel actions.
- Variants: single-column, two-column, compact.
- States: pristine, dirty, submitting, saved, invalid, error.
- Usage: group related settings and keep actions consistent.
- Anti-patterns: unannounced auto-save, destructive reset beside save, unexplained defaults.
- Accessibility: fieldsets and legends, explicit errors, focused recovery, clear unsaved-change warning.