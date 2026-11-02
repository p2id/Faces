Anatomy standards:
- Page shell: skip link, header, navigation, breadcrumb, page heading, toolbar, main content, optional aside, footer.
  - Variants: full navigation, collapsed navigation, single-column, two-column.
  - States: loading, ready, empty, error, offline.
  - Usage: establish predictable hierarchy and responsive reading order.
  - Anti-patterns: competing headings, hidden primary actions, fixed regions covering content.
  - Accessibility: landmarks, skip navigation, focus order, reflow support.

- Toolbar: search field, filters, sort control, primary action, overflow action.
  - Variants: inline, stacked, compact.
  - States: default, filtering, loading, disabled, error.
  - Usage: group controls by task and show active filter count.
  - Anti-patterns: unlabeled icons, excessive simultaneous filters, reset without confirmation.
  - Accessibility: group label, keyboard order, announced result updates.

- Card: heading, supporting text, metadata, status, action area.
  - Variants: content, selectable, interactive, loading.
  - States: default, hover, focus-within, selected, disabled, loading.
  - Usage: keep the interactive region consistent with its affordance.
  - Anti-patterns: ambiguous nested interactions, meaning-hidden truncation.
  - Accessibility: heading structure, visible focus, complete accessible names.

- Modal: backdrop, dialog container, title, description, content, action group, close control.
  - Variants: confirmation, form, information, destructive.
  - States: closed, opening, open, submitting, success, error.
  - Usage: keep scope narrow and provide an explicit cancel path.
  - Anti-patterns: modal for routine navigation, destructive default, focus leakage.
  - Accessibility: dialog semantics, focus containment, escape, restoration.

- Status message: semantic icon, title, body, optional action.
  - Variants: inline, banner, toast, empty state.
  - States: informational, success, warning, error, persistent.
  - Usage: pair concise explanation with recovery or next action.
  - Anti-patterns: color-only meaning, unexplained codes, disappearing recovery instructions.
  - Accessibility: live-region selection, text alternative, contrast, reduced motion.