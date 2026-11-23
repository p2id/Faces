# Section D — Shared Anatomy

## Page Shell
- Anatomy: header, navigation, main region, optional footer.
- Variants: full navigation, collapsed navigation, focused detail.
- States: loading, ready, empty, error, offline.
- Usage: provide consistent hierarchy and landmarks.
- Anti-patterns: multiple page titles, hidden navigation, loading layout shifts.
- Accessibility: landmarks, one primary heading, logical focus order, skip-to-content link.

## Search and Filter Bar
- Anatomy: search field, filter controls, applied-filter summary, clear action.
- Variants: inline, stacked, compact.
- States: default, populated, filtering, no-results, invalid, disabled.
- Usage: narrow a collection while preserving context.
- Anti-patterns: silent filter resets, unlabeled controls, missing clear-all action.
- Accessibility: visible labels, grouped controls, announced result changes, keyboard access.

## Card
- Anatomy: heading, supporting text, metadata, optional media, action area.
- Variants: informational, selectable, interactive, compact.
- States: default, hover, focus, selected, disabled, loading, error.
- Usage: group related content for scanning.
- Anti-patterns: nested conflicting links, dense unstructured text, decorative media used as meaning.
- Accessibility: meaningful heading, one clear interactive target, decorative media hidden from assistive technology.

## Badge
- Anatomy: text label, optional status icon.
- Variants: neutral, informative, positive, caution, negative.
- States: default, selected, disabled.
- Usage: show concise status or category context.
- Anti-patterns: badge as sole action, color-only meaning, excessive badge density.
- Accessibility: meaningful text, supplementary icon, sufficient contrast.

## Feedback Block
- Anatomy: status indicator, heading, explanation, recovery or next action.
- Variants: initial empty, filtered empty, skeleton loading, recoverable error, terminal error.
- States: visible, transitioning, resolved.
- Usage: explain current status and next available action.
- Anti-patterns: blank screens, indefinite spinner, blame-oriented copy, unconfirmed destructive recovery.
- Accessibility: announce meaningful changes, preserve layout, provide text equivalents, respect reduced motion.

## General Contract
- Tokens are the visual source of truth.
- Components expose semantic states rather than implementation details.
- Content remains understandable without color, motion, hover, or pointer input.
- Interactive regions retain stable dimensions during loading and error transitions.