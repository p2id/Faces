# C. Product Experience Specification
- Date: 2026-11-17
- Project: project-001
- Surfaces: responsive web, compact mobile view, wide desktop view, keyboard navigation, screen-reader presentation.
- Sections:
  1. Header: product label, navigation, contextual action.
  2. Overview: page title, summary, primary action.
  3. Filters: search field, status filter, clear action.
  4. Collection: list or card grid with status, metadata, and actions.
  5. Detail: title, summary, attributes, related information.
  6. Feedback: loading, empty, validation, success, warning, and error messages.
  7. Footer: supporting links and version information.
- Content examples:
  - Title: “Workspace overview”
  - Summary: “Review recent activity and outstanding items.”
  - Primary action: “Create item”
  - Search placeholder: “Search items”
  - Filter: “Status: Active”
  - Item: “Quarterly planning” / “Updated 17 Nov 2026” / “Active”
  - Empty message: “No items match these filters.”
  - Error message: “Items could not be displayed. Try again.”
  - Success message: “Item created successfully.”
- Content rules: sentence case, concise labels, explicit verbs, neutral language, no fabricated urgency.
- Interaction rules: preserve context after actions; show validation beside the affected control; provide recovery for recoverable errors; confirm only irreversible actions.