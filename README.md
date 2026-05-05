# Personal website — Finnick Chen

## 在线网站（直接打开）

**网站链接：** [https://finnickchen.site/](https://finnickchen.site/)

把上面这一行发给老师/助教即可：在浏览器地址栏粘贴链接，或用 Ctrl/Cmd+单击打开。

---

## 中文说明

设计稿在 **Figma** 中完成，并发布为上述线上站点。本仓库是课程要求的 **HTML / CSS / JavaScript** 源码，视觉与 [finnickchen.site](https://finnickchen.site/) 一致（配色、字体、资源图）。

---

## Live site

**Published site:** [https://finnickchen.site/](https://finnickchen.site/)

This repository contains the static code version of the same personal site.

## What’s included

- `index.html` — single-page structure: hero, Work, About, header/footer
- `styles.css` — responsive layout and theming
- `script.js` — mobile navigation + footer year
- `assets/` — `logo.png`, `hero-bg.png`

## How to run this code locally

No build step—use any static file server.

### Python 3

```bash
git clone https://github.com/c4han-star/personal-web.git
cd personal-web
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

### Node (npx)

```bash
cd personal-web
npx --yes serve -l 8080
```

## Optional: GitHub Pages

After pushing this repo, enable **Settings → Pages → Deploy from branch** (e.g. `main` + `/root`) to get a `https://c4han-star.github.io/personal-web/` URL as a second demo.

## Customize

1. **LinkedIn** — in `index.html`, set your profile URL.
2. **Resume** — add `assets/resume.pdf` or update the Resume link.
3. **Email & bio** — edit the About section.

## License

You may use and modify this project for coursework and your portfolio.
