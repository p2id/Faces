Budgets
- Initial JavaScript: <=170 KB compressed.
- Initial CSS: <=50 KB compressed.
- First contentful paint: <=1.8 s on mid-tier mobile.
- Largest contentful paint: <=2.5 s.
- Interaction to next paint: <=200 ms for common actions.
- Cumulative layout shift: <=0.1.
- Initial requests: <=35.
- Above-the-fold media: <=200 KB total.
- Font payload: <=100 KB; maximum two families and limited weights.
- Visible list interaction: at least 50 FPS; virtualize lists over 200 rows.
- Empty and error states render without optional assets.

Rules
- Lazy-load noncritical content.
- Reserve media and content dimensions before loading.
- Prefer transform and opacity for motion.
- Avoid layout-triggering animation.
- Use skeletons only for expected visible content.
- Verify budgets in a production-like build on a mid-tier mobile profile.