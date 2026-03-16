# Indian Air Traffic Network Analysis

This repository contains notebook-based analysis of passenger traffic between Indian cities, along with the raw monthly spreadsheets, processed lookup tables, and geospatial files used to visualize the network.

## Repository layout

- `data/raw/IndianAirways2015` to `data/raw/IndianAirways2023`: monthly passenger spreadsheets used as the source data.
- `data/processed/final_data.csv`: processed edge list with city IDs and latitude/longitude fields.
- `data/processed/ID_to_city.csv`: city ID lookup table with coordinates.
- `data/geospatial/`: additional shapefile assets kept with the project.
- `notebooks/Indian_Air_Traffic_Network_Analysis.ipynb`: main notebook for preprocessing, plotting, robustness analysis, and community detection.
- `references/maps_with_python/`: supporting notebook and mapping assets for choropleth and shapefile experiments.

## Getting started

1. Sync the project environment with `uv`:

   ```bash
   uv sync
   ```

2. Launch Jupyter through the managed environment:

   ```bash
   uv run jupyter lab
   ```

3. Open `notebooks/Indian_Air_Traffic_Network_Analysis.ipynb` in Jupyter.
