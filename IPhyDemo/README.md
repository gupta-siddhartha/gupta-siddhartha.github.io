# ViPhyDemo

Interactive visualizations for plasma-physics phenomena: cosmic-ray-driven current
instabilities and charged-particle motion at a collisionless shock.

- `index.html` — landing page linking out to both dashboards below. If GitHub Pages is
  enabled for this repo (Settings → Pages → Deploy from branch `main` / root), it's served at
  `https://gupta-siddhartha.github.io/ViPhyDemo/`; otherwise open it locally in a browser.

## Contents

- `cr_instability_visualizer.html` — Bell instability dashboard. Standalone interactive
  3D solver/visualizer for the nonresonant CR-current-driven (Bell) instability, implementing
  the dispersion relation and field reconstruction from Gupta, Caprioli & Haggerty. Pure
  JavaScript physics engine — no build step or backend.
- `shock_particle_dashboard.html` — Particle-in-shock dashboard. Visualizes the motion of a
  charged particle crossing a quasi-perpendicular collisionless shock, integrated in 3D with a
  Boris pusher. Loads Three.js from a CDN; everything else is inline.

## Usage at a glance

- To browse both dashboards from one place: open `index.html` (or the GitHub Pages URL, once
  enabled).
- To view a single visualization: open the relevant `.html` file directly in a browser.

No Python runtime or build step is needed — every file here is self-contained.
