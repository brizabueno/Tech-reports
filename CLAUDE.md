# Tech-reports

Daily automated "Tech Global Report" generation for this repository.

## Publishing convention

- Every report generation run must save/update `index.html` at the **repository root** with the latest report content (in addition to the dated/rolling copies under `reports/`). This lets GitHub Pages (or any static host pointed at the repo root) always serve the newest report at the site's base URL.
- Keep saving the rolling copy at `reports/tech-report-24h.html` and a dated copy at `reports/tech-report-YYYY-MM-DD.html` for history, as before.
- All three files (`index.html`, `reports/tech-report-24h.html`, `reports/tech-report-YYYY-MM-DD.html`) should have identical content for a given run.
