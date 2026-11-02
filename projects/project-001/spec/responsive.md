Breakpoints:
- xs: 0–479px
- sm: 480–767px
- md: 768–1023px
- lg: 1024–1279px
- xl: 1280px and above

Rules:
- Use mobile-first layout.
- xs/sm: one column, 16px page padding, drawer navigation, stacked records, full-width primary actions when useful.
- md: 24px padding, collapsed navigation, optional two-column workspace, horizontal table scrolling.
- lg: 32px padding, persistent navigation, workspace plus 320px panel, inline actions.
- xl: 1440px maximum content width, workspace plus 360px panel, readable line lengths.
- Preserve reading order when columns collapse.
- Do not clip labels, errors, or entered text.
- Do not require hover for essential information or actions.
- Maintain 44px minimum touch targets.
- Keep modal content within the viewport with internal scrolling.
- Use container-aware components in variable-width regions.
- Respect safe-area insets for fixed mobile controls.
- Provide responsive cards or controlled scrolling for tables.
- Move nonessential actions to overflow while retaining primary actions.