Breakpoints:
- xs: 0–479px
- sm: 480–767px
- md: 768–1023px
- lg: 1024–1439px
- xl: 1440px and above

Rules:
- xs/sm: single column; navigation becomes a drawer; tables become stacked items or horizontal scroll; actions become full width.
- md: use two columns where space permits; navigation may collapse; filters wrap.
- lg/xl: persistent navigation; content max-width 1200px; summary cards use multiple columns; table actions remain inline.
- All widths: preserve reading order; prevent unintended horizontal overflow; keep body text at least 16px.
- Use 44px minimum interactive targets.
- Move secondary actions into an overflow menu when space is limited.
- Respect safe-area insets on narrow screens.
- Convert dialogs to full-screen sheets below 480px.
- Do not rely on hover for meaning or access.
- Reduce spacing below lg while preserving grouping and hierarchy.