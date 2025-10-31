# FogCompliance-Ryda
Geospatial analysis of FOG(Fat, Oil and Grease) hotspots affecting wastewater compliance. This project maps food services businesses and sewer line blockages to identify areas of poor compliance and advocate for stronger enforcement policies.
License and citations: This project is licensed under [Creative Commons Attribution 4.0 International(CC BY 4.0).
Citation: Ryda, H. (2025). *Geospatial FOG hotspots assessment of major contributors to wastewater non-compliance*. GEOG587, University of Calgary.
Data source: City of Calgary Open Data Portal: Food Service Businesses, City Online Geodatabase: Sanitary Sewer Lines, City of Calgary Open Data: Water Main Breaks.
Methodes: Datas preparation- Filter datasets (2021–2024) Using City of Calgary Open Data Portal tools.Clean and georeference data using ArcGIS geoprocessing tools, Spatial analysis- Kernel Density Estimation and Spatial Join, Community-Level Analysis: gregate results by Calgary communities for localized compliance assessment, Compliance analysis- Compare blockage patterns with current surcharge-based compliance model (Bylaw 14M2012).
CRS: Coordinate Reference System (CRS)**: NAD 1983 UTM Zone 11N
Data formats: Shapefiles (.shp) for spatial data (Food Service Businesses, Sewer Lines), CSV for tabular data (Water Main Breaks)
Field dectionary: See `data/data_dictionary.md` for detailed field descriptions.
