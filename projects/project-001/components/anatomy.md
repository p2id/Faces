Global shell
- Anatomy: header, navigation, main region, optional footer.
- Variants: full navigation, compact navigation, focused workspace.
- States: loading, ready, offline, error.
- Usage: keep navigation stable and preserve page context.
- Anti-patterns: changing navigation position, blocking shell rendering for content.
- Accessibility: landmarks, skip link, logical heading hierarchy, visible focus.

Page composition
- Anatomy: context label, title, description, action group, content sections, feedback region.
- Variants: overview, list, detail, form, empty.
- States: loading, populated, empty, filtered-empty, error, success.
- Usage: place the primary task above secondary content; use progressive disclosure.
- Anti-patterns: competing primary actions, unexplained abbreviations, dense uninterrupted text.
- Accessibility: one clear page heading, meaningful section headings, readable line length, preserved reading order.

Navigation
- Anatomy: link label, selected indicator, optional icon, overflow control.
- Variants: sidebar, horizontal, compact.
- States: default, selected, hover, focus, disabled, collapsed.
- Usage: labels describe destinations and remain consistent.
- Anti-patterns: color-only selection, hidden current location, inaccessible overflow.
- Accessibility: navigation landmark, current-page indication, keyboard operation, visible focus, adequate target size.

Feedback
- Anatomy: status, concise message, next step, optional details.
- Variants: inline, banner, toast, progress.
- States: pending, active, complete, error, dismissible.
- Usage: explain what occurred and identify available next steps.
- Anti-patterns: generic errors, silent failure, conflicting simultaneous messages.
- Accessibility: announce meaningful updates, pair color with text and iconography, do not rely on motion.

Content controls
- Anatomy: label, control, hint, validation, action.
- Variants: text, choice, date, numeric, metadata.
- States: empty, filled, focus, valid, invalid, disabled, read-only.
- Usage: group related controls and keep instructions adjacent.
- Anti-patterns: unlabeled controls, placeholder-only instructions, indistinct destructive actions.
- Accessibility: explicit labels, error recovery guidance, adequate contrast, keyboard and assistive-technology support.