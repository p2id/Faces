Breakpoints:
- xs: 0–479px
- sm: 480–767px
- md: 768–1023px
- lg: 1024–1279px
- xl: 1280px and above

Rules:
- xs: single column; 16px page padding; navigation collapses; tables become stacked rows; dialogs use full width; actions stack.
- sm: single column with optional two-column form groups; 20px page padding; drawers use 90vw.
- md: two-column layouts where content permits; 24px page padding; navigation may remain compact; dialogs max 560px.
- lg: persistent navigation; two- or three-column content; 32px page padding; drawers max 420px.
- xl: content max-width 1200px; preserve readable line length; optional secondary panel; 40px page padding.
- All: maintain 44px minimum interactive target; wrap labels before truncating; use overflow scrolling for dense horizontal controls; preserve focus visibility; never rely on color alone.
- Tables: prioritize essential columns; move secondary values into row details below md.
- Forms: keep labels above controls; place related fields in groups only at md and above.
- Motion: reduce or remove nonessential transitions when reduced-motion preference is active.