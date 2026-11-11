# Shared Anatomy
- Page: navigation, location cue, page header, content regions, feedback, footer.
- Navigation: product label, links, active indicator, collapse control, utility region.
- Header: context, one H1, concise description, primary and secondary actions.
- Container: consistent gutters, readable measure, responsive grid, vertical rhythm.
- Control group: label, control, instructions, validation, action area.
- Data region: heading, search/filter controls, result count, collection, empty/loading/error treatment.
- Overlay: optional backdrop, labelled surface, content, close control, actions.

## Variants
- Density: comfortable, compact.
- Emphasis: neutral, accent, positive, caution, negative, informative.
- Layout: stacked, inline, split, responsive.
- Content: populated, empty, loading, error, filtered.
- Interaction: static, selectable, expandable, actionable.

## States
- Global: default, hover, pressed, focus-visible, selected, disabled, loading, success, error.
- Layout: expanded, collapsed, reflowed, overflowed.
- Data: empty, partial, populated, stale, filtered, sorted.
- Form: pristine, dirty, invalid, valid, submitting, submitted.
- Overlay: closed, opening, open, closing.

## Usage
- Prefer semantic structure and native controls.
- Use consistent labels, verbs, spacing, and status language.
- Keep primary actions visible and secondary actions quiet.
- Preserve content order, focus order, and task continuity at every breakpoint.
- Pair meaningful state changes with clear visual and textual cues.

## Anti-Patterns
- Do not rely on color, hover, motion, or position alone.
- Do not hide essential actions behind unexplained icons or menus.
- Do not use placeholder text as the only instruction.
- Do not require horizontal scrolling for core tasks.
- Do not remove focus indicators or auto-dismiss critical errors.
- Do not use motion that distracts, flashes, or causes layout shift.

## Accessibility
- Meet WCAG 2.2 AA.
- Provide keyboard access, visible focus, semantic structure, accessible names, and programmatic relationships.
- Support 200% zoom, 320px reflow, reduced motion, and high-contrast-compatible boundaries.
- Announce loading, success, error, and result-count changes appropriately.
- Maintain 44px minimum touch targets and adequate spacing.