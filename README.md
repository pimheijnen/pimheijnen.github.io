# Pim Heijnen – personal website

Static HTML/CSS site (migrated from Google Sites), ready for GitHub Pages.

## Structure

- `index.html` – Home
- `publications.html`, `research.html`, `reports.html`, `cv.html`, `teaching.html`, `data.html`
- `personal.html` (Other stuff), `project-2000.html`
- `style.css` – shared styling (light and dark mode)
- `images/` – photos

The header/navigation is repeated in every page; when adding a page, copy an existing one and add a link to the `<nav>` in each file.

## Preview locally

    python3 -m http.server 8000

then open http://localhost:8000.

## Publish on GitHub Pages

1. Create a repository, e.g. `pimheijnen.github.io` (gives the URL https://pimheijnen.github.io).
2. Push these files to the `main` branch.
3. In the repository: Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
