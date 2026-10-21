App shell
- Anatomy: header, navigation, main content, optional footer.
- Variants: persistent navigation, collapsed navigation, narrow viewport.
- States: default, navigation-collapsed, loading, error.
- Usage: maintain consistent landmarks and page context.
- Anti-patterns: changing navigation order, hidden current location, nested scroll traps.
- Accessibility: landmark semantics, skip link, logical focus order, current-location indication.

Page heading
- Anatomy: optional eyebrow, title, description, action group.
- Variants: title-only, title-plus-description, title-with-actions.
- States: default, loading, error.
- Usage: start main content with a specific title.
- Anti-patterns: competing page titles, action-only heading, unexplained abbreviations.
- Accessibility: one h1, descriptive title, action labels independent of position.

Metric card
- Anatomy: label, value, supporting text, optional trend or status.
- Variants: standard, emphasized, unavailable, loading.
- States: default, hover, focus, loading, unavailable.
- Usage: one meaningful measure per card with time scope where relevant.
- Anti-patterns: decorative precision, unlabeled units, color-only trend direction.
- Accessibility: reading order is label, value, context; trend meaning is text; avoid unnecessary live updates.

Filter bar
- Anatomy: query field, filter controls, active-filter summary, clear action.
- Variants: inline, wrapped, expandable.
- States: default, active-filters, expanded, collapsed, disabled.
- Usage: preserve selections, show criteria, provide clear-all.
- Anti-patterns: silent filtering, hidden criteria, destructive reset without confirmation.
- Accessibility: labels for all controls, announced result changes when appropriate, keyboard-complete operation, descriptive clear action.

Empty state
- Anatomy: title, explanation, optional icon, primary action.
- Variants: first-use, filtered, error-recovery.
- States: default, recovery-ready.
- Usage: explain absent content and provide the next useful action.
- Anti-patterns: blame-oriented language, purposeless decoration, dead-end messaging.
- Accessibility: text equivalent for visuals, correct heading level, actionable recovery path.