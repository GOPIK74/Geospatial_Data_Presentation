# Geospatial_Data_Presentation

🚀 Exploring Digital Elevation Models (DEM) and Satellite Data for Geospatial Projects 🌍
Welcome to this repository! In 2024, satellite imagery and DEM data have become more accessible than ever, offering incredible potential for GIS and remote sensing projects. This repository focuses on exploring, analyzing, and processing different types of DEM data along with satellite imagery to extract meaningful insights.

📂 Project Structure
data/: Contains raw DEM data files from various sources like SRTM, ASTER, Copernicus, etc.
scripts/: Python scripts for DEM data processing, visualization, slope, and contour analysis.
notebooks/: Jupyter notebooks showcasing step-by-step analysis of DEM and satellite data.
output/: Processed outputs including slope maps, elevation models, and water body analysis.
🔑 Key DEM Datasets in 2024:
SRTM (Shuttle Radar Topography Mission):

Resolution: 30m, 90m
Global Coverage: Available via USGS Earth Explorer.
Price: Free.
ASTER GDEM:

Resolution: 30m
Availability: Global via NASA Earthdata.
Price: Free.
Copernicus DEM:

Resolution: 30m, 90m
Availability: Global focus, with an emphasis on Europe.
Price: Free under the Copernicus Open License.
ALOS World 3D (AW3D30):

Resolution: 30m
Availability: Global via JAXA.
Price: Free.
TanDEM-X:

Resolution: 12m
Availability: Commercial and scientific use.
Price: Varies by use case.
ArcticDEM:

Resolution: 2m to 10m
Availability: Arctic regions, continuously updated.
Price: Free.
🚀 Scripts and Tools Used:
GDAL: For DEM data manipulation, including mosaicking and clipping.
Rasterio: For reading and writing raster data.
Matplotlib: For data visualization.
leafmap: For interactive map visualizations.
Shapely/Geopandas: For handling vector data and spatial operations.
🚀 Key Analysis:
Slope and Contour Analysis: Using DEM data to extract slope maps and contour lines.
Watershed and Streamline Extraction: Identifying hydrological features from DEM.
Land Use and Land Cover (LULC) Classification: Using DEM and multispectral satellite data to classify regions based on terrain and land cover.
