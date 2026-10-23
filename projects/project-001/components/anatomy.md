Global anatomy
- Shell: navigation, header, main landmark, optional side panel, notification layer.
- Header: context, title, description, primary action.
- Content: section heading, controls, primary content, feedback.
- Action group: primary action, secondary action, separated destructive action.
- Feedback: status marker, concise title, supporting text, recovery action.

Variants
- Density: comfortable, compact.
- Emphasis: neutral, accent, success, warning, danger.
- Surface: flat, bordered, elevated, overlay.
- Content: empty, populated, loading, error.
- Navigation: expanded, compact, collapsed.

States
- Rest: stable content and available actions.
- Hover: subtle surface or border change.
- Focus-visible: high-contrast ring without layout shift.
- Active: clear pressed or selected treatment.
- Disabled: reduced emphasis with explanation when needed.
- Loading: preserve structure and communicate progress.
- Empty: explain absence and offer a relevant next action.
- Error: state issue, preserve context, provide recovery.
- Success: confirm completion without blocking continued use.

Usage
- Prefer plain labels, predictable placement, semantic components, and concise feedback.
- Align content to a consistent grid and preserve reading order when columns collapse.
- Use progressive disclosure for secondary detail.
- Keep destructive actions explicit and reversible where possible.

Anti-patterns
- Ambiguous icon-only actions.
- Placeholder-only labels.
- Layout shifts during status changes.
- Interaction dependent only on color, hover, drag, or motion.
- Excessive elevation, nested overlays, competing primary actions.
- Truncation without a full-value path.

Accessibility
- Meet WCAG 2.2 AA and support keyboard-only operation.
- Provide landmarks, heading hierarchy, labels, descriptions, and status announcements.
- Maintain contrast, focus visibility, target size, zoom, reflow, and reduced-motion support.
- Expose correct roles and states for dialogs, menus, tabs, tables, and forms.
- Test keyboard navigation, screen readers, 200% zoom, 320px reflow, and forced colors.