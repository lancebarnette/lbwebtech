# LB Web Tech

A fast, static, mobile-first public website for LB Web Tech. It serves as a QR-code-friendly digital business card and is ready for static deployment to Cloudflare Pages.

## Project structure

- `index.html` — page content and metadata
- `css/style.css` — mobile-first styles
- `js/main.js` — mobile navigation and footer year
- `favicon/favicon.svg` — site favicon
- `PLAN.md` — original implementation plan

## Run locally

```bash
cd lbwebtech
python -m http.server 8000
```

Then open `http://localhost:8000`.

No build system or dependencies are required. Edit page content in `index.html`, styles in `css/style.css`, and only the small progressive enhancements in `js/main.js`.
