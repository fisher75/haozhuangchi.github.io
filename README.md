# Haozhuang Chi — GitHub Pages

This repo is a ready-to-publish personal website using the **Minimal Mistakes** Jekyll theme via `remote_theme`.

## Publish on GitHub Pages (recommended)
1. Create a repo named: **YOUR_GITHUB_USERNAME.github.io**
2. Upload all files in this folder to the repo root.
3. Go to **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
4. Wait for build → visit: `https://YOUR_GITHUB_USERNAME.github.io`

## What is already filled
- Home / About / Projects / Publications / CV pages
- Your photo as avatar
- Your CV PDF + IV paper PDF in `assets/`

## What you should customize next
- Update `_config.yml`:
  - Optionally add: GitHub link, Google Scholar link
  - If you buy a domain, set `url` and `baseurl`
- Add more project pages when ready (Cabin-WM, AU-TTC, DRAMA-X, etc.)

## Local preview (optional)
If you want local preview:
- Install Ruby + Bundler, then run:
```bash
bundle install
bundle exec jekyll serve
```
Local preview is optional — GitHub Pages can build it for you.

## Privacy note
Your email and phone are currently shown on the site because they are present in your CV.
If you prefer not to show your phone publicly, remove it from `index.md` and `_pages/cv.md`.
