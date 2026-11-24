# Breakpoints
- Base: 0–359px; one column, 16px page padding.
- Small: 360–767px; one column, 16–20px padding.
- Medium: 768–1199px; two-column layouts where useful, 24px padding.
- Large: 1200–1439px; max content width 1120px, 32px padding.
- Wide: 1440px+; centered max width 1280px, 40px outer padding.

## Rules
- Collapse header actions into overflow below 768px.
- Convert navigation to compact selector or horizontal scroll below 768px.
- Use one column below 768px, two at 768px, and three or four at 1200px.
- Prioritize table columns; move secondary data to detail below 768px.
- Use bottom-sheet dialogs and full-width drawers below 768px.
- Maintain 44×44px minimum targets at every width.
- Preserve reading order, focus order, contrast, and action prominence.
- Avoid essential horizontal scrolling; allow only dense data regions to scroll.
- Respect safe-area insets and reduced-motion preferences.