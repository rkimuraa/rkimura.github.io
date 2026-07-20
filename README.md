# robertokimura.github.io

Static personal site. No build step.

## Deploy on GitHub Pages

1. Create repo named `USERNAME.github.io` (or any repo).
2. Push these files to the root of `main`:
   ```
   git init
   git add .
   git commit -m "feat: personal site"
   git branch -M main
   git remote add origin git@github.com:USERNAME/USERNAME.github.io.git
   git push -u origin main
   ```
3. Settings → Pages → Source: `Deploy from a branch` → `main` / `root`.
4. Live at `https://USERNAME.github.io`.

## Files
- `index.html` — about + research interests + profile links
- `cv.html` — CV download + education
- `research.html` — publications and working papers
- `style.css` — shared styles
- `.nojekyll` — skips Jekyll processing

## Edit
Add a publication: copy a `.paper` block in `research.html`.
Swap the CV: change the link in `cv.html`.
