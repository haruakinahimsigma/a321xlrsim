# A321XLR Systems Lab ✈️

A fullscreen, iPad-friendly cockpit prototype using the public Sketchfab embed for the 3D view and a custom HTML overlay for simulated aircraft systems.

## Current prototype
- Full-window Sketchfab cockpit viewer
- Responsive controls for BAT 1/2, EXT PWR, APU MASTER/START, IRS 1/2/3, and simplified engine states
- Custom ECAM-style status panel that updates when controls are pressed
- Reset to cold-and-dark, collapsible controls, ECAM toggle, and fullscreen button
- No build tools or package installation required: the prototype is a single `index.html`

## Preview
Open `index.html` locally or use GitHub Pages after enabling it for this repository.

To enable Pages: **Settings → Pages → Deploy from a branch → main → /(root) → Save**. The site will be served at `https://haruakinahimsigma.github.io/a321xlrsim/` once GitHub Pages finishes publishing.

## Important limitations
- The cockpit is an embedded Sketchfab viewer; the custom buttons are separate from the 3D model and do not physically move its switches.
- The simulation logic is intentionally simplified and is for experimentation only, not real-world flight training.
- The Sketchfab model remains hosted by its creator and is subject to its page/embed settings and license.
