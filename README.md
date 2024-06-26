# choropleth_map_animated
An simple animated map with Python. This animation shows how solar irradiance levels change monthly within each "Departamento" in the Colombian Caribbean Region.

Remember create your free token in www.mapbox.com

The code is organized as follows:
1. Ingestion of the data as a layer (irradiation in the Colombian Caribbean Coast)
2. Preprocessing and imputation of values for missing continuity of datetime. The code tries to complete the continuity and then make the imputation by the man of the historical value for that department
3. A first view to check the type of data and expected behavior.
   
   ![image](https://github.com/glohalo/choropleth_map_animated/assets/28090029/f7185fa4-61b5-45a1-adf6-4c2a3701497f)

   
5. Ingestion of the base map, Colombia data for departments.
   
   ![image](https://github.com/glohalo/choropleth_map_animated/assets/28090029/fa83acb0-d8f3-4079-b3f1-3bbd0394ec7a)

7. Data preprocessing filtering of the data for the Caribbean region
   
   ![image](https://github.com/glohalo/choropleth_map_animated/assets/28090029/ed243dfa-47b5-4b86-a5e2-b12304c1cc74)
   
9. Finally, the base map and layer are integrated into the animation. The map created is a choropleth map with the avg of irradiation. For scatter plots you don't need a base map, you only need the base map for choropleth charts.
    <img width="915" alt="image" src="https://github.com/glohalo/choropleth_map_animated/assets/28090029/0056cf03-2d95-478f-ad5e-87da796949cb">
