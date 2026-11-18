Page anatomy
- Frame: navigation, main region, optional utility region.
- Header: context, page title, description, primary action.
- Summary: labeled metric cards and values.
- Controls: search, filters, sort, reset.
- Content: table or cards with loading, empty, and error alternatives.
- Feedback: inline validation, banners, transient notifications.
- Overlay: dialogs, popovers, and tooltips above content.

Component anatomy
- Control: label, input surface, supporting text, validation message.
- Action: icon or text label, interaction surface, state indicator.
- Collection: heading, description, controls, content, pagination.
- Overlay: trigger, positioned surface, title/content, dismissal or confirmation.
- Status: semantic indicator, text label, optional recovery action.

Variants
- Layout: full, compact, stacked, responsive overflow.
- Density: comfortable, compact.
- Emphasis: primary, secondary, quiet, destructive.
- Feedback: informational, success, warning, error.

States
- Default, hover, focus-visible, active/selected, disabled, loading, empty, invalid, success, error, and dismissed where applicable.
- State changes must be visible through text, structure, iconography, or motion-safe styling.

Usage
- Align related controls to a shared grid.
- Maintain one clear hierarchy per section.
- Use semantic elements before custom patterns.
- Keep related actions adjacent and destructive actions distinct.
- Preserve reading and keyboard order across layouts.

Anti-patterns
- Unlabeled controls or ambiguous icons.
- Color-only state communication.
- Excessive borders, shadows, motion, or nested containers.
- Essential content removed on small screens without an equivalent path.
- Placeholder text used for instructions.
- Skeletons that shift layout or imply unavailable content.
- Multiple competing primary actions.

Accessibility
- Every surface has a programmatic name and logical landmark.
- Every control has a visible or programmatic label.
- Every overlay manages focus predictably and supports appropriate dismissal.
- Every collection exposes status, count, and empty/error meaning.
- Visual, reading, and keyboard order remain aligned.
- Reduced-motion preferences remove nonessential transitions.
- Text remains usable at increased size, zoom, and narrow widths.