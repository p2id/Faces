Global shell
- Anatomy: navigation, header, main region, feedback layer, footer.
- Variants: expanded navigation, collapsed navigation, compact mobile shell.
- States: loading, ready, offline, error.
- Usage: establish consistent hierarchy and landmarks.
- Anti-patterns: duplicated navigation, hidden primary action, loading-induced layout shift.
- Accessibility: banner, navigation, main, and contentinfo landmarks; skip link; one clear page heading.

Page header
- Anatomy: context label, heading, supporting text, action group.
- Variants: standard, compact, with status, with tabs.
- States: default, loading, error, disabled actions.
- Usage: introduce the page and its primary task.
- Anti-patterns: competing headings, unnamed icon actions, excessive supporting text.
- Accessibility: correct heading hierarchy, readable line length, named actions.

Summary card
- Anatomy: label, value, supporting detail, optional trend or status.
- Variants: metric, status, linked card.
- States: default, hover, focus-visible, selected, loading, unavailable.
- Usage: summarize a meaningful measure or condition.
- Anti-patterns: context-free metrics, color-only trends, clickable cards without affordance.
- Accessibility: clear reading order, semantic link when clickable, text alternative for visual indicators.

Filter bar
- Anatomy: search field, filter controls, applied-filter summary, reset action.
- Variants: inline, stacked, collapsible.
- States: idle, active, loading, no-results, invalid.
- Usage: narrow visible content while preserving context.
- Anti-patterns: silent context changes, no reset path, hidden applied criteria.
- Accessibility: labeled controls, announced result changes, keyboard access, visible applied values.

Content list or table
- Anatomy: heading, controls, header row, content rows, empty or error region, pagination.
- Variants: list, table, grouped list, responsive rows.
- States: loading, populated, empty, filtered-empty, refreshing, error.
- Usage: present comparable content with predictable scanning.
- Anti-patterns: excessive density, ambiguous columns, unexplained horizontal scrolling, hover-only actions.
- Accessibility: semantic table when appropriate, row and column headers, announced sort state, keyboard-accessible actions.

Feedback region
- Anatomy: status, message, optional detail, recovery action.
- Variants: inline, banner, notice, full-page.
- States: informative, positive, caution, negative, dismissed.
- Usage: explain outcomes and next steps.
- Anti-patterns: technical-only errors, duplicate announcements, blocking minor events.
- Accessibility: suitable live-region role, sufficient duration, non-color-only status, clear recovery action.