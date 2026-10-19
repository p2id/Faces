Global anatomy:
- Shell: header, navigation, main landmark, optional secondary region, footer.
- Header: product label, navigation, search or utility controls.
- Main: context, page heading, primary workspace, feedback region.
- Workspace: collection or form, supporting summary, action group.
- Feedback: inline message near source and global status when needed.
- Footer: help, preferences, legal, version links.

Variants:
- Collection: filters, count, list or table, pagination.
- Detail: summary, grouped fields, related information, actions.
- Form: instructions, fields, validation, review, submit action.
- Compact: condensed header, stacked content, persistent primary action.

States:
- Loading: preserve structure with lightweight placeholders.
- Empty: explain absence and offer a relevant next step.
- Error: state failure, preserve recoverable input, provide retry or correction.
- Success: confirm completion and identify the next action.
- Unavailable: explain the limitation without implementation detail.

Usage:
- Establish one primary task per surface.
- Group related content with headings and consistent spacing.
- Keep status beside the content it describes.
- Order actions as primary, secondary, low-emphasis.
- Use progressive disclosure for optional detail.

Anti-patterns:
- Dense ungrouped content.
- Hidden required fields.
- Ambiguous or unnamed controls.
- Layout changes that reorder meaning.
- Modal use for routine information.
- Truncation that hides action meaning.
- Decorative motion that delays completion.

Accessibility:
- Use landmarks, headings, lists, tables, and native controls semantically.
- Maintain logical reading and focus order in every variant.
- Provide visible focus, sufficient contrast, text alternatives, and status announcements.
- Support keyboard, touch, zoom, reflow, and reduced motion.
- Give every visual state an understandable text equivalent.