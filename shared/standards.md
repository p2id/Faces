# Shared interface standards

## Structure
Use semantic regions, predictable hierarchy, consistent spacing, explicit labels, and visible primary actions.

## States
Define default, loading, empty, error, complete, disabled, validation, and recovery states for each meaningful surface.

## Accessibility
Support keyboard navigation, visible focus, adequate contrast, readable type, descriptive status, logical order, touch targets of at least 44px, and reduced-motion-safe behavior.

## Responsive behavior
Reflow before shrinking legibility; preserve action visibility; prevent clipped content; expose overflow; test small, medium, and large widths.

## Tokens
Prefer semantic tokens over raw values. Keep color, type, spacing, shape, and motion tokens consistent across components.

## Writing rules
Use short, literal, neutral labels. State the condition, impact, and next available action. Avoid identity, entity, tool, backend, personal-data, deceptive, or anthropomorphic language.

## Quality gate
Review hierarchy, state completeness, contrast, focus, keyboard path, status visibility, recovery, responsive behavior, content length, and reduced-motion tolerance.

## Publishing rules
Every artifact includes stable project id, date, scope, representation rationale, gate status, and known gaps. Keep source and rendered forms aligned. Publish only reviewed content and preserve repository paths for traceability.