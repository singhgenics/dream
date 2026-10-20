# Dream

Planning workspace for Cabin East (Wok | Steam | Draught), a small wok, dim sum and craft-beer pub in Betalbatim, South Goa.

## Design

The current design (no loft, 4.9 × 8.8 m shell, 28 covers) lives in its own repo: https://github.com/singhgenics/Simplex, live at https://singhgenics.github.io/Simplex/. The earlier loft concepts were dropped.

- `site-shell-3d.html`: the bare shell as found in `IMG_2772.MOV`. Live at https://singhgenics.github.io/dream/shell/ (`shell/index.html` is the Pages wrapper).
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
- `Drafts/`: no-loft render drafts (`r9_*.html`), fit-out checklist, ground-floor plan PDF (git-ignored).
- `Quotes/`, `TableSetting/`, `pos/`: vendor quote notes, table-setting page, point-of-sale app.
- `Links/`: the phone-friendly link index (`python3 links_build.py` inside the folder).

- `Menu-repo/` (singhgenics/Menu) and `Simplex/` (singhgenics/Simplex): separate git repos.
- `CabinEast/`: Cabin East logo, direction board and brand kit (source and build scripts; the published kit page is `Simplex/brand-kit.html`).
