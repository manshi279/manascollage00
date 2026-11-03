# Manas College Pithoragarh – Smart Library Management System

## GitHub Pages testing
1. Upload `index.html`, `Code.gs`, and this `README.md` to your repository root (or use the included project folder contents).
2. Enable GitHub Pages from **Settings → Pages → Deploy from a branch → main → /(root)**.
3. Open the published URL. On first use, create your own password; there are no demo credentials.
4. Use **Export Data** to save a JSON backup and **Import Data** to restore one.

## Included requested changes
- Warm charcoal, sage and terracotta theme (not blue).
- Add New Book opens in a centered front modal.
- Student form omits phone and address; semester is limited to 1–6.
- Book field label is **Publisher / Place**.
- Password change and logout controls.
- JSON data import/export.
- Footer: **Powered by Manshi Joshi**.

## Important limitation
This GitHub Pages version stores library records and the password hash in the current browser's local storage. It is for testing only; it does not provide server-side authentication or shared multi-device data. Export backups regularly. The optional Google Apps Script file is included for a future cloud connection, but `API_URL` must be configured and deployed separately for sync.
