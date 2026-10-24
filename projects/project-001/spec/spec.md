Project: project-001
Date: 2026-10-24
Purpose: Generic product experience for reviewing, filtering, and updating structured records.

Surfaces:
- Workspace: navigation, header, controls, summary, and record collection.
- Detail: focused record summary, metadata, notes, and actions.
- Overlay: dialog, drawer, popover, date picker, and tooltip.
- Feedback: inline messages, banners, toasts, loading, empty, and error views.

Sections:
1. Navigation: product label, primary links, current-location indicator.
2. Header: page title, description, primary action.
3. Controls: search, status filter, date range, sort, reset.
4. Summary: total records, active records, completion rate.
5. Collection: table or cards with name, status, updated date, value, actions.
6. Detail: title, status, updated date, notes, related actions.
7. System feedback: progress, empty result, error recovery, confirmation.
8. Utilities: pagination and display-density control.

Real content examples:
- Title: Activity overview
- Description: Review recent changes and current status.
- Search placeholder: Search records
- Filter: Status
- Filter values: All, Active, Paused, Completed
- Date label: Date range
- Primary action: Add item
- Secondary action: Export
- Metrics: Total items, Active items, Completion rate
- Empty message: No records match these filters.
- Error message: Information could not be loaded.
- Recovery action: Try again
- Confirmation: Item added successfully.
- Columns: Name, Status, Updated, Value, Actions
- Detail labels: Summary, Status, Last updated, Notes

Content rules:
- Use concise sentence-case labels and explicit action verbs.
- Pair irreversible actions with confirmation.
- Preserve entered values after validation failure.
- Provide a next step for empty, error, and loading states.