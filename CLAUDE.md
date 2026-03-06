# Site Psi Norberto

Professional website for psychologist Norberto Dantas, hosted on GitHub Pages.

## Stack

- Plain HTML files (no build step)
- Vanilla JavaScript for interactivity
- Vanilla CSS (separate `style.css` file)

## Deployment

Push to `main` branch triggers GitHub Pages deployment automatically. No CI/CD configuration needed.

## Architecture

Single `index.html` landing page. Additional pages may be added as separate `.html` files.
Styles live in `style.css`, linked via `<link rel="stylesheet" href="style.css">`.

No package.json, no bundler, no transpilation. Everything runs directly in the browser.

## Commands

None. Open `index.html` directly in a browser or use a local static server (e.g. `python3 -m http.server`).
