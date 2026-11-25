System anatomy:
- Shell: skip link, header, navigation, main landmark, detail region, notification region.
- Header: page title, contextual actions, responsive overflow.
- Workspace: summary, control group, content region, pagination or progressive loading.
- Item: semantic heading, description, status, metadata, action affordance.
- Form: grouped fields, labels, hints, validation messages, action row.
- Overlay: backdrop, panel, title, content, actions, close behavior.
- Feedback: status text, recovery action, dismissal control.

Variants:
- Density: comfortable, compact.
- Layout: list, grid, split detail.
- Theme: light, high-contrast-compatible.
- Content: populated, empty, filtered-empty, loading, error.

States:
- Available, hover, pressed, focus-visible, selected, disabled, loading, success, warning, error, restricted, reduced-motion.

Usage:
- Compose surfaces from semantic landmarks and reusable components.
- Keep hierarchy consistent: page title, section heading, item heading.
- Use progressive disclosure for secondary details.
- Keep primary actions and feedback in stable locations.
- Place recovery actions near affected content.

Anti-patterns:
- Decorative text used as structure.
- Unlabelled icons or controls.
- Modal use for routine editing.
- Flashing content, infinite motion, or motion-only feedback.
- Dense layouts requiring page-level horizontal scrolling.
- Hidden errors, ambiguous status labels, or routine styling for destructive actions.
- Nested interactive elements and duplicated accessible names.

Accessibility:
- Use semantic HTML and explicit control names.
- Preserve keyboard order and visible focus across responsive layouts.
- Pair visual status with text or an accessible description.
- Support zoom, reflow, reduced motion, high contrast, and announcements.
- Maintain 44×44px targets and WCAG 2.2 AA contrast.
- Ensure empty, loading, and error states explain the condition and next action.