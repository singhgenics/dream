# Dream

Planning workspace for Cabin East (Wok | Steam | Draught), a small wok, dim sum and craft-beer pub in Betalbatim, South Goa.

## Current focus: the Garden

All active design work is in the Garden repo (`Garden/web`, singhgenics/Garden): the 3D model, decor concept, equipment and stock plans, and now the menu site.

- Garden model: https://singhgenics.github.io/Garden/ (source `Garden/web/garden.html`)
- Decor concept: https://singhgenics.github.io/Garden/decor.html (source `Garden/Decor`)
- Menu (the one home for everything menu): `Garden/web/menu/`, live at https://singhgenics.github.io/Garden/menu/ . Menu data and A2 board PDFs in `source/`, photo menu in `picture/`, build and edit procedure in `UPDATE.md`.

## Brand pages: Simplex repo

The `Simplex/` repo (singhgenics/Simplex, https://singhgenics.github.io/Simplex/) now holds only the published brand kit and brand and merch pages. The old Betalbatim model, plans, BOQs, quotes and licences were removed on 2026-11-01 (they remain in that repo's git history).

- `index.html`: small landing page for https://singhgenics.github.io/dream/

## Menu

The menu lives only in the Garden repo: `Garden/web/menu/` (https://singhgenics.github.io/Garden/menu/). Prices carry no rupee sign. The printed A2 boards are rebuilt by `CabinEast/src/render_boards.sh` into `Garden/web/menu/source/`.

## Folders by topic

- `Finance/`: `Restaurant_Calculator.xlsx` (current unit economics, source of truth) and `Betalbatim_Restaurant_Dashboard.xlsx` (earlier dashboard, old numbers)
- `Research/`: `Dream.md` (original planning discussion), `Design-ideas/` (interior inspiration images and the site walkthrough video), `Reference/` (local reference images)
- `gmaps/`: competitor and market research and reports (kept at the root because its pages are published)
- `Legal/`: title deed, consent documents, rent agreement drafts (git-ignored, full-name copies stay local).
- `pos/`: point-of-sale app.
- `Links/`: the phone-friendly link index (`python3 links_build.py` inside the folder).

- `Garden/web` (singhgenics/Garden) and `Simplex/` (singhgenics/Simplex, brand pages): separate git repos.
- `CabinEast/`: Cabin East logo, direction board and brand kit (source and build scripts; the published kit page is `Simplex/brand-kit.html`).
