app_shell:
- anatomy: skip link, header, navigation, main region, optional footer
- variants: compact, expanded
- states: default, loading, error, empty, success
- usage: establish predictable landmarks and preserve layout during loading
- anti-patterns: duplicate landmarks, unreachable skip target, layout shift
- accessibility: labelled landmarks, skip-to-main link, logical tab order

navigation_item:
- anatomy: optional icon, text label, active indicator
- variants: top-level, nested, compact
- states: default, hover, focus-visible, active, disabled
- usage: match active state to the current section
- anti-patterns: unnamed icon-only navigation, color-only active indication
- accessibility: links for navigation, current-location state exposed programmatically

card:
- anatomy: heading, supporting content, optional media, optional action
- variants: metric, content, selectable
- states: default, hover, focus-visible, selected, disabled, loading, error
- usage: group related information; make the whole card interactive only for one clear action
- anti-patterns: nested links or buttons, excessive elevation, truncated essential content
- accessibility: heading hierarchy, visible selection, one clear accessible name

table:
- anatomy: caption, header row, body rows, optional footer
- variants: compact, standard, responsive
- states: default, loading, empty, error
- usage: use only for tabular relationships; expose sorting and filtering context
- anti-patterns: tables for layout, unnamed row actions, continuous motion
- accessibility: semantic table, header scope, row context, responsive alternative

toast:
- anatomy: status indicator, message, optional action, dismiss control
- variants: info, success, warning, error
- states: info, success, warning, error, dismissed
- usage: communicate non-blocking outcomes; allow adequate reading time
- anti-patterns: critical errors only in a toast, premature dismissal, excessive stacking
- accessibility: status or alert semantics as appropriate; keyboard-dismissible

modal:
- anatomy: backdrop, dialog surface, title, body, actions
- variants: small, medium, confirmation
- states: closed, open, loading, error, success
- usage: interrupt only for focused decisions and provide explicit cancellation
- anti-patterns: modal for simple context, irreversible default action, background interaction
- accessibility: labelled dialog, focus containment, safe Escape behavior, restored focus