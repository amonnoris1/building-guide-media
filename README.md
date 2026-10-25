# Building Guide media API

Static media + catalog for Building Guide MCPE Trainer. Published via GitHub Pages.

- `GET /v1/index.json` — totals and endpoint map
- `GET /v1/builds.json` — full catalog (149 builds, step URLs rewritten to this domain)
- `GET /v1/categories.json` — category counts
- `GET /v1/media/builds/steps/{stepId}.webp` — step images (14224 files)

The iOS app bundles this catalog and loads step images from here.
