# Dream

Planning workspace for Cabin East (Wok | Steam | Draught), a small wok, dim sum and craft-beer pub in Betalbatim, South Goa.

## Current focus: the Garden

All active design work is in the Garden repo (`Garden/web`, singhgenics/Garden): the 3D model, decor concept, equipment and stock plans, and now the menu site.

- Garden model: https://singhgenics.github.io/Garden/ (source `Garden/web/garden.html`)
- Decor concept: https://singhgenics.github.io/Garden/decor.html (source `Garden/Decor`)
- Menu: only the picture menu is kept, `Garden/menu/` (local folder; the published copy at https://singhgenics.github.io/Garden/menu/ is the last pushed version)

## Brand pages: Simplex repo

The `Simplex/` repo (singhgenics/Simplex, https://singhgenics.github.io/Simplex/) now holds only the published brand kit and brand and merch pages. The old Betalbatim model, plans, BOQs, quotes and licences were removed on 2026-11-01 (they remain in that repo's git history).

- `index.html`: small landing page for https://singhgenics.github.io/dream/

## Menu

Only the photo-led picture menu is kept: `Garden/menu/` (last pushed copy: https://singhgenics.github.io/Garden/menu/). Prices carry no rupee sign. The older menu, crockery, plating and board files were removed on 2026-11-03 and are in the Garden repo's git history.

## Folders by topic

- `Finance/`: `Restaurant_Calculator.xlsx` (current unit economics, source of truth) and `Betalbatim_Restaurant_Dashboard.xlsx` (earlier dashboard, old numbers)
- `Research/`: `Dream.md` (original planning discussion), `Design-ideas/` (interior inspiration images and the site walkthrough video), `Reference/` (local reference images)
- `gmaps/`: competitor and market research and reports (kept at the root because its pages are published)
- `Legal/`: title deed, consent documents, rent agreement drafts (git-ignored, full-name copies stay local).
- `pos/`: point-of-sale app.
- `Links/`: the phone-friendly link index (`python3 links_build.py` inside the folder).

- `Garden/web` (singhgenics/Garden) and `Simplex/` (singhgenics/Simplex, brand pages): separate git repos.
- `CabinEast/`: Cabin East logo, direction board and brand kit (source and build scripts; the published kit page is `Simplex/brand-kit.html`).
