# samiurk70.github.io

Personal site for Samiur Rahman Khan. Two profile pages on one domain:

- **Research profile** → `https://samiurk70.github.io/` (for PhD applications)
- **Engineering profile** → `https://samiurk70.github.io/engineering.html` (for industry ML roles)

Same styling, same person, different emphasis. Each page has a subtle footer link to the other.

## Files

- `index.html` — research page (publications, research interests, projects framed as research)
- `engineering.html` — engineering page (shipped products first, production stack, publications demoted)
- `cv.pdf` — your research CV (drop this at the repo root)
- `cv-industry.pdf` — your industry CV (drop this at the repo root)

If you only have one CV PDF for now, duplicate it to both filenames so both pages have a working download link.

## Stack

Two static HTML files. EB Garamond and JetBrains Mono via Google Fonts. No build step, no framework, no dependencies.

## Deploy (GitHub Pages, five minutes)

1. On GitHub, create a new public repository named exactly `samiurk70.github.io` (must match your username). Do not initialise with a README on GitHub's side.
2. Locally:
   ```bash
   mkdir samiurk70.github.io
   cd samiurk70.github.io
   # drop index.html, engineering.html, README.md, cv.pdf, cv-industry.pdf into the folder
   git init
   git branch -M main
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/samiurk70/samiurk70.github.io.git
   git push -u origin main
   ```
3. On GitHub: **Settings** then **Pages** then **Source: Deploy from branch** then **main** then **/ (root)** then **Save**.
4. Wait two to three minutes. Both pages are live:
   - https://samiurk70.github.io
   - https://samiurk70.github.io/engineering.html

## Which URL goes on which CV

- On your **PhD / research CV**, put: `Website: samiurk70.github.io`
- On your **industry / ML engineering CV**, put: `Website: samiurk70.github.io/engineering.html`

A curious reviewer on either page can find the other via the footer link, but the landing page is tuned for the audience the CV targets.

## Update

Edit the HTML, commit, push. Changes go live in under a minute.
