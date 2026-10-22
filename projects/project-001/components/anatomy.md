# Shared Anatomy and Interaction Rules

## Page Shell
- Anatomy: skip link, header, navigation, main landmark, optional footer.
- Variants: full navigation, compact navigation, focused layout.
- States: default, loading, unavailable-notice.
- Usage: establish structure and orientation.
- Anti-patterns: duplicate landmarks, missing page title, content hidden behind fixed regions.
- Accessibility: landmarks, skip link, logical headings, visible focus.

## Form Field
- Anatomy: label, control, hint, validation message, required indicator.
- Variants: inline, stacked, grouped.
- States: empty, filled, focused, invalid, valid, disabled, read-only.
- Usage: present each label and control as one understandable unit.
- Anti-patterns: unlabeled controls, placeholder-only instructions, detached errors.
- Accessibility: programmatic label, description, invalid state, error association, adequate target.

## Navigation Item
- Anatomy: optional icon, text label, active indicator, optional count badge.
- Variants: primary, secondary, compact.
- States: default, hover, focus-visible, active, disabled.
- Usage: move between stable destinations.
- Anti-patterns: color-only active state, ambiguous icons, changing item position.
- Accessibility: link semantics, current-location state, visible labels, keyboard access.

## Status Indicator
- Anatomy: text label, optional icon, supporting detail.
- Variants: neutral, informative, success, warning, critical.
- States: static, updating, unavailable.
- Usage: communicate state with redundant text and visual treatment.
- Anti-patterns: color-only status, unexplained symbols, flashing indicators.
- Accessibility: text equivalent, sufficient contrast, polite updates, no rapid flashing.

## Empty and Error Region
- Anatomy: heading, explanation, optional decorative graphic, recovery action.
- Variants: initial empty, filtered empty, unavailable, recoverable error.
- States: default, retrying, resolved.
- Usage: explain absence or failure and provide the next action.
- Anti-patterns: blank screens, blame-oriented language, retry loops without feedback.
- Accessibility: descriptive heading, concise explanation, keyboard recovery, contextual focus movement.

## Overlay Layer
- Anatomy: backdrop, panel, title, content, actions, close control.
- Variants: dropdown, drawer, modal, tooltip.
- States: hidden, opening, open, closing.
- Usage: present temporary context without losing orientation.
- Anti-patterns: inaccessible dismissal, essential content permanently covered, motion without fallback.
- Accessibility: correct role, focus management, Escape behavior, viewport containment, reduced-motion support.