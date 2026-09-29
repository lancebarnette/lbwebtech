# LB Web Tech

A fast, static, mobile-first public website for LB Web Tech. It serves as a QR-code-friendly digital business card and is ready for static deployment to Cloudflare Pages.

## Project structure

- `public/index.html` — page content and metadata
- `public/css/style.css` — mobile-first styles
- `public/js/main.js` — mobile navigation and footer year
- `public/favicon/favicon.svg` — site favicon
- `PLAN.md` — original implementation plan

## Run locally

```bash
cd lbwebtech
python -m http.server --directory public 8000
```

Then open `http://localhost:8000`.

No build system or dependencies are required. Edit page content in `public/index.html`, styles in `public/css/style.css`, and only the small progressive enhancements in `public/js/main.js`.
