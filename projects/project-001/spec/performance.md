# Performance Budgets
- Initial route: JavaScript ≤170 KB compressed; CSS ≤45 KB; fonts ≤100 KB; critical media ≤150 KB.
- Runtime: first contentful paint ≤1.8s; largest contentful paint ≤2.5s; interaction to next paint ≤200ms; cumulative layout shift ≤0.1; total blocking time ≤200ms.
- UI: loading placeholder within 100ms; search debounce 250ms; animation 150–250ms; reduced-motion alternative; virtualize collections over 100 visible rows.
- Delivery: lazy-load noncritical regions, compress media, reserve media/font space, cache immutable assets, measure compact/medium/expanded layouts.