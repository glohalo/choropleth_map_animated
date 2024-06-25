# choropleth_map_animated
An simple animated map with Python. This animation shows how solar irradiance levels change monthly within each "Departamento" in the Colombian Caribbean Region.

Remember create your toke in www.mapbox.com

The code is organized as follows:
1. Ingestion of the data as a layer (irradiation in the Colombian Caribbean Coast)
2. Preprocessing and imputation of values for missing continuity of datetime. The code tries to complete the continuity and then make the imputation by the man of the historical value for that department
3. A first view to check the type of data and expected behavior.
4. Ingestion of the base map, Colombia data for departments.
5. Data preprocessing filtering of the data for the Caribbean region
6. Finally, the base map and layer are integrated into the animation. The map created is a choropleth map with the avg of irradiation. For scatter plots you don't need a base map, you only need the base map for choropleth charts.
