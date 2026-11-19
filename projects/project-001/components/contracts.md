Button
- Anatomy: label, optional icon, optional loading indicator.
- Variants: primary, secondary, quiet, destructive, icon-only.
- States: default, hover, focus-visible, pressed, loading, disabled.
- Usage: trigger a clear action; use one primary action per region.
- Anti-patterns: vague labels, unnamed icon-only controls, nested buttons, unexplained disabled actions.
- Accessibility: native button semantics, keyboard activation, 44×44px target, announced loading state.

Text input
- Anatomy: label, input, optional hint, validation message.
- Variants: single-line, search, numeric, multiline.
- States: empty, filled, hover, focus, invalid, valid, disabled, readonly.
- Usage: collect one clearly defined value.
- Anti-patterns: placeholder-only labels, unexplained validation, excessive formatting constraints.
- Accessibility: programmatic label, description and error association, visible focus, suitable autocomplete.

Select and menu
- Anatomy: trigger, value, popup, options, optional search.
- Variants: select, menu, combobox.
- States: closed, open, focused, selected, invalid, disabled.
- Usage: choose from a bounded set.
- Anti-patterns: hover-only menus, inaccessible custom listboxes, long unsearchable option sets.
- Accessibility: correct expanded and selected semantics, keyboard navigation, focus restoration.

Dialog and drawer
- Anatomy: title, description, content, action area, close control.
- Variants: modal, confirmation, side drawer.
- States: closed, opening, open, submitting, error, success.
- Usage: contain a focused task or important confirmation.
- Anti-patterns: nested overlays, missing close path, destructive default action.
- Accessibility: labeled container, focus containment, Escape support, inert background, focus restoration.

Alert and notice
- Anatomy: status icon, message, optional detail, optional action, dismiss control.
- Variants: informative, positive, caution, negative.
- States: entering, visible, exiting, dismissed.
- Usage: place important status near affected content; use notices for brief non-blocking feedback.
- Anti-patterns: auto-dismiss critical errors, color-only meaning, excessive stacking.
- Accessibility: suitable live-region politeness, readable duration, dismissible content, clear action names.