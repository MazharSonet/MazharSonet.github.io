# Md Mazharul Islam — Portfolio

Personal portfolio site for Md Mazharul Islam, Software Engineer (Backend, Distributed Systems & Full-Stack) based in Vancouver, BC.

**Live site:** [mazharsonet.github.io](https://mazharsonet.github.io)

## What's on the site

- **About:** 6 years building and operating distributed backend services, most recently at Microsoft
- **Experience:** Microsoft (Vancouver and Redmond), Edifecs, MuSyC Lab at Missouri State University, Synesis IT
- **Projects (AI/LLM & Research):** Interview Coach, an AI-powered interview practice platform, and SoCeR (IEEE COMPSAC 2020)
- **Skills and Education**
- **Resume:** downloadable PDF

The layout works on phones, tablets and desktops, and supports light and dark mode.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: markup, styles and scripts in one file |
| `assets/Mazhar-Resume.pdf` | Resume linked from the Download Resume button |
| `assets/profile.jpg` | Profile photo (480×480) |
| `sitemap.xml`, `robots.txt` | Help search engines find and crawl the site. Update `<lastmod>` in the sitemap after big content changes |

There's no build step, and the site is served directly by GitHub Pages from the `main` branch.

## Updating

- **Preview locally:** open `index.html` in a browser.
- **Resume:** replace `assets/Mazhar-Resume.pdf` with the new export, keeping the same file name.
- **Content:** edit the sections in `index.html`. To add a project, copy an existing `<article class="card project">` block. The marker comment in the AI/LLM group shows where the next project goes.
- **Publish:** commit and push to `main`. GitHub Pages updates the live site within a minute or two.
