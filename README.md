# nabn.github.io

| Path | Source | Build |
|---|---|---|
| `/` | `index.html` | static |
| `/ozttpstatuses/` | `ozttpstatuses/` | static |
| `/mermaid-viewer/` | `mermaid-viewer/` | Vite (`npm run build` → `dist/`) |

`.github/workflows/pages.yml` builds everything into `_site/` and deploys on push to `main`.

To add a project: drop a folder in, add a copy step to the workflow, and add it to `index.html` and `sitemap.xml`.
