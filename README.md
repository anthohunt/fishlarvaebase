# FishLarvaeBase

**A web application for exploring the pelagic dispersal traits of the early-life stages of marine fishes: eggs, hatching, growth, flexion, metamorphosis, settlement, swimming, vertical position, rafting, and specimen photographs.**

FishLarvaeBase (originally named LarvalBase) presents trait datasets compiled by Eliot Ruiz during his PhD at MARBEC (Montpellier) as a searchable website. Each species has a page that brings together its trait records, growth curves, distribution maps, photographs and references.

**Public version: [larvalbase.ingevision.cloud](https://larvalbase.ingevision.cloud)**

The datasets are private and cannot be shared publicly. The public version shows the structure of the website with an empty database. The source code is not published here.

![Home page](docs/screenshots/home.png)

## Who it is for

- Researchers parameterising biophysical dispersal and connectivity models, who need trait values such as pelagic larval duration, size at settlement or swimming speed for many species at once.
- Marine ecologists and fisheries scientists comparing life-history traits across species, genera or families.
- Larval fish taxonomists and field teams looking for reference photographs of post-flexion larvae and early juveniles.

## The website

**Home page.** Summary of the datasets, a world map of species coverage by province, the number of references per publication period, the number of taxa per trait, a map of settlement-stage sampling sites, and an entry to the photograph library.

**Search and filters.** A sidebar searches species by scientific or common name, with synonyms matched automatically, and browses the taxonomy as a tree (order, family, genus, species). The list can be filtered by trait availability, by biogeographic province on a map, and by adult ecosystem (marine, euryhaline, freshwater) and habitat (benthic, pelagic).

![Filters](docs/screenshots/filters.png)

**Species pages.** For each species: photographs with their source, growth curves, then the traits grouped by life stage (egg and incubation, pre-flexion, flexion, metamorphosis, settlement, vertical position, swimming speed, pelagic juveniles, rafting). Each quantitative trait is shown against the values of the same genus, family and order, so that a species without data can still be placed in context. The page also shows the adult distribution by province, a map of settlement sampling sites, and the list of references.

**Family pages and photograph library.** Galleries of specimen photographs by family, with uncertain, genus-level and family-level identifications marked separately, filterable by province on a map.

**Trait pages.** One page per trait with a map of species coverage by province and a description of the variable.

![Trait page](docs/screenshots/trait.png)

**Downloads.** Exports at several levels: all traits of a species, one section of a species page (optionally widened to the genus, family or order), all species of a family or of a province, or one trait filtered by province. Exports include the reference of each record.

The interface is available in ten languages (English, French, Spanish, Portuguese, German, Japanese, Chinese, Hindi, Arabic, Russian), and common names are shown in the selected language when available.

## Technology

| | |
|---|---|
| Application | Next.js 15, React 18, TypeScript |
| Interface | Tailwind CSS, shadcn/ui (Radix UI) |
| Charts | D3, Recharts |
| Maps | Leaflet, d3-geo, Spalding marine provinces |
| Data | plain-text tables parsed with Papa Parse and cached in memory on the server |
| Images | sharp for thumbnails and compression |
| Deployment | Docker, or Node.js with pm2 |

There is no database server: the website reads plain-text tables, so a new version of the datasets is deployed by replacing the files.

## Publications

> Ruiz, E., et al. (2026). Global pelagic dispersal traits datasets for early-life stages of marine fishes. *Scientific Data*, 13, 1291. https://doi.org/10.1038/s41597-026-07768-1

> Ruiz, E., et al. (2025). In situ estimation of active dispersal abilities in reef fish early life stages using tracking technologies. *Methods in Ecology and Evolution*, 16(4), 744–759. https://doi.org/10.1111/2041-210X.70011

## Credits

- **Eliot Ruiz** — datasets, scientific content and editorial direction. PhD thesis at MARBEC (University of Montpellier), defended on 25 November 2025.
- **Anthony Hunt** — design and development of the web application.

Affiliations shown on the website: MARBEC, IRD, ETH Zürich, Reefscapers, University of Montpellier, MNHN, Université des Antilles.

---

**Anthony Hunt** — [GitHub profile](https://github.com/anthohunt) · [anthony.hunt@yahoo.fr](mailto:anthony.hunt@yahoo.fr)
