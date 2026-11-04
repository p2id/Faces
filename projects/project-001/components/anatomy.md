Shell
- Anatomy: header, navigation, main region, optional complementary panel, footer.
- Variants: full navigation, compact navigation, no complementary panel.
- States: default, collapsed, expanded, loading.
- Usage: maintain consistent landmarks and placement.
- Anti-patterns: duplicate navigation, hidden current location, loading layout shift.
- Accessibility: labelled landmarks, current navigation item, skip link, logical focus order.

Page surface
- Anatomy: breadcrumb, title, description, actions, controls, content region.
- Variants: list, detail, form, dashboard, empty, error.
- States: default, loading, empty, error, success.
- Usage: establish one heading and one primary task.
- Anti-patterns: multiple H1 headings, action-only header, unscannable text.
- Accessibility: logical heading hierarchy, descriptive title, status announcements, adequate spacing.

Content item
- Anatomy: title, metadata, status, supporting text, optional icon, actions.
- Variants: card, table row, list row, summary panel.
- States: default, hover, focus, selected, disabled, loading, error.
- Usage: show important information first and keep actions local.
- Anti-patterns: unnamed clickable container, nested interactive controls, essential-text truncation.
- Accessibility: meaningful name, visible state text, keyboard operation, sufficient contrast.

Form section
- Anatomy: section heading, fields, helper text, validation, action group.
- Variants: single-column, two-column, progressive disclosure.
- States: pristine, edited, submitting, invalid, saved, failed.
- Usage: group related fields and preserve values after errors.
- Anti-patterns: unexplained required fields, blur-only validation, destructive default action.
- Accessibility: fieldset and legend where appropriate, explicit required state, linked errors, complete keyboard flow.

Feedback surface
- Anatomy: status marker, title, message, action, dismiss control.
- Variants: inline alert, banner, toast, empty state, error state.
- States: entering, visible, dismissing, persistent, resolved.
- Usage: state what happened and the next available action.
- Anti-patterns: timeout-only critical messages, vague failure text, excessive notification stacking.
- Accessibility: match role and live-region priority to urgency; never rely on color alone.