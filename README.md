# samiurk70.github.io

Personal academic website for Samiur Rahman Khan.
Live at https://samiurk70.github.io

## Stack

Single `index.html` file. EB Garamond and JetBrains Mono via Google Fonts. No build step, no framework, no dependencies.

## Deploy (GitHub Pages, five minutes)

1. On GitHub, create a new public repository named exactly `samiurk70.github.io` (must match your username). Do not initialise with a README.
2. Locally:
   ```bash
   mkdir samiurk70.github.io
   cd samiurk70.github.io
   # drop index.html and this README.md into the folder
   # (optionally) drop cv.pdf into the folder so /cv.pdf resolves
   git init
   git branch -M main
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/samiurk70/samiurk70.github.io.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from branch → main → / (root) → Save**.
4. Wait two to three minutes. The site is live at https://samiurk70.github.io.

## Update

Edit `index.html`, commit, push. Changes go live in under a minute.

## Notes

- `cv.pdf` is referenced in the header and contact sections. Drop your latest CV PDF at the repo root with that exact filename.
- Google Scholar, LinkedIn, and GitHub URLs are hardcoded in `index.html` — update them if any change.
