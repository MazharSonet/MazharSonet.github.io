# Md Mazharul Islam — Minimal Portfolio

Single-file, GitHub Pages–ready site.

## Quick Start (Personal site: `<username>.github.io`)

1. **Create a repo** on GitHub named exactly: `<your-username>.github.io` (e.g., `MazharSonet.github.io`).
2. Download this repo zip and extract it. Then push the files to that repo:

```bash
git init
git branch -M main
git add .
git commit -m "Initial commit: portfolio site"
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

3. Visit `https://<your-username>.github.io` after ~30–60 seconds.

## Alternative: Project site (any repo name)

1. Create a repo with any name (e.g., `portfolio`).
2. Push the files:
```bash
git init
git branch -M main
git add .
git commit -m "Initial commit: portfolio site"
git remote add origin https://github.com/<your-username>/portfolio.git
git push -u origin main
```
3. In **Settings → Pages**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / `/root`
4. Your site will be served at `https://<your-username>.github.io/portfolio/`.

## Custom Domain (optional)

1. Add your domain in **Settings → Pages → Custom domain** (e.g., `mazharsonet.dev`).
2. Create DNS records:
   - `A` records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `AAAA` records (optional) → `2606:50c0:8000::153`, `::/109::153`, `::/110::153`, `::/111::153`
3. (Optional) Add a `CNAME` file at the repo root containing only your domain:

```
mazharsonet.dev
```

## Resume PDF

Your resume is referenced at `assets/Mazhar-Resume.pdf`. Replace that file if you update your resume.

## Local Preview

Just open `index.html` in a browser. No build step, no tooling required.
