# Running and publishing

This is a single static HTML page. Opening it redirects the browser to `https://google.com` with the page's URL fragment appended to the destination URL.

- Preview: run the `Start application` workflow (`python3 -m http.server 5000 --bind 0.0.0.0`).
- Publish: use the configured Static deployment. Its build command copies `index.html` to `dist/`, and `dist/` is the public directory. No packages or secrets are needed.