# Plant Tracker Preview Build

Static Cloudflare Pages deploy artifact generated from the private Plant Tracker source repository.

Do not edit this repository by hand. Replace its contents with a freshly generated build from the private source repository when publishing a new preview.

## Cloudflare Pages

- Build command: leave blank
- Build output directory: `.`

This artifact includes:

- `robots.txt` disallowing all crawlers
- Cloudflare Pages `_headers` with `X-Robots-Tag: noindex, nofollow, noarchive, nosnippet`
- `noindex` robots meta tag in `index.html`
- SPA fallback in `_redirects`
- `package.json` and `package-lock.json` for Aikido dependency scanning
