# bibkreyol-comments-read-pages

Static JSON for **BibKreyol** daily comments reads (GitHub Pages mirror).

## URL pattern

`https://bolividob.github.io/bibkreyol-comments-read-pages/comments/daily/{yyyy-MM-dd}.json`

Same layout as Firebase Hosting / Cloudflare: path `comments/daily/` + UTC date filename.

## Deploy

- **GitHub Actions** (`.github/workflows/sync-from-comments-data.yml`): hourly sync from [bibkreyol-comments-data](https://github.com/bolividob/bibkreyol-comments-data) + **Run workflow** manual button.
- **Legacy GitHub Pages:** each push to `main` rebuilds the site (no separate Pages Actions workflow).

`_headers` / `_routes.json` are for **Cloudflare Pages** if you connect this repo there; `github.io` does not read `_headers`.

See upstream app repo: `docs/github-pages/comments-read-static/README.md`.
