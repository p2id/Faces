Global anatomy:
- Shell: navigation, header, main content, overlay layer.
- Section: heading, supporting text, controls, content, feedback.
- Control: visible label, value, affordance, state indicator, focus indicator.
- Feedback: concise message, optional status icon, corrective action.

Variants:
- Density: comfortable, compact.
- Emphasis: primary, secondary, muted.
- Content: populated, loading, empty, error, unavailable.
- Layout: single column, split panel, grid, responsive rows.

States:
- Rest: neutral surface and content.
- Hover: non-layout-moving surface or border change.
- Focus: visible high-contrast ring.
- Selected: persistent selected treatment and programmatic state.
- Disabled: reduced emphasis with an available explanation.
- Loading: stable dimensions and progress indication.
- Error: clear cause, affected area, and correction path.
- Empty: explain absence and provide a relevant next action.
- Success: confirm completion without blocking continuation.

Usage:
- Present purpose before controls.
- Group related controls before content.
- Keep terminology consistent across labels and messages.
- Use progressive disclosure for secondary detail.

Anti-patterns:
- Placeholder-only labels.
- Color-only state communication.
- Decorative motion that delays access.
- Unbounded text lines or dense control clusters.
- Hidden essential content at narrow widths.
- Ambiguous actions such as “Submit”.
- Visual order that conflicts with keyboard order.

Accessibility:
- Use semantic structure and native controls.
- Maintain WCAG 2.2 AA contrast and keyboard operation.
- Provide visible focus, logical order, labels, descriptions, and errors.
- Announce dynamic status without unnecessary interruption.
- Support reduced motion, zoom, reflow, and 320px layouts.
- Give every icon-only control an accessible name.