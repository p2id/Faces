## Breakpoints
- xs: 0–479px
- sm: 480–767px
- md: 768–1023px
- lg: 1024–1439px
- xl: 1440px+

## Rules
- Horizontal padding: 16px xs/sm, 24px md, 32px lg/xl.
- Content max-width: 1200px; reading measure: 80ch.
- xs/sm: single column, stacked actions, cards instead of tables where appropriate.
- md: two columns only when the primary region remains at least 60% width.
- lg/xl: allow persistent secondary panels and multi-column summaries.
- Navigation collapses below md with an accessible menu control.
- Summary cards: 1 column xs, 2 columns sm/md, 3–4 columns lg/xl.
- Dialog: viewport width minus 32px xs; maximum 560px md+.
- Minimum interactive target: 44×44px at all sizes.
- Required content reflows or scrolls; it is not hidden solely by viewport width.
- Support browser zoom and text scaling to 200% without loss of function.