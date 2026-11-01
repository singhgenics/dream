# Dream

Planning workspace for Cabin East (Wok | Steam | Draught), a small wok, dim sum and craft-beer pub in Betalbatim, South Goa.

## Current focus: the Garden

All active design work is in the Garden repo (`Garden/web`, singhgenics/Garden): the 3D model, decor concept, equipment and stock plans, and now the menu site.

- Garden model: https://singhgenics.github.io/Garden/ (source `Garden/web/garden.html`)
- Decor concept: https://singhgenics.github.io/Garden/decor.html (source `Garden/Decor`)
- Menu site (copy of the Menu repo): `Garden/web/menu/`, live at https://singhgenics.github.io/Garden/menu/ once pushed. The original `Menu-repo/` (singhgenics/Menu) is kept untouched because its edit hook and build scripts use fixed paths.

## Brand pages: Simplex repo

The `Simplex/` repo (singhgenics/Simplex, https://singhgenics.github.io/Simplex/) now holds only the published brand kit and brand and merch pages. The old Betalbatim model, plans, BOQs, quotes and licences were removed on 2026-11-01 (they remain in that repo's git history).

- `index.html`: small landing page for https://singhgenics.github.io/dream/

## Menu

The food and drinks menus are separate, each with its own owner's notes and PDF.

- Menu chooser: https://singhgenics.github.io/dream/menu/
- Food menu: `food.html` (source) → `menu/food/index.html`, live at https://singhgenics.github.io/dream/menu/food/ · print: `menu-food.pdf` (front of the board, one A2 sheet)
- Drinks menu: `drinks.html` (source) → `menu/drinks/index.html`, live at https://singhgenics.github.io/dream/menu/drinks/ · print: `menu-drinks.pdf` (back of the board, one A2 sheet)
- Two-sided board: `menu-board.pdf`, food on page 1 (front) and drinks on page 2 (back), A2 portrait 420 × 594 mm, three columns per side

## Folders by topic

- `Finance/`: `Restaurant_Calculator.xlsx` (current unit economics, source of truth) and `Betalbatim_Restaurant_Dashboard.xlsx` (earlier dashboard, old numbers)
- `Research/`: `Dream.md` (original planning discussion), `Design-ideas/` (interior inspiration images and the site walkthrough video), `Reference/` (local reference images)
- `gmaps/`: competitor and market research and reports (kept at the root because its pages are published)
- `Legal/`: title deed, consent documents, rent agreement drafts (git-ignored, full-name copies stay local).
- `pos/`: point-of-sale app.
- `Links/`: the phone-friendly link index (`python3 links_build.py` inside the folder).

- `Menu-repo/` (singhgenics/Menu), `Garden/web` (singhgenics/Garden) and `Simplex/` (singhgenics/Simplex, brand pages): separate git repos.
- `CabinEast/`: Cabin East logo, direction board and brand kit (source and build scripts; the published kit page is `Simplex/brand-kit.html`).
