# Data Dictionary

## Food_Service_Businesses.zip
- **Source**: City of Calgary Open Data Portal
- **Format**: Shapefile (.shp)
- **Description**: Locations of food service businesses categorized by type.
- **Fields**:
  - `business_type`: Dine-in, Take-out, Mixed
  - `address`: Business address
  - `license_status`: Active/Inactive
  - `geometry`: Spatial coordinates of business location

## Sanitary_Sewer_Lines.zip
- **Source**: City Online Geodatabase
- **Format**: Shapefile (.shp)
- **Description**: Calgary’s sanitary sewer network geometry.
- **Fields**:
  - `segment_id`: Unique sewer line ID
  - `diameter_mm`: Pipe diameter in millimeters
  - `material`: Pipe material type
  - `geometry`: Line geometry representing sewer segments

## Water_Main_Breaks.zip
- **Source**: City of Calgary Open Data
- **Format**: CSV
- **Description**: Historical water main break incidents.
- **Fields**:
  - `break_type`: A–S (e.g., A = circular break, C = corrosion)
  - `year`: Year of break occurrence
  - `location`: Coordinates or address of break
  - `severity`: Severity level of break 

## **Community_Boundaries.zip**
- **Source**: [City of Calgary Open Data] 
- **Format**: Shapefile (.shp)  
- **Description**: Polygon boundaries for Calgary communities used for spatial aggregation.  
- **Fields**:
  - **comm_name**: Community name  
  - **shape_area**: Area of the community polygon  
  - **geometry**: Polygon geometry representing community boundaries  

## **Water_Main_Map.zip**
- **Source**: [City of Calgary Open Data]
- **Format**: Shapefile (.shp)  
- **Description**: Calgary’s water main network geometry.  
- **Fields**:
  - **pipe_id**: Unique water main identifier  
  - **diameter**: Pipe diameter in millimeters  
  - **material**: Pipe material type  
  - **install_date**: Year of installation  
  - **geometry**: Line geometry representing water mains

  ## **Sanitary_Manholes.zip**
- **Source**: [City of Calgary Open Data] 
- **Format**: Shapefile (.shp)  
- **Description**: Locations of sanitary manholes across Calgary.  
- **Fields**:
  - **manhole_id**: Unique manhole identifier  
  - **location**: Coordinates of manhole  
  - **depth**: Depth of manhole (meters)  
  - **geometry**: Point geometry representing manhole location
  
