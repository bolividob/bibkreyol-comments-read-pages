# bibkreyol-comments-read-pages

Static JSON for **BibKreyol** daily comments reads (GitHub Pages mirror).

## URL pattern

`https://bolividob.github.io/bibkreyol-comments-read-pages/comments/daily/{yyyy-MM-dd}.json`

Same layout as Firebase Hosting / Cloudflare: path `comments/daily/` + UTC date filename.

## Deploy

Push JSON files to `comments/daily/` on `main`. GitHub Pages rebuilds automatically (legacy branch build).

See upstream app repo: `docs/github-pages/comments-read-static/README.md`.
