# Student Register Lookup

A minimalist, zero-scroll, responsive web application for looking up student records by **Name**, **Date of Birth**, **Admission Number (`Adm.NO`)**, or **Registration Number** across multi-sheet Excel registers (`Regn. & Adm.No..xlsx`).

## Features
- **Minimalist, Responsive Design**: Clean layout with color-coded tabs (`Search Register`, `Full Register`, `Excel & Pre-Bundle`) and color-coded search filter pills that adapt across mobile, tablet, and laptop viewports without horizontal scrollbars.
- **Dedicated Search & Smart Matching**: Supports instant search by **Name of Student**, **Date of Birth** (including `DD-MM-YYYY`, `DD/MM/YYYY`, `YYYY-MM-DD`, month names, Excel serial numbers, and a native calendar picker), **Adm.NO**, and **Registration**.
- **Excel Integration & Pre-Bundling**: Automatically detects and splits side-by-side register tables within worksheets, persists uploaded `.xlsx` / `.xls` / `.csv` files in IndexedDB, and lets you download a **Pre-Bundled HTML** file with your entire register embedded for direct GitHub Pages hosting.

## Deploying to GitHub Pages
1. Upload `index.html` and `README.md` to your GitHub repository.
2. Open **Settings → Pages** in your repository, select the `main` branch (`/ (root)`), and click **Save**.
3. Open your live GitHub Pages URL, load your full `Regn. & Adm.No..xlsx` under the **Excel & Pre-Bundle** tab, and optionally click **Download Pre-Bundled HTML** to commit an updated `index.html` containing all student records.
