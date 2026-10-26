Global shell
- Anatomy: header, navigation, skip link, page container, main content, overlay layer.
- Variants: full navigation at md+, compact navigation below md.
- States: default, loading, empty, error.
- Usage: maintain consistent hierarchy and route context.
- Anti-patterns: changing navigation placement, hidden page title, overlays covering content.
- Accessibility: landmarks, skip link, logical headings, keyboard navigation.

Overview surface
- Anatomy: title block, primary action, summary cards, filter row, item collection, feedback region.
- Variants: populated, empty, filtered, loading, error.
- States: ready, refreshing, no-results, failed.
- Usage: place orientation before controls and content.
- Anti-patterns: unexplained controls, blank empty canvas, mixed action priority.
- Accessibility: labeled regions, announced result changes, preserved focus after filtering.

Item row
- Anatomy: status indicator, title, supporting metadata, optional action menu.
- Variants: compact, standard, selected.
- States: default, hover, focus-visible, selected, disabled, loading.
- Usage: keep title primary and metadata secondary.
- Anti-patterns: color-only status, ambiguous menus, clipped essential text.
- Accessibility: expose row name and status; provide distinct names for actions; support keyboard access.

Detail panel
- Anatomy: title, status, description, metadata, action group, close or back control.
- Variants: inline, side panel, dialog.
- States: viewing, editing, saving, saved, error.
- Usage: preserve originating context and show completion feedback.
- Anti-patterns: hidden close control, silent loss of changes, unclear action consequences.
- Accessibility: heading on entry, managed focus for overlays, associated errors, announced status updates.

Feedback region
- Anatomy: loading indicator, empty message, error message, recovery action.
- Variants: inline, full-region, toast.
- States: loading, empty, success, warning, error.
- Usage: explain the condition and the next available action.
- Anti-patterns: indefinite spinner, technical error text, visual-only feedback.
- Accessibility: appropriate live regions, text alternatives, sufficient contrast, reduced-motion support.