Shared anatomy:
- Page: landmark, header, title block, main content, feedback region, footer.
- Action group: primary, secondary, optional tertiary action.
- Form row: label, control, helper text, validation text.
- Review block: summary, changed values, consequence note, confirmation action.
- Collection: heading, status, rows, empty or error fallback.

Variants:
- Density: comfortable, compact.
- Layout: single-column, split-panel, stacked-mobile.
- Emphasis: neutral, accent, warning, error.
- Interaction: static, selectable, expandable, dismissible.

States:
- System: loading, ready, empty, unavailable, degraded, error.
- Interaction: hover, focus-visible, pressed, selected, disabled.
- Validation: untouched, valid, invalid, corrected.
- Submission: idle, submitting, completed, failed.

Usage:
- Keep anatomy consistent across surfaces.
- Use hierarchy before decoration.
- Place the primary action at the end of the task sequence.
- Preserve content and action order across responsive layouts.
- Pair each state change with clear text or an equivalent accessible signal.

Anti-patterns:
- Ambiguous labels, hidden prerequisites, unexplained abbreviations, layout shifts, clipped controls, color-only status, inaccessible custom controls, automatic destructive actions, excessive motion, hover-dependent content.

Accessibility:
- Use semantic HTML and heading hierarchy.
- Provide accessible names, descriptions, and associated errors.
- Maintain keyboard access and visible focus.
- Meet WCAG 2.2 AA contrast and resize requirements.
- Maintain 44px minimum targets and logical reading order.
- Announce meaningful status changes without unnecessary interruption.
- Respect reduced-motion preferences without removing functionality.