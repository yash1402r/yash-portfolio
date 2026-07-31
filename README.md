# Yash Jitendra Kothari — Portfolio

A single-page, self-contained portfolio site. Works fully offline (open `index.html`) and on GitHub Pages.

## Live URL (once published)
`https://yash1402r.github.io/yash-portfolio/`

## Publish on GitHub Pages
1. Create a repo named **`yash-portfolio`** under the `yash1402r` account.
2. Push this folder (see commands below).
3. On GitHub: **Settings → Pages → Source: `main` branch, `/root`** → Save.
4. Wait ~1 min; the site goes live at the URL above (already linked from the résumé).

```bash
cd C:/CLaude/yash-portfolio
git remote add origin https://github.com/yash1402r/yash-portfolio.git
git branch -M main
git push -u origin main
```

## Add your own photos
Replace the gradient placeholders in the **Featured Work** section:
1. Drop images into the `images/` folder using the filenames shown on each card
   (`design-sprints.jpg`, `3d-printed-molds.jpg`, `assembly-sops.jpg`, `kickstarter.jpg`, `ev-kit.jpg`, `formula-student.jpg`).
2. In `index.html`, uncomment the `<img>` line inside that card's `.ph` block.

## Files
- `index.html` — the whole site (HTML + CSS + JS inline).
- `YASH_JITENDRA_KOTHARI_Resume.pdf` — downloadable résumé (linked from the site).
- `images/` — drop your work photos here.
