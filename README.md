# preparedpath-site

Static website for [preparedpath.ngo](https://preparedpath.ngo) — a single
self-contained `index.html`. The chat API, model, and database live on
Cloudflare (Worker at api.preparedpath.ngo); this repo holds only the static
frontend.

Deployment: InMotion cPanel Git Version Control tracks this repo; pushes to
`main` deploy to the site's document root via webhook and `.cpanel.yml`.
