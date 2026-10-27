Breakpoints:
- xs: 0–479px
- sm: 480–767px
- md: 768–1023px
- lg: 1024–1279px
- xl: 1280px and above

Responsive rules:
- Use 100% width, 16px minimum side padding, and a 12-column grid from md upward.
- xs/sm: single column; navigation becomes a menu; tables stack or scroll horizontally; secondary actions move to overflow.
- md: navigation may collapse; cards use two columns when space permits.
- lg/xl: persistent navigation; content max-width 1440px; inline controls when they fit.
- Keep interactive targets at least 44px in every layout.
- Wrap or stack controls before shortening labels.
- Preserve reading order, focus order, and semantic grouping.
- Overlays use viewport width minus 16px margins on xs/sm and centered max-width on md+.
- Support a 320px minimum viewport without requiring horizontal scrolling for essential content.
- Use fluid spacing and type within token limits; avoid fixed-height content containers.