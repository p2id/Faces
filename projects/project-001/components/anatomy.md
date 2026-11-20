AppShell
- Anatomy: skip link, header, navigation, main landmark, optional footer.
- Variants: full navigation, compact navigation, embedded surface.
- States: default, loading, offline, error.
- Usage: provide stable landmarks and consistent navigation.
- Anti-patterns: competing primary navigation, hidden current location.
- Accessibility: one main landmark, visible current item, keyboard skip link.

Collection
- Anatomy: heading, search, filters, sort, result count, list, pagination.
- Variants: grid, list, table-like rows, filtered view.
- States: populated, loading, empty, no-results, error, partial.
- Usage: keep query and filter context visible; provide reset and recovery.
- Anti-patterns: silent filter changes, unbounded lists, inaccessible table patterns.
- Accessibility: announce result changes; label controls; preserve focus after updates.

Detail
- Anatomy: back link, heading, status, summary, attributes, primary and secondary actions.
- Variants: read-only, editable, compact.
- States: loading, populated, editing, saving, saved, validation-error, load-error.
- Usage: establish hierarchy and place the primary action near the heading.
- Anti-patterns: indistinct destructive action, lost unsaved values, unexplained status.
- Accessibility: heading hierarchy, meaningful landmarks, error summary, status announcement.

Feedback
- Anatomy: semantic tone, concise message, recovery or dismiss action.
- Variants: inline, banner, toast, dialog.
- States: info, success, warning, error, persistent, dismissed.
- Usage: place feedback at the point of impact and provide next steps.
- Anti-patterns: flashing content, vague errors, essential information only in a toast.
- Accessibility: appropriate live-region behavior, sufficient duration, pause or dismiss controls.

Overlay
- Anatomy: trigger, surface, title or label, content, close or selection control.
- Variants: tooltip, popover, menu, dialog.
- States: closed, opening, open, focused, dismissed.
- Usage: anchor to the trigger and provide predictable dismissal.
- Anti-patterns: hover-only content, off-screen positioning, unclear nested escape.
- Accessibility: keyboard parity, focus management, Escape behavior, trigger relationship.