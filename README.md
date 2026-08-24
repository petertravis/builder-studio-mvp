# Builder Studio MVP

**▶ [Open the prototype](https://petertravis.github.io/builder-studio-mvp/)**

A clickable prototype of building an Asana app out of objects that already
exist in a workspace. Fictional company: **Northline**, a property manager.

## The flow

1. **Build** — bottom-left of the icon rail
2. **Apps** — the index of existing apps → *Create new app*
3. **Name it** — name, icon, colour
4. **Build tab** — a live app shell whose sidebar you edit directly: add
   sections, then add objects into them from a typeahead over 33 objects
   that already exist (portfolios, projects, tables, dashboards, pages,
   teams, goals). Drag to reorder objects, or whole sections.
5. **Settings tab** — general access and the list of app editors
6. **Publish** — hands the structure to the end-user experience

Use the numbered trail in the dark bar to jump between steps, or **Start
over** to reset.

## What's worth looking at

- The builder is **structural, not conversational** — there is no AI chat
  panel. An app is a curated arrangement of existing objects.
- Composition happens by **direct manipulation on the real nav**, not in a
  form that generates one.
- The five **Properties** groupings (All properties, Takeovers, New
  Developments, Stabilized, Separations) are *one table with five tabs* — a
  sidebar item deep-links to its tab.
- Clicking a property row opens the **record detail pane**.
- The three dashboards each serve a different audience: Portfolio Health
  (leadership), Leasing & Occupancy (leasing), Maintenance & Vendors
  (operations).
- Every dashboard figure is **derived** from the same record sets the
  tables render, so a chart cannot disagree with its table. The only
  illustrative series is the 12-month occupancy history, which terminates
  on the derived current value.

## Notes

- Single file, no build step. Vanilla HTML/CSS/JS; charts are inline SVG.
- Design tokens are the real Asana Falcon values (`falcon-tokens.css`);
  rail and sidebar glyphs are Figma exports.
- Not affiliated with, or endorsed by, any real company. All data is
  fictional.
