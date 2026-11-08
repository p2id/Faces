# Section D — Performance Budgets

- Largest Contentful Paint: ≤2.5s.
- First Contentful Paint: ≤1.8s.
- Interaction to Next Paint: ≤200ms.
- Cumulative Layout Shift: ≤0.1.
- Initial meaningful shell: ≤1s.
- JavaScript per initial route: ≤170KB compressed.
- CSS per initial route: ≤50KB compressed.
- Fonts: maximum 2 families, 4 files, 120KB compressed total.
- Primary images: ≤200KB each; use responsive sources and lazy loading below the fold.
- Initial requests: ≤50, excluding required platform requests.
- Long tasks: no initial main-thread task above 200ms.
- Lists: virtualize collections above 100 visible records.
- Search: debounce input by 200ms.
- Loading: reserve media space and preserve scroll position during updates.
- Monitoring: measure web vitals at all defined breakpoints.