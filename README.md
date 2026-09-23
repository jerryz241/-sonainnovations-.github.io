# SONA Innovations — VATARA Website

Marketing site for SONA Innovations, the U.S. commercial spinout of nonprofit [SONA Global](https://www.sonaglobal.org), built to market the VATARA portable suction device and consumables kit for uterine suction tamponade.

## Publishing to GitHub Pages

1. Create a new GitHub repo (e.g. `vatara-website`) and push this folder to it:

   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

2. On GitHub, go to the repo's **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Editing

- `index.html` — page content and structure
- `styles.css` — all styling
- `script.js` — mobile nav toggle + footer year
- `assets/` — logo and favicon (SVG)

No build step required — it's plain HTML/CSS/JS.
