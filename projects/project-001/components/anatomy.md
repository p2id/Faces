Global anatomy:
- Header: product label, global search, utility actions.
- Navigation: section links, active indicator, collapse control.
- Main: page heading, supporting text, primary action, content regions.
- Content region: toolbar, filters, body, feedback, pagination.
- Footer: secondary links and version label.
- Variants: wide, compact, mobile.
- States: default, loading, empty, error, unavailable.
- Usage: preserve hierarchy and consistent region order.
- Anti-patterns: duplicated headings, hidden navigation, overcrowded toolbars.
- Accessibility: landmarks, logical heading order, keyboard access, visible focus.

Overview anatomy:
- Heading block: “Overview” and supporting summary.
- Metric grid: label, value, change or status.
- Recent items: heading, table or list, empty or error message.
- Action area: primary action and secondary actions.
- Variants: standard, dense, mobile.
- States: loading, populated, empty, error.
- Usage: show the most relevant summary first.
- Anti-patterns: metrics without labels, unexplained changes, color-only status.
- Accessibility: descriptive headings, table/list semantics, announced updates.

Detail anatomy:
- Back link, title, status badge, metadata, content, related activity, action group.
- Variants: read-only, editable, compact, wide.
- States: loading, populated, unsaved, validation-error, success, unavailable.
- Usage: keep title and status visible; separate destructive actions.
- Anti-patterns: hidden status, unexplained abbreviations, destructive action beside primary save, hover-only content.
- Accessibility: logical headings, labelled status, keyboard-accessible actions, non-color state cues.

Feedback anatomy:
- Inline alert: role cue, title, message, optional action, dismiss control.
- Toast: concise message, severity, optional action, dismiss control.
- Variants: informative, positive, caution, negative.
- States: entering, visible, dismissing, expired.
- Usage: use inline alerts for contextual issues and toasts for completed low-risk actions.
- Anti-patterns: toast-only critical errors, unreadably short auto-dismissal, redundant messages.
- Accessibility: appropriate live-region politeness; sufficient reading time; labelled dismissal; persistent critical errors.