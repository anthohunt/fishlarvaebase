# FishLarvaeBase

**A web application for exploring the pelagic dispersal traits of the early-life stages of marine fishes: eggs, hatching, growth, flexion, metamorphosis, settlement, swimming, vertical position, rafting, and specimen photographs.**

FishLarvaeBase (originally named LarvalBase) presents trait datasets compiled by Eliot Ruiz during his PhD at MARBEC (Montpellier) as a searchable website. Each species has a page that brings together its trait records, growth curves, distribution maps, photographs and references.

**Public version: [larvalbase.ingevision.cloud](https://larvalbase.ingevision.cloud)**

The public version shows a sample of eight species with their real data and photographs. The full datasets are private and cannot be shared publicly, and the source code is not published here.

![Home page](docs/screenshots/home.png)

## Gallery

Post-flexion larvae and early juveniles of the eight species in the public sample, as shown on the website. Each photograph is credited to its source.

<table>
<tr>
<td width="50%" align="center"><img src="docs/gallery/amphiprion-ocellaris-1.jpg" width="100%" alt="Amphiprion ocellaris"><br><sub><i>Amphiprion ocellaris</i> (clown anemonefish) · © Baensch (2026)</sub></td>
<td width="50%" align="center"><img src="docs/gallery/amphiprion-ocellaris-2.jpg" width="100%" alt="Amphiprion ocellaris"><br><sub><i>Amphiprion ocellaris</i> (clown anemonefish) · © Baensch (2026)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="docs/gallery/chromis-viridis-1.jpg" width="100%" alt="Chromis viridis"><br><sub><i>Chromis viridis</i> (blue-green chromis) · © Current study (ADLIFISH 1)</sub></td>
<td width="50%" align="center"><img src="docs/gallery/chromis-viridis-2.jpg" width="100%" alt="Chromis viridis"><br><sub><i>Chromis viridis</i> (blue-green chromis) · © Current study (ADLIFISH 1)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="docs/gallery/dascyllus-trimaculatus-1.jpg" width="100%" alt="Dascyllus trimaculatus"><br><sub><i>Dascyllus trimaculatus</i> (threespot dascyllus) · © Current study (ADLIFISH 1)</sub></td>
<td width="50%" align="center"><img src="docs/gallery/dascyllus-trimaculatus-2.jpg" width="100%" alt="Dascyllus trimaculatus"><br><sub><i>Dascyllus trimaculatus</i> (threespot dascyllus) · © Current study (ADLIFISH 1)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="docs/gallery/dicentrarchus-labrax-1.jpg" width="100%" alt="Dicentrarchus labrax"><br><sub><i>Dicentrarchus labrax</i> (European seabass) · © Lecaillon et al. (2012)</sub></td>
<td width="50%" align="center"><img src="docs/gallery/dicentrarchus-labrax-2.jpg" width="100%" alt="Dicentrarchus labrax"><br><sub><i>Dicentrarchus labrax</i> (European seabass) · © Lenfant et al. (2022)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="docs/gallery/pagrus-major-1.jpg" width="100%" alt="Pagrus major"><br><sub><i>Pagrus major</i> (red seabream) · © Ulsan samplings (2025)</sub></td>
<td width="50%" align="center"><img src="docs/gallery/pagrus-major-2.jpg" width="100%" alt="Pagrus major"><br><sub><i>Pagrus major</i> (red seabream) · © Ulsan samplings (2025)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="docs/gallery/rhabdosargus-sarba-1.jpg" width="100%" alt="Rhabdosargus sarba"><br><sub><i>Rhabdosargus sarba</i> (goldlined seabream) · © Connell (2012)</sub></td>
<td width="50%" align="center"><img src="docs/gallery/rhabdosargus-sarba-2.jpg" width="100%" alt="Rhabdosargus sarba"><br><sub><i>Rhabdosargus sarba</i> (goldlined seabream) · © Connell (2012)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="docs/gallery/sparus-aurata-1.jpg" width="100%" alt="Sparus aurata"><br><sub><i>Sparus aurata</i> (gilthead seabream) · © Lenfant et al. (2022)</sub></td>
<td width="50%" align="center"><img src="docs/gallery/sparus-aurata-2.jpg" width="100%" alt="Sparus aurata"><br><sub><i>Sparus aurata</i> (gilthead seabream) · © Lenfant et al. (2022)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="docs/gallery/stegastes-partitus-1.jpg" width="100%" alt="Stegastes partitus"><br><sub><i>Stegastes partitus</i> (bicolor damselfish) · © Ruiz et al. (2024)</sub></td>
<td width="50%" align="center"><img src="docs/gallery/stegastes-partitus-2.jpg" width="100%" alt="Stegastes partitus"><br><sub><i>Stegastes partitus</i> (bicolor damselfish) · © Valdez-Moreno et al. (2010)</sub></td>
</tr>
</table>

## Who it is for

- Researchers parameterising biophysical dispersal and connectivity models, who need trait values such as pelagic larval duration, size at settlement or swimming speed for many species at once.
- Marine ecologists and fisheries scientists comparing life-history traits across species, genera or families.
- Larval fish taxonomists and field teams looking for reference photographs of post-flexion larvae and early juveniles.

## The website

**Home page.** Summary of the datasets, a world map of species coverage by province, the number of references per publication period, the number of taxa per trait, a map of settlement-stage sampling sites, and an entry to the photograph library.

**Search and filters.** A sidebar searches species by scientific or common name, with synonyms matched automatically, and browses the taxonomy as a tree (order, family, genus, species). The list can be filtered by trait availability, by biogeographic province on a map, and by adult ecosystem (marine, euryhaline, freshwater) and habitat (benthic, pelagic).

![Photograph library of a family](docs/screenshots/family-gallery.png)

**Species pages.** For each species: photographs with their source, growth curves, then the traits grouped by life stage (egg and incubation, pre-flexion, flexion, metamorphosis, settlement, vertical position, swimming speed, pelagic juveniles, rafting). Each quantitative trait is shown against the values of the same genus, family and order, so that a species without data can still be placed in context. The page also shows the adult distribution by province, a map of settlement sampling sites, and the list of references.

![Species page: photographs, adult distribution and traits](docs/screenshots/species.png)

![Species page: trait cards](docs/screenshots/species-growth.png)

**Family pages and photograph library.** Galleries of specimen photographs by family, with uncertain, genus-level and family-level identifications marked separately, filterable by province on a map.

**Trait pages.** One page per trait with a map of species coverage by province and a description of the variable.

![Photograph library](docs/screenshots/gallery.png)

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
