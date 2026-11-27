performance_budgets:
- initial_js: <=170KB gzip
- initial_css: <=45KB gzip
- critical_font: <=100KB total
- largest_contentful_paint: <=2.5s on mid-tier mobile
- interaction_to_next_paint: <=200ms
- cumulative_layout_shift: <=0.1
- first_input_delay: <=100ms where measured
- above_fold_image: <=150KB per asset
- initial_requests: <=40
- collection_rendering: virtualize collections over 100 rows

implementation_rules:
- Reserve media dimensions before loading.
- Lazy-load below-fold media.
- Split secondary surfaces from the initial view.
- Prefer system fonts and immutable asset caching.
- Minimize nonessential scripts.
- Use tokenized CSS variables.
- Test compact and expanded layouts under throttled mobile conditions.
- Preserve skeleton geometry to avoid layout shift.