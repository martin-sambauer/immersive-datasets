## Immersive Data Hub – datasets for immersive experiences and venues

Immersive Data Hub is a curated data library for immersive media and immersive experiences. It supports creative directors, producers, data scientists and strategists who work with planetariums, fulldome cinemas, XR venues and other forms of location-based entertainment.

The repository focuses on clean, well-documented datasets that can be used for market analysis, venue planning, audience development, experiential marketing and immersive storytelling.

The Immersive Data Hub is maintained by Creative Director Martin Sambauer (martin-sambauer.com). It connects structured venue data with strategic insights for immersive experiences, brand storytelling and innovation in immersive media.

---

## Repository structure

Suggested base structure:

* `datasets/`
  Ready-to-use CSV files.

* `notebooks/`
  Optional Jupyter or other analysis notebooks that show how datasets were created or how they can be used.

* `meta/`
  Methodology notes, data dictionaries and intermediate processing descriptions.

* `docs/`
  Material for public documentation or websites (figures, diagrams, excerpts).

Each dataset should be accompanied by at least a short description in this README or in a separate markdown file in `meta/`, including:

* data source(s)
* geographic and thematic coverage
* processing and cleaning steps
* field definitions
* date of last update

---

## License – CC BY 4.0

Unless explicitly stated otherwise in a subfolder, all original content in this repository is licensed under:

Creative Commons Attribution 4.0 International (CC BY 4.0)
[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

You are free to:

* share: copy and redistribute the material in any medium or format
* adapt: remix, transform and build upon the material for any purpose, even commercially

Under the following terms:

* attribution: give appropriate credit, provide a link to the license and indicate if changes were made.

A simple attribution example:

Immersive Data Hub by Martin Sambauer (martin-sambauer.com), licensed under CC BY 4.0.

If a dataset includes third-party content or has different terms, this will be documented in its folder.

---

## Typical use cases

The datasets in this repository are intended to support:

* immersive media strategy and concept development
* creative direction for fulldome and planetarium shows
* planning of immersive experiences and location-based entertainment
* venue and market mapping for XR, VR and mixed reality
* audience and catchment area analysis using demographic data
* storytelling, presentations and whitepapers on immersive experiences

Keywords that describe the focus of this repository include:
immersive media, immersive experiences, creative director for immersive media, fulldome, planetariums, XR venues, location-based entertainment, experiential marketing, immersive storytelling, venue planning, market analysis and audience development.

---

## How to update or add datasets with git

### 1. Fork and clone the repository

1. Fork the repository on GitHub to your own account.

2. Clone your fork:

   ```bash
   git clone https://github.com/<your-username>/immersive-data-hub.git
   cd immersive-data-hub
   ```

3. (Optional but recommended) Add the original repository as an upstream remote:

   ```bash
   git remote add upstream https://github.com/<original-owner>/immersive-data-hub.git
   ```

### 2. Create a feature branch

Create a branch for your change:

```bash
git checkout -b feature/update-dataset-planetariums
```

Use clear branch names, for example:

* `feature/add-new-dataset-<name>`
* `feature/update-venue-metadata`
* `fix/clean-duplicates-<dataset>`

### 3. Add or update the dataset

1. Place new or updated CSV files under `datasets/` in a logically named subfolder.

   Example:
   `datasets/osm-planetariums/planetariums_with_population_and_regions_v2.csv`

2. If you changed the structure or processing, update the documentation:

   * extend this README, and/or
   * add or update a markdown file in `meta/` with:

     * data sources
     * processing steps
     * field definitions
     * date and author of the update

3. Stage your changes:

   ```bash
   git status
   git add datasets/<your-folder> meta/<your-doc>.md
   ```

### 4. Commit your changes

Write a clear, short commit message:

```bash
git commit -m "Update planetarium dataset with population and region fields"
```

If you made several types of changes (for example, dataset update and documentation cleanup), consider splitting them into separate commits.

### 5. Push your branch

Push the branch to your fork:

```bash
git push origin feature/update-dataset-planetariums
```

### 6. Open a pull request

1. Go to your fork on GitHub.
2. Click "Compare & pull request".
3. In the pull request description, briefly explain:

   * what changed
   * which dataset(s) were affected
   * how the data was generated or cleaned
   * any known limitations or to-dos

After review and discussion, the branch can be merged into the main repository.

---

## Citing this repository

If you use the data for research, reports or presentations, please include a reference such as:

Immersive Data Hub, curated by Martin Sambauer (martin-sambauer.com).
Available at: [https://github.com/](https://github.com/)<owner>/immersive-data-hub
Licensed under CC BY 4.0.

---

## Contact

For questions, corrections or collaboration proposals related to immersive datasets, immersive storytelling and venue mapping, please get in touch:

* website: [https://martin-sambauer.com](https://martin-sambauer.com)
