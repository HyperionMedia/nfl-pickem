# Herzog Family Pick'em 2026

Single-file NFL pick'em pool: `index.html` (served via GitHub Pages).

- Shared picks/results state: npoint.io (see `DB_URL` in index.html)
- Schedule + logos embedded from ESPN (2026 season); live scores fetched client-side from ESPN's CORS-open API
- `index-src.html` is the template; rebuild by replacing `//__DATA_BUNDLE__` with the generated schedule/logo bundle
