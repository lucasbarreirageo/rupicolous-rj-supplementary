<!--
  INSTRUÇÕES: substitua os campos entre colchetes [ ] pelos seus dados
  antes de publicar. Depois apague este comentário.
-->

# Supplementary Material — Threatened Rupicolous Flora of Rio de Janeiro

Interactive supplementary material for the article:

> [BARREIRA, A.L. et al.] ([2026]). *[Beyond land-use change: landslide susceptibility 
and rock-outcrop flora conservation]*. [Acta Botanica Brasilica].
> DOI: [DOI do artigo, quando disponível]

This repository hosts the interactive supplementary dataset accompanying a regional
IUCN Red List assessment of threatened rupicolous plant species (with emphasis on
Orchidaceae and Bromeliaceae) endemic to rock outcrops of the Atlantic Forest in the
state of Rio de Janeiro, Brazil.

## Live version

The navigable supplementary material is available at:

**https://[SEU_USUARIO].github.io/[NOME_DO_REPO]/**

Start from the master table (`00_Supplementary_Master_Table.html`); click any species
name to open its individual factsheet.

## Contents

| File | Description |
|------|-------------|
| `00_Supplementary_Master_Table.html` | Master synthesis table: all assessed species grouped by family, with Red List category distribution, threat synthesis, and links to each factsheet. |
| `Factsheet_<Genus>_<species>.html` | Individual factsheet per taxon: taxonomy, assessment justification, EOO/AOO, locations, threats (IUCN-CMP v3.3), protection status, interactive distribution map, and reference photographs. |

## How to use

Open the master table and use the search box and filters (category, family, protection
status) to locate taxa. Clicking a species name opens its full factsheet, including an
interactive distribution map (occurrence points, EOO and AOO polygons, and protected-area
boundaries). Each factsheet can also be opened directly by its filename.

## Data sources and methods

Spatial metrics — Extent of Occurrence (EOO) and Area of Occupancy (AOO, 2×2 km grid) —
and Red List categories follow the IUCN Red List Categories and Criteria v3.1 (Guidelines
v16, March 2024). Threats are classified according to the IUCN-CMP Threats Classification
Scheme v3.3. Occurrence records were compiled and filtered as described in the associated
article. Base maps are © OpenStreetMap contributors. Reference photographs are retrieved
from the Global Biodiversity Information Facility (GBIF); authorship and license are shown
per image.

## Technical notes

These are static HTML documents. An internet connection is required when viewing, because
the interactive maps load the Leaflet library and OpenStreetMap tiles, and photographs are
loaded from GBIF. No data is collected from users; the pages contain no tracking or
server-side code.

## Citation

If you use this material, please cite the associated article and this archived dataset:

> [SOBRENOME, Inicial.] ([ANO]). *Supplementary material — Threatened Rupicolous Flora of
> Rio de Janeiro* [Data set]. Zenodo. https://doi.org/[DOI_DO_ZENODO]

## License

- **Code and HTML documents:** [ex.: MIT License] (see `LICENSE`).
- **Assessment data and text:** [ex.: CC BY 4.0].
- **Photographs:** © respective authors, under the Creative Commons licenses indicated on
  each image (sourced from GBIF).
