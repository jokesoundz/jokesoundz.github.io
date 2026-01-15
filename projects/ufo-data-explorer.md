# 🛸 UFO Data Explorer

A data science project exploring the geography of UFO sightings - and the gaps, biases, and unanswered questions hidden inside incomplete datasets.

## 🧠 Concept

This project began with a deliberately provocative question:

***Where in the world are UFO sightings not being reported - and what might those gaps mean?***

Rather than hunting for patterns in the sightings themselves, I focused on the _voids_: the regions with few or no reports, the inconsistencies in global data collection, and the limitations of drawing bold conclusions from imperfect information.  The notebook is both a technical exercise and a reflection on how data science can mislead when the dataset is patchy, biased, or incomplete.

My original plan was to generate an 'inverse map' using Voronoi diagrams to highlight the areas furthest from any reported sighting.  After outlining the method, I found the global-scale computation impractical - so I pivoted.  I brought in two NASA datasets (fireballs and meteorite landings) to compare known atmospheric events with reported UFO locations, exploring how multiple layers of sky-activity data might inform future research.

## 🧩 My Role

- Designed and executed the full data exploration workflow
- Cleaned and analysed multiple geospatial datasets
- Experimented with Voronoi-based mapping concepts
- Built maps and visualisations using Python geospatial libraries
- Reflected on data gaps, bias, and the limits of interpretation

## 🛠️ Tech Stack

Python • Jupyter notebooks • pandas • geopandas • matplotlib & seaborn • folium • scipy

## 🔧 Process

### Goal

To explore UFO sightings through the lens of _absence_, not presence - and to experiment with geospatial methods for mapping the 'quiet zones' of reported activity.

### Constraints

- Voronoi-based inverse mapping was computationally heavy for global-scale data
- UFO dataset contained inconsistencies, missing values, and uneven global coverage
- NASA datasets varied in resolution and format
- Time constraints for implementing a full geospatial pipeline

### Approach

- Cleaned and standardised the UFO dataset
- Mapped sightings year-by-year to reveal clustering
- Outlined a method for generating inverse Voronoi regions
- Pivoted to comparing UFO data with NASA meteor and fireball datasets
- Explored overlaps, mismatches, and what they imply about reporting bias
- Reflected on the philosophical side of 'unknown' vs 'unidentified'

### Key Decisions

- Documented the Voronoi method rather than forcing an incomplete implementation
- Expanded the project to include NASA datasets for richer comparison
- Chose visual clarity over algorithmic complexity for the final maps
- Emphasised the limitation of the data as part of the project's value

## 🎥 Media

<figure style="margin-bottom: 24px;">
  <img src="/assets/images/ufo-data-explorer/Voronoi-diagrams-explanation-trimmed.PNG" alt="screenshot of Voronoi diagram and code to build it">
  <figcaption style="text-align: center; font-size:0.9em; color:#666;">
    Code for building simple Voronoi diagrams
  </figcaption>
</figure>

<div style="display: grid; grid-template-columns: 1fr; gap: 16px; margin-bottom: 24px">
  <figure>
    <img src="/assets/images/ufo-data-explorer/fireball-data-map-with-anomaly.png" alt="map of fireball data with anomaly">
    <figcaption style="text-align: center; font-size:0.9em; color:#666;">
      Noticing an anomaly on the world map
    </figcaption>
  </figure>
  <figure>
    <img src="/assets/images/ufo-data-explorer/meteorite-on-mars.png" alt="screenshot of info about meteorite from mars">
    <figcaption style="text-align: center; font-size:0.9em; color:#666;">
      My anomalous datapoint was on mars!
    </figcaption>
  </figure>
</div>

<div style="display: grid; grid-template-columns: 1fr; gap: 16px; margin-bottom: 24px">
  <figure>
    <img src="/assets/images/ufo-data-explorer/comparitive-map-of-datasets-code.PNG" alt="code for building comparitive map">
    <figcaption style="text-align: center; font-size:0.9em; color:#666;">
      Code for building my comparitive map
    </figcaption>
  </figure>
  <figure>
    <img src="/assets/images/ufo-data-explorer/comparitive-map-of-datasets-map.PNG" alt="comparitive map made using matplotlib">
    <figcaption style="text-align: center; font-size:0.9em; color:#666;">
      My matplotlib map comparing datasets
    </figcaption>
  </figure>
</div>

  

## ⭐ Reflections

### What worked

- Honest documentation of both successful and abandoned approaches
- Clear visualisations that highlight clustering and absence
- A playful but thoughtful narrative about uncertainty and bias

### What I'd improve

- Implement a more efficient Voronoi pipeline using spatial indexing
- Bring in higher-resolution global datasets
- Explore clustering or anomaly-detection methods for cross-dataset comparison

### What I learned

- How to handle messy real-world geospatial data
- The limits of certain algorithms at global scale
- The importance of interrogating what's missing, not just what's present
- That exploratory analysis can be meaningful even without a definitive conclusion
