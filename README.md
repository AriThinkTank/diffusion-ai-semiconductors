# Diffusion and Power: an interactive model

Interactive companion to the Takshashila research paper *Diffusion and the Distribution of Power* (Arindam, High-Tech Geopolitics Programme, November 2026).

The site is a single file, `index.html`, with all data embedded. It needs no build step.

## Deploying on GitHub Pages
1. Create a new public repository and upload `index.html`, `.nojekyll` and the `data` folder.
2. In the repository, open Settings → Pages.
3. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, and save.
4. The site appears at `https://<your-username>.github.io/<repository-name>/` within a few minutes.

Each tab has its own address, for example `.../#simulator` or `.../#findings`.

## Data files
`data/` holds the estimation outputs behind the site: the 123-economy panel (`panel_5yr.csv`), the fitted S-curves (`scurve_internet.csv`), the cross-section used for the equations (`cross_section.csv`), all regression results (`results.json`) and the preset scenarios (`scenarios.json`). Sources: World Bank World Development Indicators, Microsoft AI Diffusion Report H2 2025, Stanford AI Index 2025, General Administration of Customs of China.
