# Brick Intake

Phone-friendly tool for logging a LEGO haul: scan one brick, pick the colour from swatches,
enter the count, then export a Rebrickable CSV (Part, Color, Quantity).

- Identifies parts with the Brickognize API.
- Looks up valid colours per part with the Rebrickable API (free key, entered in Settings, stored only in the browser).
- No build step. The whole app is `index.html`.

## Publish with GitHub Pages
Settings > Pages > Deploy from a branch > `main` / `(root)`.
