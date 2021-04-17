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

- Python >= 3.5 (it will probably work on python 2.7 as well, but I didn't test it specifically)
- pandas
- geopandas >= 0.3.0
- matplotlib
- rtree
- PySAL
- scikit-learn
- mgwr
- cartopy
- geoplot
- [Jupyter Notebook](http://jupyter.org)

If you do not yet have these packages installed, we recommend to use the [conda](http://conda.pydata.org/docs/intro.html) package manager to install all the requirements 
(you can install [miniconda](http://conda.pydata.org/miniconda.html) or install the (larger) Anaconda
distribution, found at https://www.anaconda.com/download/).

Once this is installed, the following command will install all required packages in your Python environment:

```
conda env create -f environment.yml
```

But of course, using another distribution (e.g. Enthought Canopy) or ``pip`` is fine as well (a requirements file is provided as well), as long as you have the above packages installed.


## Downloading the tutorial materials

**NOTE:** *We may update the materials up until the workshop. So, please make sure that, if you download the materials, you refresh the downloaded material close to the workshop.*

If you have git installed, you can get the tutorial materials by cloning this repo:

    git clone https://github.com/geopandas/scipy2018-geospatial-data

Otherwise, you can download the repository as a .zip file by heading over
to the GitHub repository (https://github.com/geopandas/scipy2018-geospatial-data) in
your browser and click the green "Download" button in the upper right:

![](img/download-button.png)


## Test the tutorial environment

To make sure everything was installed correctly, open a terminal, and change its directory (`cd`) so that your working directory is the tutorial materials you downloaded in the step above. Then enter the following:

```sh
python check_environment.py
```

Make sure that this scripts prints "All good. Enjoy the tutorial!"
