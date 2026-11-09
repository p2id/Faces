App shell
- Anatomy: skip link, navigation, header, main, optional complementary region.
- Variants: persistent, compact, mobile-collapsed.
- States: loading, ready, constrained, offline, error.
- Usage: provide consistent landmarks and preserve content position.
- Anti-patterns: unnecessary nested scrolling; hidden navigation without a trigger; load-induced layout shift.
- Accessibility: landmarks, skip link, logical focus order, visible focus.

Button
- Anatomy: label, optional icon, optional progress indicator.
- Variants: primary, secondary, tertiary, destructive, icon-only.
- States: default, hover, pressed, focused, disabled, loading.
- Usage: use clear verbs and one primary action per prominent region.
- Anti-patterns: vague labels; unexplained disabled actions; unnamed icon-only controls.
- Accessibility: native button semantics, 44×44px target, announced loading, sufficient contrast.

Text input
- Anatomy: label, control, hint, error, optional character guidance.
- Variants: single-line, multiline, search, readonly.
- States: empty, populated, focused, invalid, disabled, readonly.
- Usage: keep labels persistent and show format guidance before entry.
- Anti-patterns: placeholder-only labels; clearing values after errors; color-only validation.
- Accessibility: associated label, appropriate autocomplete, hint/error description, explicit required state.

Select and filter
- Anatomy: label, trigger, option list, selected value, clear action.
- Variants: single-select, multi-select, filter, date range.
- States: closed, open, placeholder, selected, applied, invalid, disabled.
- Usage: show applied criteria and provide clear-all.
- Anti-patterns: hidden active filters; unbounded lists; selections that close without feedback.
- Accessibility: keyboard navigation, expanded state, visible focus, selected-state announcement.

Table
- Anatomy: caption/name, headers, sortable headers, rows, row actions, pagination.
- Variants: compact, standard, responsive-card.
- States: loading, populated, empty, filtered-empty, selected, error.
- Usage: align values consistently and keep row actions predictable.
- Anti-patterns: structural layout tables; excessive columns; color-only status.
- Accessibility: semantic table, header associations, sort state, selection announcement.

Dialog
- Anatomy: title, description, content, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, success, error.
- Usage: reserve for focused decisions or short tasks.
- Anti-patterns: nested dialogs; destructive default action; closing after recoverable validation errors.
- Accessibility: labelled dialog, focus containment, Escape behavior, focus restoration, announced errors.

Banner and toast
- Anatomy: status text, optional icon, optional action, dismiss control.
- Variants: info, success, warning, error; inline or floating.
- States: visible, dismissible, persistent.
- Usage: provide concise outcome and next step.
- Anti-patterns: critical instructions only in auto-dismissed messages; obscuring stacks; ambiguous status.
- Accessibility: appropriate status or alert role, text-first message, sufficient duration.