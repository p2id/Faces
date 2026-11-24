# Shared Anatomy
- Page shell: skip link, header, navigation, main landmark, optional footer.
- Header: product label, section title, search, primary action, overflow action.
- Navigation: labeled landmark, ordered items, active indicator, collapse control.
- Section: heading, supporting text, content group, local actions.
- Control group: visible label, control, hint, validation message, status.
- Data view: caption or heading, field labels, values, statuses, empty state.
- Overlay: backdrop, title, description, content, actions, close control.

## Variants
- Density: comfortable, compact.
- Emphasis: primary, secondary, quiet, destructive.
- Layout: inline, stacked, split, full-width.
- Surface: flat, bordered, raised.
- Content: loading, populated, empty, error.

## States
- Interactive elements: default, hover, focus-visible, pressed or selected, disabled, loading, success, error.
- Content surfaces: loading, populated, empty, error, offline.
- State changes preserve context, announce meaningful updates, and do not rely on color alone.

## Usage
- Use one primary action per surface.
- Keep labels specific: “Save changes”, “Try again”, “View details”.
- Group related information and maintain consistent alignment.
- Use progressive disclosure for secondary detail.
- Preserve entered values and selections after validation failure.

## Anti-Patterns
- Avoid placeholder-only labels, unlabeled icons, hover-only information, nested interactive elements, layout shifts, irreversible actions without confirmation, and modal navigation.
- Do not hide essential content behind color, animation, tooltip, or horizontal scrolling.
- Do not represent unavailable data as complete, successful, or verified.

## Accessibility
- Prefer semantic HTML before ARIA.
- Provide names, roles, values, descriptions, focus order, keyboard operation, and status announcements.
- Maintain WCAG 2.2 AA contrast, 44px targets, visible focus, 200% zoom, 320px reflow, and reduced-motion behavior.