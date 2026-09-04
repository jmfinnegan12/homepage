# algojimbo.com

Jim Finnegan's personal homepage — a single static HTML page, no build step.

- `index.html` — the page (all CSS inline).
- `assets/` — portrait (`jim.jpg`) and social-share card (`og.png`).
- `CNAME` — custom domain (`algojimbo.com`).

Deployed to GitHub Pages on every push to `v4` by `.github/workflows/deploy.yml`,
which just copies the static files into the Pages artifact (no npm, no framework).
