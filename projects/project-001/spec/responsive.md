Breakpoints:
- xs: 0–479px
- sm: 480–767px
- md: 768–1023px
- lg: 1024–1279px
- xl: 1280px and above

Rules:
- Use 16px minimum gutters on xs/sm and 24px on md and above.
- xs/sm: single-column layout, collapsed navigation, stacked actions, full-width fields and dialogs.
- md: compact navigation; permit two-column detail layouts when readable.
- lg/xl: persistent navigation; constrain reading content to 720px; secondary panels up to 320px.
- Wrap toolbar controls below 768px; preserve search and primary action priority.
- Move low-priority filters into overflow controls on narrow screens.
- Tables retain essential columns, support horizontal scrolling, and expose row details without hover.
- Cards use one column on xs, two on sm/md, and additional columns only with 240px minimum card width.
- Maintain 44px minimum touch targets at every breakpoint.
- Respect safe-area insets on edge-to-edge surfaces.
- Support 200% zoom and reflow without clipped content or hidden essential actions.