# Portfolio

Personal portfolio site for Yash Sri Raj Gudivada — ML and GenAI engineer, M.S. Applied Machine Learning, University of Maryland.

A single self-contained page: all styles, scripts, and markup live in `docs/index.html`. The only external dependency is Google Fonts (Instrument Serif, Archivo, JetBrains Mono).

## Sections

`background` · `experience` · `projects` · `skills` · `contact`

## Running locally

Open `docs/index.html` in a browser, or serve that directory:

```bash
python -m http.server 8000 --directory docs
```

Then visit http://localhost:8000

## Links

- GitHub: https://github.com/yashraz23
- LinkedIn: https://linkedin.com/in/yashgdvd

## Hosting

The site is published from `docs/` to two places:

- **GitHub Pages** — https://yashraz23.github.io/portfolio/ — rebuilds automatically on every push to `main`.
- **Cloudflare Workers** — https://yashgudivada.yashgudivada231.workers.dev — deployed manually with `npx wrangler deploy` (see `wrangler.jsonc`).

Serving from `docs/` keeps repo files like this README out of both deployments.
