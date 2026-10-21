# Luma Office

Luma Office is a lightweight Korean-language spreadsheet web app designed for desktop and mobile browsers.

## Current MVP
- 100 rows × 26 columns
- Cell editing and keyboard navigation
- Basic formulas: arithmetic, cell references, SUM, AVERAGE, MIN, MAX, COUNT
- Multiple sheets, basic bold/italic formatting, undo/redo
- CSV import/export

## GitHub Pages deployment
1. Open **Settings → Pages** and ensure the source is **GitHub Actions**.
2. Push to `main`; the workflow in `.github/workflows/pages.yml` deploys the static site.
3. After the first successful run, the site should be available at https://dds0188-code.github.io/luma-office/

## Limitations
This is an initial MVP, not an Excel replacement yet. XLSX/XLS import/export, richer formula parsing, persistent autosave, and full compatibility testing remain future work.
