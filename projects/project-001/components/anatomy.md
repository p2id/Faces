## Global shell
- Anatomy: skip link, navigation, page container, header, main, status region.
- Variants: expanded, collapsed, narrow content, wide content.
- States: loading, ready, empty, error, unavailable.
- Usage: consistent structure across surfaces.
- Anti-patterns: changing navigation placement; missing page heading; load-induced layout shift.
- Accessibility: landmarks, skip link, logical focus order, current-section indication.

## Page header
- Anatomy: context label, heading, supporting text, action group.
- Variants: standard, compact, status, filter-enabled.
- States: default, loading, action-disabled, validation-error.
- Usage: state purpose and primary next action.
- Anti-patterns: vague heading; multiple dominant actions; detached actions.
- Accessibility: one clear heading, labelled actions, associated status.

## Summary region
- Anatomy: metric label, value, comparison, optional status.
- Variants: one-column, multi-column, compact.
- States: loading, populated, unavailable, stale, error.
- Usage: show high-value summaries before detail.
- Anti-patterns: unexplained abbreviations; color-only trends; distracting motion.
- Accessibility: textual trend meaning, labelled values, announced loading.

## Collection region
- Anatomy: search, filters, sort, result count, list/table, pagination.
- Variants: table, card list, filtered, compact.
- States: loading, populated, empty, filtered-empty, error, refreshing, selected.
- Usage: keep controls near results and preserve filter context.
- Anti-patterns: silent filter resets; inaccessible horizontal scroll; unannounced count changes.
- Accessibility: labelled controls, list/table semantics, announced updates, keyboard pagination.

## Form region
- Anatomy: field group, labels, controls, hints, errors, actions.
- Variants: single-column, two-column, compact.
- States: pristine, edited, submitting, invalid, valid, success, failure.
- Usage: group related fields and keep actions consistent.
- Anti-patterns: ambiguous labels; errors without guidance; destructive reset as default.
- Accessibility: fieldset and legend where needed, error association, preserved focus.

## Empty and error region
- Anatomy: heading, explanation, optional decorative icon, next action.
- Variants: initial empty, filtered-empty, recoverable error, unavailable.
- States: visible, action-pending, resolved.
- Usage: explain absence and provide the safest useful next step.
- Anti-patterns: blame-oriented wording; delayed action; generic unrecoverable error.
- Accessibility: meaningful heading, actionable text, announced status, no color-only meaning.