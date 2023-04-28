# Geospatial Data Processing and Visualization

This project focuses on geospatial data processing and visualization using Python libraries like GeoPandas, Shapely, and Folium. The goal is to derive insights from a dataset with geographical information and create interactive maps for better understanding.

## Dataset

We will use the US Airports dataset, which contains information about airports in the United States. The dataset can be found at the following link:

[US Airports Dataset](https://ourairports.com/data/)

## Libraries

The following libraries will be used in this project:

- [GeoPandas](https://geopandas.org/): A library to work with geospatial data in a Pandas-like structure.
- [Shapely](https://shapely.readthedocs.io/): A library for manipulation and analysis of planar geometric objects.
- [Folium](https://python-visualization.github.io/folium/): A library to create interactive maps using Leaflet.js and Python.

## Project Structure

- `data`: This folder stores raw and processed data files.
- `notebooks`: This folder stores Jupyter notebooks for data exploration, processing, and visualization.
- `src`: This folder stores Python scripts and modules.
- `reports`: This folder stores generated reports, charts, and visualizations.
- `README.md`: This file contains project documentation.

## Getting Started

1. Set up a virtual environment and install the required libraries:

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt