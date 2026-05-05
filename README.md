# Personal website — Finnick Chen

## Live site

**Open in your browser:** [https://finnickchen.site/](https://finnickchen.site/)

Paste the URL into the address bar, or Cmd/Ctrl-click the link above.

The visual design was created in **Figma** and published to that URL. This repository is the **HTML / CSS / JavaScript** source code for the same site (colors, typography, and image assets match the live version).

## Repository

**GitHub:** [https://github.com/c4han-star/personal-web](https://github.com/c4han-star/personal-web)

## What’s included

- `index.html` — single-page layout: hero, Work, About, header, footer
- `styles.css` — responsive layout and styling
- `script.js` — mobile navigation and footer year
- `assets/` — `logo.png`, `hero-bg.png`

## Run locally

No build step. Use any static file server.

### Python 3

```bash
git clone https://github.com/c4han-star/personal-web.git
cd personal-web
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

### Node (npx)

```bash
cd personal-web
npx --yes serve -l 8080
```

## Optional: GitHub Pages

In the repo on GitHub: **Settings → Pages → Build and deployment** — deploy from the `main` branch with folder `/ (root)` to get a URL like `https://c4han-star.github.io/personal-web/`.

## Customize

1. **LinkedIn** — set your profile URL in `index.html`.
2. **Resume** — add `assets/resume.pdf` or change the Resume link.
3. **Email and bio** — edit the About section.

## License

You may use and modify this project for coursework and your portfolio.
