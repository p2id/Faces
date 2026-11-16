Shared anatomy:
- Surface: canvas, container, border, elevation.
- Hierarchy: context, heading, description, primary content, supporting content.
- Control: label, value, affordance, feedback, action.
- Feedback: status icon, concise message, recovery action.
- Navigation: landmark, destination label, selected indicator, focus treatment.

Variants:
- Density: comfortable, compact.
- Layout: single-column, split-view, full-width.
- Emphasis: default, accent, muted, destructive.
- Interaction: static, actionable, selectable, editable.
- Viewport: desktop, tablet, mobile.

States:
- Interaction: default, hover, focus-visible, pressed, selected, disabled.
- Data: loading, populated, empty, no-results, error, success.
- Connectivity: available, offline, reconnecting.
- Validation: untouched, invalid, valid, submitting.

Usage:
- Compose pages from named regions with one primary task per region.
- Keep anatomy order stable across variants.
- Use progressive disclosure for secondary details.
- Keep status and recovery actions adjacent to affected content.
- Preserve reading order during reflow.

Anti-patterns:
- Unnamed controls or unlabeled icons.
- Inconsistent action placement.
- Hidden focus or hover-only functionality.
- Color-only status.
- Decorative density that harms scanning.
- Modal use for content that fits inline.
- Unexpected content reordering.
- Empty, loading, or error states without explanation or next action.

Accessibility:
- Prefer semantic HTML before ARIA.
- Give every control an accessible name and visible focus.
- Preserve heading hierarchy, reading order, and keyboard operation.
- Associate labels, hints, errors, and status updates programmatically.
- Meet WCAG 2.2 AA contrast, zoom, reflow, target-size, and motion requirements.
- Test keyboard use, screen reader output, 200% zoom, 400% reflow, and touch input.