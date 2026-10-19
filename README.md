# UP EV Charging Gap: Round 1 Proof of Concept

Live map: https://tejashx09.github.io/up-ev-gap-poc/

# What it shows: Uttar Pradesh districts coloured by four-wheeler EVs per publicly mapped charger (a visibility gap score). Blue dots are the 22 unique chargers found in open data.

# Data and method
- Chargers: OpenStreetMap (ODbL), pulled 18 Oct 2026. 230 raw records in the UP bounding box, 24 inside UP districts, 22 unique after a 100 m merge.
- EV registrations: VAHAN, UP by RTO and vehicle category, mapped to districts (rto_district_mapping.csv).
- Boundaries: DataMeet Census 2011 districts.
- Benchmark: 2,901 officially reported UP stations (Rajya Sabha reply, 01-03-2025). OSM captures about 0.8%.

# Limitations: open data under-counts chargers, boundaries are 2011 (four newer districts merged into their parents), and the score is a screening signal, not a measure of true supply.

# Files: index.html (map), top10_underserved.csv, rto_district_mapping.csv, COLAB_DISTRICT_DATA.ipynb (notebook).
