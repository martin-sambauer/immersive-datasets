## Immersive Datasets – structured data for immersive experiences and venues

Immersive Datasets is a curated data library for immersive media, immersive experiences and location-based entertainment.  
It provides structured datasets for:

- creative directors and producers  
- strategists and analysts  
- destination and venue managers  
- investors and investment researchers  
- policy makers and cultural planners  
- curriculum designers and educators  
- journalists and writers covering immersive media, culture, tourism and innovation  

Use cases range from venue planning and market analysis to soft-power strategy, educational design and narrative research on immersive ecosystems.

All datasets follow a unified ontological framework that formalizes how immersive ecosystems are described, categorized and interlinked.  
Immersive Datasets is maintained by Creative Director Martin Sambauer (martin-sambauer.com).

---

## Ontology and Semantic Framework

This repository follows the Martin Sambauer Ontology for Immersive Data Systems, which defines:

- core entity types (investors, destinations, creative roles, projects, skills, institutions, policies, regions)  
- semantic relationships across datasets  
- dialectical axes for modelling immersive ecosystems  
- the philosophical basis (homo medialis, constructivist perception, perceptual architectures)  
- principles for stacking datasets to generate higher-order analytical layers  

The ontology is located in the repository root:

[ontology.md](./ontology.md)

All datasets, schemas and methodologies are expected to conform to this ontology to ensure long-term interoperability and semantic consistency.

---

## Repository structure

Suggested structure:

- `datasets/`  
  Data folders with JSON, CSV or similar formats.

- `notebooks/`  
  Optional Jupyter notebooks demonstrating dataset generation or typical analyses.

- `meta/`  
  Methodologies, data dictionaries and documentation of intermediate processing steps.

- `docs/`  
  Public-facing documentation assets (figures, diagrams, excerpts).

Each dataset should include:

- a README describing purpose, scope and key results  
- a methodology file documenting data sources and processing steps  
- a JSON schema (for JSON-based datasets)  
- date of last update  
- author reference (martin-sambauer.com)

---

## License – CC BY 4.0

Unless stated otherwise, all original content is licensed under:

Creative Commons Attribution 4.0 International (CC BY 4.0)  
https://creativecommons.org/licenses/by/4.0/

You may:

- share: copy and redistribute the material  
- adapt: remix, transform and build upon it, even commercially

Under the condition:

- attribution: credit must be given to Martin Sambauer (martin-sambauer.com)

If a dataset includes third-party content, this is documented in its folder.

---

## Typical use cases

The datasets in this repository can be used for:

- immersive media strategy and concept development  
- creative direction for fulldome and planetarium shows  
- planning of immersive experiences and location-based entertainment  
- mapping immersive venues, ecosystems and market segments  
- investment screening and investor–destination matching  
- soft-power and tourism strategy in immersive infrastructures  
- curriculum and training design for immersive skills and creative roles  
- policy analysis related to cultural infrastructure and innovation programs  
- demographic and spatial analysis for catchment areas  
- storytelling, whitepapers and research on immersive ecosystems  
- data-driven pitch materials for destinations, venues and investors  

Core thematic keywords include:  
immersive media, immersive experiences, creative director for immersive media, fulldome, planetariums, XR venues, location-based entertainment, experiential marketing, immersive storytelling, venue planning, market analysis, audience development, soft power, cultural strategy.

---

## Updating or adding datasets with git

### 1. Fork and clone

```bash
git clone https://github.com/<your-username>/immersive-datasets.git
cd immersive-datasets
