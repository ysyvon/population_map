# Population Map Project

This project demonstrates GIS workflows in Python, including visualising and exporting populated place data using Geopandas and Folium.

## Features
- Load and manipulate shapefiles using Geopandas.
- Create interactive maps with Folium.
- Export filtered data as GeoJSON.

## Requirements
Install dependencies using:

pip install -r requirements.txt

## How to Run
Open notebooks/script.py.ipynb in Jupyter Notebook.
Follow the instructions to load data and create visualisations.

## Outputs
Processed data is saved in the outputs/ folder.
Example outputs include populated_places_points.geojson and an interactive map (populated_places_map.html).

## File Structure
```bash
Copy code
population_map/
├── data/                           # Raw input datasets
├── notebooks/                      # Jupyter Notebook(s)
├── outputs/                        # Processed data and results
├── .gitignore                      # Ignore unnecessary files
├── README.md                       # Project description
└── requirements.txt                # Python dependencies
