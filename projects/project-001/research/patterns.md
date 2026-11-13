Project: project-001
Date: 2026-11-13
Scope: Generic product experience

DOMINANT PATTERNS
- Clear hierarchy with one primary action per surface.
- Modular cards, lists, panels, tabs, tables, and status rows.
- Neutral foundations with one restrained accent.
- Persistent navigation, visible location, predictable back and close behavior.
- Responsive stacking and prioritization instead of desktop shrinking.

EMERGING PATTERNS
- Searchable command surfaces with keyboard access.
- Inline editing with explicit save and cancel states.
- Summary views above detailed records.
- Status encoded by text, icon, and color.
- Motion limited to state feedback and orientation.

DEPRECATED PATTERNS
- Ungrouped dense dashboards.
- Color-only status communication.
- Gesture-only or hidden actions.
- Auto-advancing content and unsolicited overlays.
- Low-contrast decorative gradients.

OUTLIER PATTERNS
- Extremely sparse single-purpose surfaces.
- Configurable expert tables.
- Monochrome interfaces emphasizing shape and spacing.
- Timeline or spatial layouts for sequence-heavy content.

VISUAL DNA
- Neutral background, elevated light surfaces, charcoal text, single blue, green, or violet accent.
- 8px spacing rhythm, 10–14px radius, subtle borders, minimal shadows.
- Strong titles, compact metadata, grouped controls, readable content width.
- Simple line icons paired with labels.

INTERACTIONAL DNA
- One dominant action per surface.
- Immediate acknowledgment after committed actions.
- Reversible destructive actions with proportional confirmation.
- Local validation, explicit empty/loading/success/warning/error states.
- Keyboard-equivalent paths for pointer actions.

ACCESSIBILITY DNA
- WCAG 2.2 AA target.
- At least 4.5:1 normal-text contrast and 3:1 large-text or graphical contrast.
- Semantic landmarks, visible focus, logical focus order, labeled controls.
- No color-only meaning; minimum 44x44 CSS px targets.
- Reduced-motion mode and usable content at 200% zoom.

RESPONSIVE DNA
- Compact under 640px, medium 640–1023px, wide 1024px and above.
- 12-column wide layout, 8-column medium layout, single primary column compact layout.
- Navigation collapses without changing destinations.
- Tables become prioritized rows or horizontal scroll regions.
- Controls wrap or stack while preserving action order.
- Recommended maximum content width: 1200px.

CANDIDATE PRODUCT DOMAINS
1. Planning workspace: organizes items, priorities, dates, and progress in a structured surface.
2. Resource library: supports browsing, filtering, previewing, and organizing reusable content.
3. Monitoring console: summarizes states, exceptions, trends, and detailed records.
4. Configuration center: presents settings, rules, permissions, and validation in guided sections.
5. Reporting studio: combines metric selection, comparison, annotation, and presentation-ready views.
6. Service catalog: presents offerings with comparison, detail, and request states.

WEIGHTED SCORING MATRIX
Weights: clarity 25, responsive fit 20, accessibility fit 20, pattern coverage 20, distinctiveness 15.
- Planning workspace: 23+18+19+19+12 = 91
- Resource library: 22+19+18+18+13 = 90
- Monitoring console: 20+16+17+20+14 = 87
- Configuration center: 21+18+19+18+11 = 87
- Reporting studio: 19+17+17+19+14 = 86
- Service catalog: 21+19+18+17+12 = 87

SELECTED DOMAIN RATIONALE
Planning workspace selected because it supports the broadest reusable combination of hierarchy, status, filtering, responsive restructuring, inline actions, and accessible progress communication.

CYCLE LOCK
Locked domain: planning workspace.
Locked principles: calm hierarchy, one primary action, explicit state feedback, responsive stacking, semantic accessibility.
Locked exclusions: decorative density, color-only states, hidden navigation, automatic movement.

FALLBACK RULE
If planning signals are insufficient, switch to resource library while preserving palette discipline, component grammar, accessibility targets, responsive rules, and motion restraint.