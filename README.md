# Sehrish Fatima — Portfolio Website

A single-page profile site built from your CV: profile summary, research interests,
education, publications, professional experience, skills, conferences, awards, and references.

## Files
- `index.html` — the whole site (HTML + CSS + a little JS, no build step needed)
- `assets/sehrish.jpg` — your photo, pulled from the CV

## Deploy on GitHub Pages (free hosting)

1. Create a new repository on GitHub, e.g. `sehrish-fatima-portfolio`.
2. Upload `index.html` and the `assets` folder (keep the folder structure as-is) —
   either drag-and-drop on the GitHub website, or:
   ```bash
   git init
   git add .
   git commit -m "Add portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/sehrish-fatima-portfolio.git
   git push -u origin main
   ```
3. On GitHub: go to the repo → **Settings → Pages** → under "Build and deployment",
   set **Source** to "Deploy from a branch", branch **main**, folder **/(root)**, then Save.
4. GitHub will give you a live URL after a minute or two, usually:
   `https://<your-username>.github.io/sehrish-fatima-portfolio/`

## Editing later
Everything — text, colors, section order — lives in `index.html`. Colors and fonts are
defined once at the top of the `<style>` block under `:root{ ... }`, so changing a hex
value there updates the whole site.
