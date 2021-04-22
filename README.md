# Geopython 2021 Tutorial - Introduction to GIS and Geospatial Analysis with Python 



### Instructors

- [Krishna Lodha](https://krishnaglodha.com)
This tutorial is an introduction to Geospatial Domain and its analysis using python. Since almost all industries are more or less connected to Location and mapping, it is important to spread awareness and literate developers to understand different aspects of the GIS (Geographic Information System) industry. The first Part of this series focuses on different GIS Data types and how to read them, This includes understanding different data formats such as Shapefiles, GeoJSON, WKT, CSV, TIFF, GeoTIFF, etc. . Users can actually read such files on their computers and be familiar with them. The second part of this series focuses on geospatial analysis with python. Users will first practice working with some core GIS functionalities using GDAL and OGR on the terminal (and later in python). After this, users will be familiarised with the most widely used geospatial python libraries such as pandas, geopandas, fiona, shapely, matplotlib, PySAL, rasterio .
Complete Series is divided into the following subtopics :

1. Introduction to GIS, GIS Data formats
2. Introduction and Installation of all Geospatial libraries in computer and in python environment
3. Working with GDAL and OGR capabilities
4. Spatial Operations and Relationships
5. Vector data analysis and visualization
6. Raster Data analysis and visualization
7. Working with Interactive Map in a python notebook
   

## Installation notes

Following this tutorial will require recent installations of:

- Python >= 3.5 
- pandas
- geopandas >= 0.3.0
- matplotlib
- shapely
- ipyleaflet
- GDAL-OGR
- [Jupyter Notebook](http://jupyter.org)

If you do not yet have these packages installed, we recommend to use the [venv]( https://docs.python.org/3/library/venv.html ) environment manager to install all the requirements 

Once venv is installed create env

```
python3 -m venv geopy2021 
```
once environment is create, activate it by following command
```
source geopy2021/bin/activate
```
All required packages can be installed by following command

```
pip install -r requirements.txt
```
