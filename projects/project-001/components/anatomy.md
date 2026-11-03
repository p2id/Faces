Header:
- Anatomy: product label, navigation, search, utility actions.
- Variants: full, compact, responsive-collapsed.
- States: default, scrolled, loading, unavailable.
- Usage: keep global actions stable and predictable.
- Anti-patterns: crowded controls, undisclosed collapsed navigation, unlabeled icons.
- Accessibility: landmark, ordered keyboard path, expanded-state exposure, 44px targets.

Page header:
- Anatomy: breadcrumb, heading, description, action group.
- Variants: with-tabs, with-status, compact.
- States: default, loading, action-disabled, error.
- Usage: provide one clear title and contextual actions.
- Anti-patterns: multiple equal headings, detached actions, title-only icons.
- Accessibility: heading hierarchy, breadcrumb labels, action names, visible focus.

Button and icon button:
- Anatomy: text or accessible name, optional icon, progress indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, pressed, focus-visible, disabled, loading, success, error.
- Usage: use concise verbs and stable dimensions.
- Anti-patterns: ambiguous symbols, unexplained disabled state, irreversible action without confirmation.
- Accessibility: native button semantics, busy state, keyboard activation, supplemental tooltip.

Field and select:
- Anatomy: label, input, hint, validation, optional affordance.
- Variants: text, search, select, multiline, compact.
- States: empty, filled, focused, disabled, read-only, invalid, valid, loading, open.
- Usage: label every field; show constraints before entry; preserve input.
- Anti-patterns: placeholder-only label, silent validation, low-contrast disabled text.
- Accessibility: programmatic label and description, autocomplete where applicable, error association, sufficient target size.

Tabs:
- Anatomy: tab list, tab, active indicator, associated panel.
- Variants: standard, compact, scrollable.
- States: default, active, hover, focus-visible, disabled, loading.
- Usage: switch between related views without losing context.
- Anti-patterns: unrelated navigation, clipped labels, color-only active state.
- Accessibility: tab roles and relationships, selected state, logical keyboard movement, visible active indicator.

Card and collection:
- Anatomy: heading, metadata, content, optional status, actions.
- Variants: metric, content, selectable, table, list.
- States: default, hoverable, focused, selected, loading, empty, error.
- Usage: group related information with scan-friendly labels.
- Anti-patterns: clickable card with nested actions, excessive decoration, unexplained inconsistent heights.
- Accessibility: meaningful heading, logical reading order, non-color status, keyboard access.

Modal and toast:
- Anatomy: title, message or content, action area, close or dismiss control.
- Variants: confirmation, form, informational, success, warning, error.
- States: closed, opening, open, submitting, success, error, closing.
- Usage: use modals for focused decisions and toasts for brief nonblocking confirmation.
- Anti-patterns: stacked modals, critical information only in a toast, dismissal without recovery.
- Accessibility: dialog name, focus trap and restoration, escape handling, live-region role, reduced-motion support.