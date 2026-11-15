# Section C — Performance Budgets

- Critical initial payload: ≤200KB compressed.
- Initial JavaScript: ≤150KB compressed.
- Initial CSS: ≤60KB compressed.
- Fonts: ≤2 families and ≤4 files; prefer system fonts.
- Images: ≤100KB each by default, responsive and modern-format.
- LCP: ≤2.5s on mid-tier mobile.
- INP: ≤200ms for primary interactions.
- CLS: ≤0.1.
- FCP: ≤1.8s.
- Interactive content: ≤3.5s on constrained mobile.
- Above-the-fold DOM: under 1,500 nodes.
- Reserve media and async-content dimensions.
- Use skeletons only when content is expected after 300ms.
- Avoid autoplay, blocking third-party resources, unnecessary polling, and layout-shifting content.