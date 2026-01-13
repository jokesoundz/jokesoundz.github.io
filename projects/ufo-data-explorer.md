# 🛸 UFO Data Explorer

A data science project where I honed my Python skills by analysing real UFO sighting data and exploring the geography of where sightings *do* and *don't* occur.

## 🧠 Concept

This project started with a simple question:

***If UFO sightings cluster in certain places, where are the places that never see them?***

Using a global dataset of reported sightings, I focused on **location**, not the stories.  My initial ideas to generate an 'inverse map' using Voronoi diagrams to highlight regions furthest from any sighting.  When that approach proved computationally impractical, I pivoted to comparing UFO locations with other datasets of known sky anomalies such as meteors and fireballs, to explore how multiple layers of geospatial data might inform future research.

## 🧩 My Role

- Designed and exectured the full data exploration workflow
- Cleaned, transformed, and analysed geospatial datasets
- Experimented with Voroni-based mapping concepts
- Built visualisations using Python geospatial libraries
- Documented the process, decisions, and limitations in a Jupyter Notebook

## 🛠️ Tech Stack

python • Jupyter notebooks • pandas • geopandas • matplotlib & seaborn • folium • scipy

## 🔧 Process

### Goal

To explore the geography of UFO sightings and attempt to map the regions maximally distant from any reported sighting.

### Constraints

- Voronoi-based inverse mapping was computationally heavy for global-scale data
- Inconsistent formatting and missing values in the UFO dataset
- Time constraints for implementing a full geospatial pipeline

### Approach

- Cleaned and standardised the UFO dataset
- Plotted global sighting clusters using geopandas and folium
- Outlined a method for generating inverse Voronoi regions
- Pivoted to analysing additional datasets (meteors, fireballs, etc)
- Compared spatial patterns accross multiple phenomena
- Reflected on how these layers could support future research

### Key Decisions

- Prioritised documenting the Voronoi method rather than forcing an incomplete implementation
- Expanded the project scope to include meteor and fireball datasets
- Chose visual clarity over algorithmic complexity for the final maps
- Focused on exploratory insight rather than definitive conclusions

## 🎥 Media

## ⭐ Reflections

### What worked

- Clear documentation of both successful and abandoned approaches
- Strong use of Python's geospatial ecosystem
- Effective visualisations that reveal clustering patterns

### What I'd improve

- Implement a more efficient Voronoi pipeline using spatial indexing or tiling
- Explore machin-learning clustering methods for anomaly detection

### What I learned

- How to work with messy real-world geospatial data
- The limits of certain algorithms at global scale
- The value of pivoting when a method becomes impractical
- How layering multiple datasets can reveal richer patterns
