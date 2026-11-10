Breakpoints:
- xs: 0–479px
- sm: 480–767px
- md: 768–1023px
- lg: 1024–1439px
- xl: 1440px+

Rules:
- Container max-width 1280px; side padding 16px xs/sm, 24px md, 32px lg/xl.
- xs: single column, collapsed navigation, stacked cards and controls, result rows instead of table.
- sm: one-column content, two-column summary where space permits.
- md: optional two-column detail layout; controls share a row only if each remains at least 160px.
- lg/xl: three-column summary grid, visible table columns, persistent detail panel with 320px minimum width.
- Keep 44px touch targets and 8px target gaps at every width.
- Preserve reading order: heading → controls → results → detail.
- Avoid horizontal scrolling for primary actions and essential status.
- Do not reduce body text below 14px; reduce decorative spacing first.
- Reduced-motion mode removes nonessential transitions and animated progress.