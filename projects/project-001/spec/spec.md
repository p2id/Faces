# Product Experience Specification
- Date: 2026-10-22
- Project: project-001
- Scope: generic, neutral, reusable product interface.

## Surfaces
- Overview: summary, search, filters, recent items.
- Items: structured list, sorting, pagination, item actions.
- Detail: item summary, metadata, activity, actions.
- Settings: display, density, notification preferences.
- Feedback: validation, alerts, confirmations, empty and error regions.
- Compact layout: stacked content, condensed navigation, touch controls.

## Sections
1. Global navigation
   - Label: “Product”
   - Links: “Overview”, “Items”, “Settings”
   - Primary action: “Create item”
2. Overview
   - Heading: “Overview”
   - Description: “Review recent activity and manage items.”
   - Cards: “Total items”, “Needs attention”, “Completed”
   - Search: “Search items”
   - Filter: “Filter by status”
   - Empty message: “No items match the current filters.”
3. Items
   - Columns: “Name”, “Status”, “Updated”, “Actions”
   - Example row: “Sample item | Ready | 22 Oct 2026 | View details”
4. Detail
   - Heading: “Sample item”
   - Status: “Ready”
   - Sections: “Summary”, “Details”, “Activity”
   - Actions: “Edit”, “Archive”
5. Settings
   - Heading: “Settings”
   - Controls: “Theme”, “Density”, “Notifications”
   - Action: “Save changes”
6. Feedback
   - Success: “Changes saved.”
   - Validation: “Enter a valid value.”
   - Error: “Something went wrong. Try again.”
   - Confirmation: “Archive this item?”

## Content Rules
- Use sentence case, concise labels, explicit verbs, and neutral examples.
- Preserve essential text when content wraps or is unavailable.
- Never communicate status by color alone.