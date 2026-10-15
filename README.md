# BEL-E_graphs

Interactive isometric study figures for the BEL-E Notion workspace, built with the
[Anatomy](https://github.com/wheresryan22/anatomy) skill. Each figure explains one
technical concept as a real, working physical object, in a single self-contained HTML file.

Served via **GitHub Pages** so the figures can be embedded directly in Notion pages.

## Figures

| Concept | Subject | File |
|---|---|---|
| Hydraulic press (Pascal's law) | G5 Technology I | [`figures/hydraulic-press.html`](figures/hydraulic-press.html) |
| Double-acting cylinder + 4/2 valve | G5 Technology I | [`figures/pneumatic-cylinder.html`](figures/pneumatic-cylinder.html) |
| Packaging hierarchy (pallet → item) | G1 Logistics Systems | [`figures/packaging-hierarchy.html`](figures/packaging-hierarchy.html) |
| Spring scale (Hooke's law) | G5.1 Technical Mechanics | [`figures/spring-scale.html`](figures/spring-scale.html) |
| Strain-gauge load cell + Wheatstone bridge | G5 Technology I | [`figures/strain-gauge.html`](figures/strain-gauge.html) |
| High-bay warehouse + SRM | G1 Logistics Systems | [`figures/high-bay.html`](figures/high-bay.html) |

## Setup (one-time)

GitHub Pages: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`**.

Pages URL: `https://akramguediri.github.io/BEL-E_graphs/`

Embed a figure in Notion with an `<embed>` block pointing at its Pages URL, e.g.
`https://akramguediri.github.io/BEL-E_graphs/figures/hydraulic-press.html`
