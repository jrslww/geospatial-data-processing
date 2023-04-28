# Geospatial Data Processing and Visualization Project

This project focuses on processing and visualizing geospatial data related to airports in the United States. The dataset used in the analysis is the "airports.csv" file containing airport locations, types, and other attributes. The project demonstrates the use of Python libraries like GeoPandas, Shapely, and Folium for working with geospatial data formats, performing spatial operations, and creating interactive maps.

## Summary of Steps

1. Loading and preprocessing the dataset:
    - Imported the necessary libraries (GeoPandas, Shapely, Folium)
    - Loaded the raw dataset and filtered it to keep only US airports and non-military airports
    - Converted the dataset into a GeoDataFrame with the appropriate geometry

2. Exploring and visualizing the data:
    - Explored the dataset using descriptive statistics, checking for missing values, and examining unique values for categorical variables
    - Visualized the data using Folium to create an interactive map displaying the locations of airports

3. Performing spatial operations:
    - Found airports within a specified distance of a given location using Shapely
    - Visualized the nearby airports using Folium

4. Exporting the results:
    - Exported the GeoDataFrame containing the nearby airports to a shapefile for further analysis or use in other GIS applications

## Visualizations

- [Interactive map of all US airports](reports/airport_map.html)
- [Interactive map of nearby airports](reports/nearby_airports_map.html)

## Observations and Insights

- Patterns or trends in airport locations or types can be observed in the interactive maps.
- The distribution of airports across the United States is not uniform, with higher concentrations in certain areas.
- The majority of airports in the dataset are small or regional airports, with a smaller number of large international airports.

## Limitations and Challenges

- The search radius used in the analysis is in degrees, which may not accurately represent distances on the Earth's surface. A more precise distance calculation method, such as the Haversine formula, could be used for better results.
- The dataset may not include all airports in the United States or may have outdated information. Ensuring access to a comprehensive and up-to-date dataset would improve the analysis.

## Future Improvements

- Investigate relationships between airport locations and factors such as population density, economic activity, or physical geography.
- Analyze airport accessibility by calculating distances or travel times from nearby cities or transportation hubs.
- Incorporate additional geospatial datasets, such as road networks, land use, or environmental data, to enrich the analysis and provide a deeper understanding of the factors influencing airport locations.
