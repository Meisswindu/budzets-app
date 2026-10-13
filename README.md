# Budžeta app (PWA)

Personal budgeting web app that reads/writes Markdown transaction files in a private Obsidian vault repo via the GitHub API.

**Note:** this repo contains only the app code — no tokens or data. Data lives in the private vault repo.

## Updating
Edit `index.html` and bump the `CACHE` version in `sw.js` (e.g. v1 → v2) so phones pick up the new version.
