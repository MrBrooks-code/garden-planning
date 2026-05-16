# Meadow

A native-plant memorial garden in Racine, Wisconsin (USDA Zone 6a). 125 plants across 31 species, dedicated to recently-lost dogs.

The memorial plant is Wild Columbine — chosen because it self-seeds and returns in slightly different places each year, like memory.

## Pages

- **[index.html](index.html)** — landing page
- **[memorial_meadow_field_guide.html](memorial_meadow_field_guide.html)** — printable planting-day field guide (segment-by-segment placement, planting workflow, spacing reference, first-year care)
- **[memorial_meadow_plant_reference.html](memorial_meadow_plant_reference.html)** — dynamic species browser for the 31 design plants, with bloom timeline and filters
- **[sale_reference.html](sale_reference.html)** — sortable, filterable catalog of all 169 native species available at the sale, with size, spacing, and soil preferences
- **[swaps.html](swaps.html)** — sale day backup plan: recommended upgrades, irreplaceable plants, ranked substitution table, and a printable shopping checklist
- **[matrix.html](matrix.html)** — matrix planting concepts: the two layers, the pairs-to-random gradient from path-edge to interior, and how the method applies to each segment of the design

## Hosting (GitHub Pages)

To enable GitHub Pages on this repository:

1. Create an empty repository on GitHub (no README, no `.gitignore` — those already exist locally).
2. Add the remote and push:
   ```sh
   git remote add origin git@github.com:USERNAME/memorial-meadow.git
   git branch -M main
   git push -u origin main
   ```
3. Repository → **Settings** → **Pages** → Source: *Deploy from a branch*. Select `main` branch, `/` (root) directory. Save.
4. Wait a minute for the first build. The site URL appears at the top of the Pages settings (typically `https://USERNAME.github.io/memorial-meadow/`).

The `.nojekyll` file disables Jekyll processing so plain HTML files are served as-is.
