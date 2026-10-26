Breakpoints:
- xs: 0–479px
- sm: 480–767px
- md: 768–1023px
- lg: 1024–1279px
- xl: 1280px+

Rules:
- Use a 4px spacing grid and fluid widths.
- xs: single column, 16px page padding, compact navigation, stacked actions, list rows become cards.
- sm: single column, 20px page padding, inline filters when space permits.
- md: optional two-column detail layout, 24px page padding, full navigation.
- lg: 1200px maximum content width, 32px page padding, summary cards in a row, persistent detail panel allowed.
- xl: 1280px maximum content width, 40px page padding, larger gaps without unnecessary text scaling.
- Dialog: width calc(100% - 32px) below md; maximum 560px at md+.
- Controls: minimum 44×44px touch target at every breakpoint.
- Wrap text before truncation; truncated values require an accessible full value.
- Preserve logical reading order when columns collapse.