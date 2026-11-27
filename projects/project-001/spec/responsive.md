breakpoints:
- compact: 0-599px
- medium: 600-959px
- expanded: 960-1279px
- wide: 1280px+

responsive_rules:
- Use mobile-first styles.
- Content padding: 16px compact, 24px medium, 32px expanded and wide.
- Shell: one column compact; two-region layout expanded and wide.
- Navigation: collapse secondary links compact; retain the current location label.
- Grid: one column compact, two medium, three expanded, four wide.
- Card minimum width: 240px.
- Filters: stacked compact; inline medium and above.
- Tables: transform to labeled cards below 600px when relationships remain clear.
- Actions: full-width compact; inline and right-aligned expanded and wide.
- Dialogs: full-height with 16px inset compact; max-width 560px medium and above.
- Typography: display 28/34 compact; 36/44 expanded; body 16/24 all sizes.
- Targets: minimum 44x44px at every breakpoint.
- Overflow: wrap labels; use horizontal scrolling only for genuinely tabular content.
- Never rely on hover-only actions or conceal essential content through truncation.