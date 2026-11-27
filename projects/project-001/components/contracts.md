global:
- anatomy: label or heading, content or control, optional description, status, action
- variants: neutral, primary, quiet, destructive only when necessary
- states: default, hover, focus-visible, active, disabled, loading, success, error, empty as applicable
- usage: use semantic HTML, stable labels, token references, and geometry-preserving state changes
- anti-patterns: placeholder-as-label, color-only status, clipped text, nested interactive controls, hover-only actions
- accessibility: keyboard operation, accessible names, 44px targets, visible focus, announced status

button:
- anatomy: label, optional leading icon, optional trailing icon
- variants: primary, secondary, quiet
- states: default, hover, focus-visible, active, disabled, loading, success, error
- usage: use one primary action per region; retain an understandable loading label
- anti-patterns: unnamed icon-only control, ambiguous label, unexplained disabled action
- accessibility: native button semantics, Enter and Space support, busy status while loading

input:
- anatomy: label, field, description, error or success message
- variants: text, search, number
- states: empty, filled, hover, focus-visible, disabled, loading, error, success
- usage: use a persistent label and validate after interaction or submission
- anti-patterns: silent validation, destructive clearing, placeholder-only instructions
- accessibility: label association, described instructions, invalid state, keyboard editing

dialog:
- anatomy: backdrop, labelled title, body, actions, close control
- variants: alert, form, informational
- states: closed, open, loading, error, success
- usage: reserve for focused decisions; provide explicit cancel behavior
- anti-patterns: stacked dialogs, unexpected dismissal, background interaction
- accessibility: dialog semantics, focus containment, safe Escape behavior, focus restoration