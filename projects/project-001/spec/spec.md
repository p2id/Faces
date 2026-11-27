project_id: project-001
date: 2026-11-27
scope: generic neutral product experience

surfaces:
- application shell
- overview surface
- collection surface
- detail surface
- feedback surface
- overlay surface

sections:
- header: title, navigation, utility action
- overview: summary, metrics, filters
- collection: search, filter, table or list, pagination
- detail: title, metadata, grouped content, actions
- feedback: loading, empty, success, error
- overlay: dialog, toast, popover

real_content_examples:
- title: "Overview"
- summary: "Review current activity and recent changes."
- metric: "Active items — 24"
- search_label: "Search items"
- filter_label: "Status"
- filter_value: "All statuses"
- primary_action: "Create item"
- secondary_action: "Export list"
- empty_title: "No items found"
- empty_body: "Adjust the search or filters and try again."
- error_message: "Content could not be loaded. Try again."
- success_message: "Changes saved."
- cancel_action: "Cancel"
- confirm_action: "Confirm"

content_rules:
- Use sentence case and concise labels.
- Use explicit action verbs.
- Do not imply urgency without evidence.
- Preserve meaning at narrow widths and increased text size.
- Keep labels stable across surfaces.