Global anatomy:
- App shell: header, navigation, main landmark, optional footer.
- Browse: title block, search, filter row, result collection, pagination or empty state.
- Detail: back action, title, metadata, content, action row.
- Form: title, grouped fields, help text, validation summary, action row.
- Feedback: inline status, banner or toast, recovery action.

Variants:
- Density: comfortable, compact.
- Layout: single-column, split-panel, stacked-mobile.
- Emphasis: neutral, selected, warning, error.
- Content length: short, standard, long.

States:
- Global: loading, ready, empty, error, unavailable.
- Interactive: hover, pressed, focus-visible, selected, disabled.
- Transactional: submitting, success, recoverable-error.

Usage:
- Maintain hierarchy from page title to section heading to field label.
- Use progressive disclosure for secondary detail.
- Keep primary actions in predictable locations.
- Group related content with semantic structure and whitespace.

Anti-patterns:
- Decorative elements that resemble controls.
- Unlabelled icon controls or ambiguous status icons.
- Multiple visual styles for the same action.
- Fixed-width content causing horizontal overflow.
- Essential content hidden only at smaller widths.
- Dialogs for routine reversible actions.

Accessibility:
- Use landmarks, semantic headings, labels, lists, and native controls.
- Preserve logical reading and focus order across layouts.
- Provide text alternatives for icons, media, status, and visual summaries.
- Maintain focus visibility and state clarity at all contrast modes.
- Support keyboard access, screen readers, zoom, reflow, reduced motion, and touch input.