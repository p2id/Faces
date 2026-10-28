App shell
- Anatomy: skip link, navigation region, header, main region, optional footer.
- Variants: full navigation, compact navigation, single-surface.
- States: loading, ready, offline, permission-limited, error.
- Usage: maintain consistent landmarks and page title.
- Anti-patterns: duplicated navigation, inaccessible collapse control, content hidden behind fixed elements.
- Accessibility: landmark labels, logical heading hierarchy, keyboard skip mechanism, visible focus.

Collection view
- Anatomy: title, result count, search, filters, sort, result region, pagination.
- Variants: list, grid, table, filtered.
- States: loading, populated, empty, no-results, error.
- Usage: keep controls adjacent to result context; retain applied filters.
- Anti-patterns: resetting filters unexpectedly, ambiguous sort labels, infinite loading without status.
- Accessibility: announce result changes; label filter groups; expose sort direction; support keyboard traversal.

Detail view
- Anatomy: title, summary, metadata, primary action, secondary actions, related sections.
- Variants: read-only, editable, compact.
- States: loading, ready, saving, saved, error.
- Usage: prioritize summary and primary action above secondary information.
- Anti-patterns: hidden required fields, action labels based only on icons, unclear save status.
- Accessibility: descriptive title, structured headings, status announcements, explicit action names.

Form surface
- Anatomy: heading, instructions, field groups, validation messages, action group.
- Variants: short, multi-section, inline edit.
- States: pristine, editing, invalid, submitting, success, error.
- Usage: group related fields; preserve entered values after errors.
- Anti-patterns: validation only after submission, unexplained required markers, destructive reset as default.
- Accessibility: visible labels, fieldset/legend for groups, error summary, programmatic associations, keyboard-complete operation.

Overlay surface
- Anatomy: trigger, layer, title or label, content, close behavior.
- Variants: tooltip, popover, drawer, dialog, toast.
- States: hidden, opening, open, closing, blocked.
- Usage: select the least disruptive overlay appropriate to the task.
- Anti-patterns: hover-only essential content, overlays without dismissal, stacked competing layers.
- Accessibility: correct overlay role, focus management, Escape handling, sufficient contrast, no obscured focus.

===DONE===