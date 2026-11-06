# C — Product Experience Specification
- Project: project-001
- Date: 2026-11-06
- Purpose: reusable interface for locating, reviewing, and updating product information.
- Surfaces:
  - Overview: navigation, heading, toolbar, collection, pagination.
  - Detail: summary, grouped fields, status, edit, close.
  - Feedback: inline validation, toast, confirmation dialog.
- Sections:
  1. Header: product title, page title, utility actions.
  2. Navigation: Overview, Activity, Settings.
  3. Toolbar: search, filters, sort, primary action.
  4. Collection: title, metadata, status, row actions.
  5. Empty/error area: explanation and recovery action.
  6. Detail area: summary, attributes, actions.
  7. Footer: version, help, legal links.
- Real content examples:
  - Page title: “Overview”
  - Search placeholder: “Search settings”
  - Filter: “Status”
  - Options: “All”, “Active”, “Archived”
  - Primary action: “Create item”
  - Collection item: “Notification preferences”
  - Metadata: “Updated 06 Nov 2026”
  - Status: “Active”
  - Empty message: “No items match these filters.”
  - Success message: “Changes saved.”
  - Error message: “Unable to save changes. Try again.”
  - Confirmation: “Archive this item?”
- Content rules: sentence case, literal labels, verb-led actions, inline recovery guidance, no color-only meaning, preserve entered values after errors.