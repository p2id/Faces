Project: project-001
Date: 2026-11-21
Purpose: Generic product interface for reviewing information, selecting options, editing content, and confirming actions.

Surfaces:
- App shell: header, navigation, main content, utility region.
- Overview: summary, filters, item list, primary action.
- Detail: title, metadata, content, related actions.
- Form: labeled fields, validation, confirmation.
- Feedback: loading, empty, success, warning, error.

Sections:
- Header: “Workspace”; navigation “Overview”, “Details”, “Settings”; action “Help”.
- Overview: “Overview”; “Review current items and continue where needed.”
- Summary: “Total 24”, “Active 18”, “Needs review 3”.
- Filters: label “Status”; options “All”, “Active”, “Archived”.
- List: “Recent items”; “Quarterly plan”, “Release notes”, “Research summary”; “Updated 21 Nov 2026”.
- Detail: “Quarterly plan”; “Active”; “A concise plan for the next review period.”; actions “Edit”, “Save”.
- Form: “Title”, “Description”, “Status”; placeholder “Enter a title”; actions “Cancel”, “Save changes”.
- Feedback: “Changes saved.”, “Review the highlighted fields.”, “Something went wrong. Try again.”, “No items match these filters.”

Content rules:
- Use sentence case, concise labels, neutral language, and explicit outcomes.
- Keep one primary action per region.
- Pair status color with text or an icon.
- Preserve entered values after validation failure.