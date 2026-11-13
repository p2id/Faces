Budgets:
- Critical CSS: ≤50KB compressed.
- Initial JavaScript: ≤150KB compressed.
- Route-level JavaScript: ≤100KB compressed.
- Above-fold media: ≤150KB total.
- Largest Contentful Paint: ≤2.5s.
- First Contentful Paint: ≤1.8s.
- Interaction to Next Paint: ≤200ms.
- Cumulative Layout Shift: ≤0.1.
- Control readiness: ≤3s on a mid-tier mobile device.
- Initial requests: ≤25.
- Main-thread blocking task: ≤50ms.
- Visible list baseline: ≤100 rows without jank.

Rules:
- Reserve media dimensions.
- Defer non-critical code.
- Lazy-load below-fold content.
- Avoid layout shifts and unnecessary reflows.
- Keep loading indicators lightweight.
- Use skeletons only when they communicate meaningful structure.