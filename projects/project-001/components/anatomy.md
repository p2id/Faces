# Section D — Shared Anatomy and Behavior

## Page Shell
- Anatomy: navigation, main landmark, context header, content region, feedback region, footer.
- Variants: persistent navigation, collapsed navigation, compact mobile.
- States: loading, ready, degraded, offline, error.
- Usage: keep title, navigation, and action placement consistent.
- Anti-patterns: competing page titles, hidden primary action, layout shift during loading.
- Accessibility: landmarks, skip link, heading order, logical focus order.

## Control Bar
- Anatomy: search, filters, sort, view control, reset action.
- Variants: inline, wrapped, stacked, compact.
- States: idle, active, loading, invalid, disabled.
- Usage: place before results; expose active criteria and reset.
- Anti-patterns: hidden active filters, unlabeled icons, silent result changes.
- Accessibility: grouped controls, explicit labels, keyboard access, announced result updates.

## Results Region
- Anatomy: count, result collection, pagination or load control, empty/error state.
- Variants: cards, rows, dense data list.
- States: loading, populated, no-results, filtered-empty, error, offline.
- Usage: preserve ordering and selection during updates.
- Anti-patterns: blank loading screen, unbounded loading, inaccessible virtualized content.
- Accessibility: collection semantics, stable reading order, announced count changes, keyboard-equivalent actions.

## Detail Region
- Anatomy: title, metadata, summary, content sections, action group, close or back control.
- Variants: inline panel, drawer, full-screen mobile panel.
- States: closed, opening, open, loading, error, saving, success, closing.
- Usage: retain context and provide a clear return path.
- Anti-patterns: lost context, detached actions, adjacent destructive and primary actions without separation.
- Accessibility: heading on open, focus management, labeled close/back action, status announcements, zoom support.

## Empty and Error Feedback
- Anatomy: title, explanation, next action, optional secondary action.
- Variants: no-content, no-results, recoverable-error, blocking-error, offline.
- States: visible, retrying, resolved.
- Usage: explain condition and provide a next step.
- Anti-patterns: blame-oriented language, generic error without recovery, empty state without action.
- Accessibility: text alternatives to visual cues, sufficient contrast, keyboard access, live announcement.