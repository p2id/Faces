App shell
- Anatomy: skip link, navigation, header, main region, optional utility region, responsive menu.
- Variants: persistent navigation, collapsed navigation, mobile navigation.
- States: default, loading, error, navigation-open.
- Usage: keep landmark structure stable and primary content in main.
- Anti-patterns: changing navigation order, trapped menu focus, hidden essential labels.
- Accessibility: landmarks, skip link, logical tab order, menu state, Escape-to-close.

Card
- Anatomy: container, eyebrow, heading, body, metadata, action area.
- Variants: informational, actionable, selectable, featured.
- States: default, hover, focus-visible, selected, disabled, loading.
- Usage: represent one coherent subject; make the destination clear.
- Anti-patterns: nested interactive elements, decorative density, unclear click target.
- Accessibility: heading hierarchy, accessible name, semantic link or button, visible focus.

Badge
- Anatomy: text label, optional icon, optional status marker.
- Variants: neutral, informative, positive, caution, negative.
- States: default, disabled.
- Usage: show concise status or category information.
- Anti-patterns: color-only meaning, long sentences, excessive stacking.
- Accessibility: meaningful text, sufficient contrast, stable announcements for changing status.

Tabs
- Anatomy: tab list, tab, active indicator, tab panel.
- Variants: standard, compact, scrollable.
- States: default, hover, focus-visible, active, disabled, overflow.
- Usage: group peer sections with persistent context.
- Anti-patterns: unrelated destinations, hidden active state, disruptive automatic switching.
- Accessibility: tablist, tab, tabpanel semantics, arrow-key navigation, selected state, panel association.

Pagination
- Anatomy: previous control, page controls, next control, result summary.
- Variants: full, compact, cursor-like.
- States: default, previous-disabled, next-disabled, focus-visible, loading.
- Usage: show current position and preserve filters between pages.
- Anti-patterns: unlabeled icon controls, unexpected scroll reset, lost context.
- Accessibility: labeled navigation landmark, current-page indication, descriptive previous/next labels, predictable focus.

===END===