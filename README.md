# Bridge ML Project

Static GitHub Pages deployment package.

## Structure

- `index.html`
- `plan-a/index.html`
- `plan-a/data/plan_a_bridge_data.json`
- `plan-b/index.html`
- `plan-b/data/plan_b_reference_library.json`
- `README.md`
- `.nojekyll`

Plan A is the Germany bridge condition map.
Plan B is the bridge-type decision-support interface.

The interfaces run as static HTML/CSS/JavaScript. The large embedded DATA objects were moved into local JSON files and are loaded with relative browser `fetch()` calls.

Plan B is planning decision support based on comparable existing bridges; it is not structural design, FEM, dimensioning, code checking, or formal engineering approval.

The frozen condition model is not retrained or changed by this deployment package.
## Mobile UI

Plan A uses a responsive mobile layout: the map remains full-screen, filters collapse into a bottom sheet, and selected bridge details appear in a separate bottom card.
