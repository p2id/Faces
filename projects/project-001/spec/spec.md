Project: project-001
Date: 2026-10-27
Purpose: Generic product experience for browsing, filtering, reviewing, and configuring structured content.

Surfaces:
- App shell: navigation, header, utility actions, main content.
- Collection: title, controls, results, pagination.
- Detail: summary, attributes, related sections, actions.
- Overlay: modal, drawer, popover, tooltip.
- Feedback: loading, empty, success, warning, error.

Sections:
- Header: title, description, primary action.
- Controls: search, filters, sort, view switcher, reset.
- Results: cards or table with status, metadata, and actions.
- Detail: grouped information and secondary actions.
- Feedback: contextual status and recovery action.
- Footer: result count, pagination, optional supporting information.

Real content examples:
- Title: “Workspace overview”
- Description: “Review configured items and recent changes.”
- Primary action: “Create item”
- Search placeholder: “Search items”
- Filters: “Status”, “Category”, “Updated”
- Table headers: “Name”, “Status”, “Category”, “Updated”
- Rows: “Release plan” / “Active” / “Planning” / “27 Oct 2026”; “Review queue” / “Draft” / “Operations” / “26 Oct 2026”
- Empty: “No items match these filters.”
- Success: “Item created successfully.”
- Error: “Unable to load items. Try again.”
- Confirmation: “Delete item?” / “This action cannot be undone.” / “Cancel” / “Delete”

Content rules:
- Use sentence case, concise labels, explicit actions, and consistent terminology.
- Preserve entered values and context during state changes.
- Pair status color with text, icon, or structure.
- Prefer progressive disclosure to dense initial presentation.