# Muhammad Zakaria Syed – Website / محمد زکریا سید کی ویب سائٹ

Static website (HTML + CSS + JS). Languages: Urdu, English, Arabic. Light / dark mode.

## Files
- `index.html` – the page
- `css/style.css` – styles
- `js/main.js` – language switch, light/dark, animations, galleries
- `images/` – all photos, flags (`images/flags/`) and favicon
- `files/jamia-ubaidia.pdf` – the PDF report (download button)

## Publish on GitHub Pages
1. Go to github.com, sign in, click **New repository** (name e.g. `zakaria-syed`, Public) and create it.
2. Click **uploading an existing file**. Unzip this package first, then drag **everything inside the folder** (index.html, css, js, images, files, .nojekyll) into the page. Click **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After 1–2 minutes your site is live at `https://YOUR-USERNAME.github.io/zakaria-syed/`.

`index.html` must stay in the root of the repository. Keep the folder names as they are.

## Notes
- Fonts load from Google Fonts, so an internet connection is needed for the intended fonts.
- To change text, edit the `T` object at the top of `js/main.js` (ur / en / ar).
