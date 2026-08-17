# .github
Organization-wide documentation of code resources and project repositories - last updated August 2026 by Annie Fu

Questions about these repositories: [urbanconservation@nybg.org](mailto:urbanconservation@nybg.org)

---

## In this repository

You’ll find (across NYBG-Conservation project repos — details live in each project README):

### Architecture

Per-project diagrams and stack notes: SvelteKit/MapLibre public maps and sites (Welikia, Layers of the Past, Urban Conservation Hub, storymaps, TFF frontend) and Django/PostGIS admin or API backends (microforests-db, TFF). This `.github` repo holds org-facing docs, not application code.

### Connecting to deployment (SSH / AWS / Vercel)

Each project README states how that app is reached: **Vercel** (most public SvelteKit sites), **AWS EC2 SSH + Docker** (microforests-db today; TFF planned), or **no deploy** (welikia-cleanup scripts). Do not assume one host for the whole org.

### Data cleaning / management pipeline

Pipelines differ by repo: GIS/script prep (welikia-cleanup → welikia-maplibre), Google Sheet → CSV (urban-conservation-hub), Django admin CSV/folder import (microforests-db, TFF), SharePoint/SDR geometry scripts (layers-of-the-past). See the matching section in the project README rather than duplicating procedures here.
