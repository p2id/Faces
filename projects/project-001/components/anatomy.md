# Interface Anatomy

## App Shell
- Anatomy: header, navigation, main, optional complementary region, footer.
- Variants: full navigation, compact navigation, mobile sheet.
- States: expanded, collapsed, focused, loading.
- Usage: preserve landmarks and page position.
- Anti-patterns: moving primary navigation; hiding current location.
- Accessibility: skip link, landmarks, current-page indication, keyboard navigation.

## Page Layout
- Anatomy: breadcrumb, heading, description, action group, content regions.
- Variants: overview, list, detail, settings.
- States: default, loading, empty, error.
- Usage: place the primary heading before controls and content.
- Anti-patterns: multiple primary headings; context-free action labels.
- Accessibility: logical heading order, descriptive document title, responsive reflow.

## Summary Card
- Anatomy: heading, value, supporting label, optional trend or action.
- Variants: metric, status, shortcut.
- States: default, hover, selected, loading, unavailable.
- Usage: show one clear fact and its interpretation.
- Anti-patterns: color-only meaning; decorative symbols without text; dense paragraphs.
- Accessibility: meaningful heading, complete value text, no visually exclusive information.

## Filter Toolbar
- Anatomy: search field, filter controls, applied-filter indicators, apply and clear actions.
- Variants: inline desktop, stacked mobile, advanced panel.
- States: default, active, invalid, loading, expanded.
- Usage: preserve criteria and expose active-filter count.
- Anti-patterns: submitting on every keystroke; hiding active filters; unclear reset behavior.
- Accessibility: grouped labeled controls, keyboard expansion, announced result updates.

## Item Detail
- Anatomy: title, status, metadata, grouped fields, related actions, return navigation.
- Variants: read-only, editable, compact.
- States: loading, populated, editing, saving, saved, validation-error, unavailable.
- Usage: group related information and keep actions near affected content.
- Anti-patterns: ambiguous statuses; adjacent destructive and save actions without separation; unexplained abbreviations.
- Accessibility: semantic descriptions, fieldset grouping, linked errors, announced status changes.

## Empty/Error/Loading Region
- Anatomy: state title, explanation, optional decorative-free icon, next action.
- Variants: initial empty, filtered empty, recoverable error, skeleton loading.
- States: empty, retryable, loading, resolved.
- Usage: explain the condition and provide the safest useful next step.
- Anti-patterns: blank screen; indefinite spinner; blaming or alarming language.
- Accessibility: available status text, no motion dependency, clearly named retry control.