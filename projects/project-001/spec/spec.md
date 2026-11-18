Date: 2026-11-18
Project: project-001
Scope: Generic product experience for reviewing and managing records.

Surfaces
- Desktop workspace: navigation, header, summary, controls, content, feedback.
- Tablet workspace: collapsible navigation, wrapped controls, content region.
- Mobile workspace: compact header, stacked controls, single-column content.
- Overlay layer: dialog, popover, tooltip, toast, banner.

Sections
1. Header: page title, description, primary action.
2. Navigation: Overview, Records, Activity, Settings.
3. Summary: Records, Needs review, Completed.
4. Controls: search, status filter, date range, clear filters.
5. Content: Recent records with Name, Status, Updated, Actions.
6. Empty state: no matching records and recovery action.
7. Error state: explanation and retry action.
8. Confirmation: title, consequence, cancel, confirm.
9. Feedback: success, warning, and error messages.
10. Footer: support and legal links.

Real content examples
- Title: Records
- Description: Review recent records and update their status.
- Search placeholder: Search records
- Status options: All statuses, Draft, In review, Complete
- Date options: Last 7 days, Last 30 days, Custom range
- Row: Quarterly review | In review | 18 Nov 2026 | View
- Primary action: Create record
- Secondary action: Export
- Confirmation: Confirm archive
- Body: This record will be removed from the active list.
- Success: Record archived
- Validation: Enter a valid date range.

Content rules
- Use sentence case, concise labels, explicit verbs, stable status names, and clear recovery actions.
- Never use color as the sole meaning carrier.
- Preserve entered values after validation failure.