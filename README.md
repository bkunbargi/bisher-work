# bisher.work

Static site on GitHub Pages. No build step: edit the HTML and push to `main`.

- `book/index.html` is what the flyer's QR code opens, so its URL must not change.
  When online booking exists, add a "Pick a time" button linking to it (link out, don't redirect).
- DNS (GoDaddy): `@` A → 185.199.108.153, .109, .110, .111 (GitHub Pages); `www` CNAME → `bkunbargi.github.io`. Orbit lives at `orbit.bisher.work` (CNAME → `bisher-orbit.fly.dev`).
