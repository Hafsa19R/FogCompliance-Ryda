# Assesing Fog-Related Infrastructure Vulnerability in Calgary
**Authour** Hafsa Ryda
**Course** GEOG 587 - Geospital Project Managment
**license** Creative commons Attribution 4.0 International

## Project Overview
This project evaluates how **Fats, Oils, and Grease (FOG)** accumulation influences Calgary’s water infrastructure by analyzing:
- The correlation between **restaurant density** and **water main breaks**
- The spatial stress on **sanitary pipes and manholes** in high-density food service clusters
The analysis compares infrastructure vulnerability across communities (CityCenter and Brentwood) and demonstrates how the City can apply **hotspot analysis** to identify areas of elevated FOG discharge. These insights support strategies to **increase compliance** and reduce infrastructure risk by decreasing potential blockages at accumulation points—such as Citycenter where multiple restaurants discharge into the same manholes.
The goal is to inform **targeted compliance strategies** that reduce costly repairs and improve sustainability, aligning with **SDG 6: Clean Water and Sanitation**

## Objective
Assess whether restaurant density correlates with water main break frequency.
Identify sanitary system stress in high-density food service zones.
Highlight limitations in Calgary’s surcharge-based wastewater compliance model.
Advocate for stricter enforcement and proactive measures.


# Methods
### Software and Environment
- **ArcGIS Pro** (desktop) for geoprocessing and map production
- **ArcGIS Online** for data retrieval and visualization  
Projection: **NAD 1983 CSRS v2 Alberta 3TM (114°W)** as per cartographic standards

### Analytical Workflow
**Part 1: Water Main Break Correlation**
- **Spatial Join**: Linked food establishment points to community polygons to calculate restaurant density per community
- **Attribute Aggregation**: Summarized water main break counts per community from historical records
- **Scatterplot Analysis**: Plotted restaurant density against water main break frequency; computed **R²** to measure correlation
- **Interpretation**: Weak positive correlation (R² = 0.01), indicating minimal direct influence of restaurant density on water main failures

**Part 2: Sanitary System Stress Assessment**
- **Cluster Selection**: Chose **City Centre** (high density) and **Brentwood** (moderate density) for comparative analysis
- **Buffer Creation**: Generated **50 m buffers** around restaurants to approximate FOG discharge zones
- **Spatial Join**: Linked buffers to sanitary pipes to identify segments receiving multiple discharges
- **Manhole Clipping**: Extracted manholes within buffers; calculated **manhole-to-restaurant ratios** to assess chokepoint risk  
    - City Centre: ~6–8 manholes per restaurant → higher vulnerability  
    - Brentwood: ~11.5 manholes per restaurant → lower stress

**Techniques Applied**
- **Geoprocessing Tools**: Spatial Join, Buffer, Clip, Attribute Summarization
- **Visualization**: Scatterplot for correlation; thematic maps for buffer analysis
- **Quality Control**: Verified projection, symbology, and map elements (legend, scale bar, north arrow, source credits)

