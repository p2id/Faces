Global anatomy:
- Shell: header, navigation, main landmark, optional secondary region, footer.
- Header: product label, navigation, search or utility controls.
- Main: breadcrumb or context, page heading, primary workspace, feedback region.
- Workspace: content collection or form, supporting summary, action group.
- Feedback: inline messages near the source plus global status when needed.
- Footer: support, preferences, legal, and version links.

Variants:
- Collection view: filters, result count, list or table, pagination.
- Detail view: summary, grouped fields, related information, action group.
- Form view: instructions, fields, validation, review, submit action.
- Compact view: condensed header, stacked content, persistent primary action.

States:
- Loading: preserve structure with lightweight placeholders.
- Empty: explain what is absent and offer a relevant next step.
- Error: state what failed, preserve recoverable input, provide retry or correction.
- Success: confirm the completed action and identify the next available action.
- Unavailable: explain the limitation without exposing implementation details.

Usage:
- Establish one clear primary task per surface.
- Group related information with headings and adequate spacing.
- Keep status adjacent to the content it describes.
- Use consistent action order: primary, secondary, low-emphasis.
- Prefer progressive disclosure for optional detail.

Anti-patterns:
- Dense ungrouped content.
- Hidden required fields.
- Ambiguous icons or unlabeled controls.
- Layout changes that reorder meaning.
- Modal use for routine information.
- Truncated labels that hide action meaning.
- Decorative motion that delays task completion.

Accessibility:
- Use landmarks, headings, lists, tables, and native controls semantically.
- Maintain logical reading and focus order in every variant.
- Provide visible focus, sufficient contrast, text alternatives, and status announcements.
- Support keyboard, touch, zoom, reflow, and reduced motion.
- Ensure every state has an understandable text equivalent.