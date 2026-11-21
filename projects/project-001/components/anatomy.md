System anatomy:
- Shell: header, navigation, main content, optional complementary region, footer.
- Page frame: context line, one H1, supporting text, primary action, content sections.
- Content section: heading, description, aligned content, local actions, status or empty treatment.
- Form section: grouped fields, labels, help text, validation summary, action row.
- Feedback layer: inline message near source, global alert for broad impact, toast for noncritical confirmation.
- Responsive layer: layout changes without changing meaning, order, or action priority.

Variants:
- Density: comfortable, compact.
- Emphasis: neutral, informative, positive, warning, negative.
- Layout: single-column, split-column, grid, list.
- Interaction: static, selectable, actionable, modal.
- Content: populated, empty, filtered-empty, loading, error.

States:
- System: loading, ready, empty, filtered-empty, partial-error, error, complete.
- Interaction: default, hover, pressed, focus-visible, selected, disabled.
- Form: untouched, focused, invalid, valid, submitting, submitted.
- Motion: entering, stable, exiting, reduced-motion.

Usage:
- Prefer semantic elements and progressive enhancement.
- Pair each action with a clear outcome and stable placement.
- Keep content scannable, readable, and localization-resilient.
- Apply semantic tokens consistently.
- Preserve focus and entered content during transitions and errors.

Anti-patterns:
- Unlabeled controls, ambiguous icons, hidden errors, layout shifts, color-only meaning.
- Deep nesting, dense ungrouped content, forced page scrolling, unpausable motion.
- Arbitrary colors, inconsistent spacing, competing primary actions.
- Placeholder-only instructions, disappearing critical feedback, destructive actions without confirmation.

Accessibility:
- Target WCAG 2.2 AA with keyboard-complete interaction.
- Provide landmarks, headings, names, roles, values, descriptions, and states.
- Meet 4.5:1 body-text contrast and 3:1 large-text and non-text contrast.
- Use 44×44px targets, visible focus, zoom/reflow support, and reduced-motion support.
- Announce dynamic changes appropriately and preserve logical focus.