App shell
- Anatomy: navigation, header, main region, overlay layer.
- Variants: expanded, compact.
- States: default, collapsed, overlay-open.
- Usage: establish landmarks and preserve content position.
- Anti-patterns: nested scroll regions, hidden primary navigation, layout shift.
- Accessibility: named landmarks, skip path, logical focus order.

Button
- Anatomy: label, optional icon, focus indicator, loading indicator.
- Variants: primary, secondary, quiet, icon-only, destructive.
- States: default, hover, focus, pressed, disabled, loading, success.
- Usage: use explicit action verbs such as “Apply filters”.
- Anti-patterns: unnamed icon-only controls, multiple competing primary actions, unexplained disabled state.
- Accessibility: native button semantics, 44px target, announced loading status.

Field
- Anatomy: label, control, hint, error, required indicator.
- Variants: text, search, select, date.
- States: empty, filled, hover, focus, disabled, read-only, invalid, valid, loading.
- Usage: keep labels persistent and place help beside the relevant control.
- Anti-patterns: placeholder-only labels, color-only errors, ambiguous grouping.
- Accessibility: programmatic label, description, error association, keyboard operation.

Table
- Anatomy: caption, header, rows, cells, sort control, row action.
- Variants: compact, standard, responsive.
- States: loading, populated, sorted, filtered, empty, error, unavailable.
- Usage: present comparable structured information with stable column meaning.
- Anti-patterns: unreadable density, unexplained abbreviations, essential labels hidden by scrolling.
- Accessibility: header associations, announced sort state, keyboard-accessible actions.

Dialog
- Anatomy: backdrop, title, content, actions, close control.
- Variants: confirmation, form, informational.
- States: closed, opening, open, submitting, success, error.
- Usage: interrupt only for focused decisions or required input.
- Anti-patterns: nested dialogs, destructive default action, loss of entered content.
- Accessibility: labelled dialog, focus containment, Escape handling, focus restoration.

Toast
- Anatomy: status indicator, message, optional action, dismiss control.
- Variants: information, success, warning, error.
- States: entering, visible, dismissing.
- Usage: provide brief non-blocking feedback.
- Anti-patterns: critical instructions only in a toast, rapid stacking, automatic removal of important errors.
- Accessibility: suitable live-region priority, readable duration, dismissible output.