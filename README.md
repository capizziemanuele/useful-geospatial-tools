# Geospatial Tools

This is a list of Python geospatial tools and libraries that can be useful to GIS or EO users. It contains also references to Machine Learning and Deep Learning libraries.
The table shows:
- Name
- Documentation page
- GitHub repository
- Brief description

## :open_book: Geospatial lists

| Name | GitHub Repository | Description |
|:--------------------:|:-----------------------:|:-----------------:|
|Awesome Geospatial| <a href="https://github.com/sacridini/Awesome-Geospatial" target="_blank">GitHub link</a> | Long list of geospatial analysis tools. Geospatial analysis, or just spatial analysis, is an approach to applying statistical analysis and other analytic techniques to data which has a geographical or spatial aspect. |
|satellite-image-deep-learning| <a href="https://github.com/robmarkcole/satellite-image-deep-learning" target="_blank">GitHub link</a> | This repository lists resources on the topic of deep learning applied to satellite and aerial imagery. To a lesser extent classical machine learning techniques are listed, as are topics such as cloud computing and model deployment. |
|awesome-gee-community-datasets| <a href="https://github.com/samapriya/awesome-gee-community-datasets" target="_blank">GitHub link</a> | The awesome-gee-community-datasets are community-sourced geospatial datasets made available for use by the larger Google Earth Engine community and shared publicly as Earth Engine assets. |
|Awesome Earth Engine| <a href="https://github.com/giswqs/Awesome-GEE" target="_blank">GitHub link</a> | A curated list of Google Earth Engine resources. Please visit the Awesome-GEE GitHub repo if you want to contribute to this project. |
|Awesome-EarthObservation-Code| <a href="https://github.com/acgeospatial/awesome-earthobservation-code" target="_blank">GitHub link</a> | A curated list of awesome tools, tutorials, code, helpful projects, links, stuff about Earth Observation and Geospatial stuff. |

## :artificial_satellite: Earth Observation

| Name | Documentation | GitHub Repository | Description |
|:--------------------:|:-----------------------:|:-----------------:|:-----------------:|
|Raster4ML| <a href="https://raster4ml.readthedocs.io/" target="_blank">Doc link</a> | <a href="https://github.com/remotesensinglab/raster4ml" target="_blank">GitHub link</a> | Raster4ML is a python package that extracts machine learning ready dataset from geospatial raster data and shapefiles. The package aims to aid geospatial researchers and scientists to extract meaningful faetures easily and focus more on the model training or reproducibility issues. |
|ee| <a href="https://gee-python-api.readthedocs.io/en/latest/ee.html" target="_blank">Doc link</a> | <a href="https://github.com/google/earthengine-api" target="_blank">GitHub link</a> |Python and JavaScript client libraries for calling the Google Earth Engine API. |
|geemap| <a href="https://geemap.org/" target="_blank">Doc link</a> | <a href="https://github.com/giswqs/geemap" target="_blank">GitHub link</a> | A Python package for interactive mapping with Google Earth Engine, ipyleaflet, and ipywidgets.|
|eemont| <a href="https://eemont.readthedocs.io/en/latest/" target="_blank">Doc link</a> | <a href="https://github.com/davemlz/eemont" target="_blank">GitHub link</a> | A Python package that extends Google Earth Engine. |
|EODAG| <a href="https://eodag.readthedocs.io/en/latest/" target="_blank">Doc link</a> | <a href="https://github.com/CS-SI/eodag" target="_blank">GitHub link</a> | EODAG (Earth Observation Data Access Gateway) is a command line tool and a plugin-oriented Python framework for searching, aggregating results and downloading remote sensed images while offering a unified API for data access regardless of the data provider. |
|RSGISLib| <a href="http://rsgislib.org/rsgislib_zonalstats.html" target="_blank">Doc link</a> | <a href="https://github.com/remotesensinginfo/rsgislib" target="_blank">GitHub link</a> | The Remote Sensing and GIS software library (RSGISLib) is a collection of tools for processing remote sensing and GIS datasets. |
|sentinelhub| <a href="https://sentinelhub-py.readthedocs.io/en/latest/" target="_blank">Doc link</a> | <a href="https://github.com/sentinel-hub/sentinelhub-py" target="_blank">GitHub link</a> | The sentinelhub Python package is the official Python interface for Sentinel Hub services. It supports most of the services described in the Sentinel Hub documentation and any type of satellite data collections, including Sentinel, Landsat, MODIS, DEM, and custom collections produced by users. |
|EOEPCA System| <a href="https://eoepca.org/software/" target="_blank">Doc link</a> | <a href="https://github.com/EOEPCA" target="_blank">GitHub link</a> | "A selection of building blocks are available, addressing the three key domains identified in the architecture: Resource Management - catalogue and discovery of data and applications. Processing and Chaining - deployment and execution of applications. User Management - identity, security, access control and accounting" |
|MetPy| <a href="https://unidata.github.io/MetPy/latest/examples/index.html"  target="_blank">Doc link</a> | <a href="https://github.com/Unidata/MetPy" target="_blank">GitHub link</a> | MetPy is a collection of tools in Python for reading, visualizing and performing calculations with weather data. |
|Museo ToolBox| <a href="https://github.com/nkarasiak/MuseoToolBox"  target="_blank">Doc link</a> | <a href="https://museotoolbox.readthedocs.io/en/latest/?badge=latest" target="_blank">GitHub link</a> | Museo ToolBox is a python library to simplify the use of raster/vector, especially for machine learning and remote sensing. It is now easy to extract raster values from vector polygons and to do some spatial/unspatial cross-validation for scikit-learn from raster. |


## :earth_americas: GIS

| Name | Documentation | GitHub Repository | Description |
|:--------------------:|:-----------------------:|:-----------------:|:-----------------:|
|geopandas| <a href="https://geopandas.org/en/stable/" target="_blank">Doc link</a> | <a href="https://github.com/geopandas/geopandas" target="_blank">GitHub link</a> | GeoPandas is a project to add support for geographic data to pandas objects. |
|MGWR| - | <a href="https://github.com/pysal/mgwr" target="_blank">GitHub link</a> | This module provides functionality to calibrate multiscale (M)GWR as well as traditional GWR. It is built upon the sparse generalized linear modeling (spglm) module. |
|Shapely| <a href="https://shapely.readthedocs.io/en/stable/manual.html/" target="_blank">Doc link</a> | <a href="https://github.com/shapely/shapely" target="_blank">GitHub link</a> | Manipulation and analysis of geometric objects in the Cartesian plane. |
|rasterio| <a href="https://rasterio.readthedocs.io/en/latest/" target="_blank">Doc link</a> | <a href="https://github.com/rasterio/rasterio" target="_blank">GitHub link</a> | Rasterio reads and writes geospatial raster data. |
|rasterstats| <a href="https://pythonhosted.org/rasterstats/" target="_blank">Doc link</a> | <a href="https://github.com/perrygeo/python-rasterstats" target="_blank">GitHub link</a> | Python module for summarizing geospatial raster datasets based on vector geometries. It includes functions for zonal statistics and interpolated point queries. |
|WhiteboxTools| <a href="https://www.whiteboxgeo.com/manual/wbt_book/intro.html" target="_blank">Doc link</a> | <a href="https://github.com/jblindsay/whitebox-tools" target="_blank">GitHub link</a> | WhiteboxTools is an advanced geospatial data analysis platform. |
|whiteboxgui| <a href="https://whiteboxgui.gishub.org/" target="_blank">Doc link</a> | <a href="https://github.com/giswqs/whiteboxgui" target="_blank">GitHub link</a> | The whiteboxgui Python package is a Jupyter frontend for WhiteboxTools, an advanced geospatial data analysis platform. |
|pysal| <a href="https://pysal.org/" target="_blank">Doc link</a> | <a href="https://github.com/pysal/pysal" target="_blank">GitHub link</a> | PySAL, the Python spatial analysis library, is an open source cross-platform library for geospatial data science with an emphasis on geospatial vector data written in Python. |
|pykrige| <a href="https://geostat-framework.readthedocs.io/projects/pykrige/en/stable/" target="_blank">Doc link</a> | <a href="https://github.com/GeoStat-Framework/PyKrige" target="_blank">GitHub link</a> | Kriging Toolkit for Python. |
|geostat framework| <a href="https://geostat-framework.readthedocs.io/en/latest/" target="_blank">Doc link</a> | <a href="https://github.com/GeoStat-Framework/GeoStat-Framework.github.io/blob/master/docs/source/index.rst" target="_blank">GitHub link</a> | GeoStatTools is a library providing geostatistical tools like kriging, random field generation, variogram estimation, covariance models and much more. |
|gstools| <a href="https://geostat-framework.readthedocs.io/en/latest/#gstools" target="_blank">Doc link</a> | <a href="https://github.com/GeoStat-Framework/GSTools" target="_blank">GitHub link</a> | GeoStatTools provides geostatistical tools for various purposes. |
|Spatialpandas| <a href="-" target="_blank">Doc link</a> | <a href="https://github.com/holoviz/spatialpandas" target="_blank">GitHub link</a> | Spatialpandas provides Pandas and Dask extensions for vectorized spatial and geometric operations, such as fast, spatially indexed rendering of large collections of polygons, lines, or points. |
|GeoParquet| <a href="-" target="_blank">Doc link</a> | <a href="https://github.com/opengeospatial/geoparquet" target="_blank">GitHub link</a> | This repository defines how to store geospatial vector data (point, lines, polygons) in Parquet, a popular columnar storage format for tabular data. |
|SciKit GStat| <a href="https://scikit-gstat.readthedocs.io/en/latest/index.html" target="_blank">Doc link</a> | <a href="https://github.com/mmaelicke/scikit-gstat" target="_blank">GitHub link</a> | SciKit-Gstat is a scipy-styled analysis module for geostatistics. It includes two base classes Variogram and OrdinaryKriging. Additionally, various variogram classes inheriting from Variogram are available for solving directional or space-time related tasks. |
|R terra| <a href="https://cran.r-project.org/web/packages/terra/index.html" target="_blank">Doc link</a> | <a href="https://github.com/rspatial/terra" target="_blank">GitHub link</a> | terra is an R package for spatial data analysis. Methods for spatial data analysis with vector (points, lines, polygons) and raster (grid) data. Methods for vector data include standard operations such as intersect and buffer. Raster methods include global, local, zonal, and focal computations. The predict and interpolate methods facilitate the use of regression type (interpolation, machine learning) models for spatial prediction, including with satellite remote sensing data. Processing of very large files is supported. |

## :computer: Data Science & Machine Learning/Deep Learning

| Name | Documentation | GitHub Repository | Description |
|:--------------------:|:-----------------------:|:-----------------:|:-----------------:|
|SHAP| <a href="https://shap.readthedocs.io/en/latest/index.html" target="_blank">Doc link</a> | <a href="https://github.com/slundberg/shap/blob/master/docs/index.rst" target="_blank">GitHub link</a> | SHAP (SHapley Additive exPlanations) is a game theoretic approach to explain the output of any machine learning model. It connects optimal credit allocation with local explanations using the classic Shapley values from game theory and their related extensions. |
|gradio| <a href="https://gradio.app/" target="_blank">Doc link</a> | <a href="https://github.com/gradio-app/gradio" target="_blank">GitHub link</a> | Gradio is an open-source Python library that is used to build machine learning and data science demos and web applications. |
|Torchgeo| <a href="https://torchgeo.readthedocs.io/en/stable/" target="_blank">Doc link</a> | <a href="https://github.com/microsoft/torchgeo" target="_blank">GitHub link</a> | TorchGeo is a PyTorch domain library, similar to torchvision, providing datasets, samplers, transforms, and pre-trained models specific to geospatial data. |

## :gear: Interactivity & Visualization

| Name | Documentation | GitHub Repository | Description |
|:--------------------:|:-----------------------:|:-----------------:|:-----------------:|
|leafmap| <a href="https://leafmap.org/" target="_blank">Doc link</a> | <a href="https://github.com/giswqs/leafmap" target="_blank">GitHub link</a> | A Python package for geospatial analysis and interactive mapping in a Jupyter environment. |
|ipyleaflet| <a href="https://ipyleaflet.readthedocs.io/en/latest/" target="_blank">Doc link</a> | <a href="https://github.com/jupyter-widgets/ipyleaflet" target="_blank">GitHub link</a> | A Jupyter / Leaflet bridge enabling interactive maps in the Jupyter notebook. |
|ipywidgets| <a href="https://ipywidgets.readthedocs.io/en/latest/" target="_blank">Doc link</a> | <a href="https://github.com/jupyter-widgets/ipywidgets" target="_blank">GitHub link</a> | ipywidgets, also known as jupyter-widgets or simply widgets, are interactive HTML widgets for Jupyter notebooks and the IPython kernel. |
|folium| <a href="https://python-visualization.github.io/folium/" target="_blank">Doc link</a> | <a href="https://github.com/python-visualization/folium" target="_blank">GitHub link</a> | folium builds on the data wrangling strengths of the Python ecosystem and the mapping strengths of the leaflet.js library. Manipulate your data in Python, then visualize it in on a Leaflet map via folium. |
|voilà| <a href="https://voila.readthedocs.io/en/latest/?badge=latest" target="_blank">Doc link</a> | <a href="https://github.com/voila-dashboards/voila" target="_blank">GitHub link</a> | Rendering of live Jupyter notebooks with interactive widgets. |
|pyvista| <a href="https://docs.pyvista.org/" target="_blank">Doc link</a> | <a href="https://github.com/pyvista/pyvista" target="_blank">GitHub link</a> | PyVista is a helper module for the Visualization Toolkit (VTK) that wraps the VTK library through NumPy and direct array access through a variety of methods and classes. This package provides a Pythonic, well-documented interface exposing VTK's powerful visualization backend to facilitate rapid prototyping, analysis, and visual integration of spatially referenced datasets. |
|kepler.gl| <a href="https://docs.kepler.gl/docs/keplergl-jupyter" target="_blank">Doc link</a> | <a href="https://github.com/keplergl/kepler.gl/tree/master/bindings/kepler.gl-jupyter" target="_blank">GitHub link</a> | Kepler.gl is a data-agnostic, high-performance web-based application for visual exploration of large-scale geolocation data sets. Built on top of Mapbox GL and deck.gl, kepler.gl can render millions of points representing thousands of trips and perform spatial aggregations on the fly. |
|Datashader| <a href="https://datashader.org/" target="_blank">Doc link</a> | <a href="https://github.com/holoviz/datashader" target="_blank">GitHub link</a> | Datashader is a data rasterization pipeline for automating the process of creating meaningful representations of large amounts of data. |
|HoloViews| <a href="https://holoviews.org/" target="_blank">Doc link</a> | <a href="https://github.com/holoviz/holoviews" target="_blank">GitHub link</a> | HoloViews is an open-source Python library designed to make data analysis and visualization seamless and simple. With HoloViews, you can usually express what you want to do in very few lines of code, letting you focus on what you are trying to explore and convey, not on the process of plotting. |
|Panel| <a href="https://panel.holoviz.org/" target="_blank">Doc link</a> | <a href="https://github.com/holoviz/panel" target="_blank">GitHub link</a> | Panel provides tools for easily composing widgets, plots, tables, and other viewable objects and controls into custom analysis tools, apps, and dashboards. Panel works with visualizations from Altair, Bokeh, HoloViews, Matplotlib, Plotly, pydeck, PyVista and many other Python plotting libraries, making them instantly viewable either individually or when combined with interactive widgets that control them. |
|Mito Spreadsheets| <a href="https://docs.trymito.io/getting-started/installing-mito" target="_blank">Doc link</a> | <a href="https://github.com/mito-ds/monorepo" target="_blank">GitHub link</a> | Mito is a spreadsheet that lives inside your JupyterLab notebooks. It allows you to edit Pandas dataframes like an Excel file, and generates Python code that corresponds to each of your edits. |
|plotly| <a href="https://plotly.com/python/" target="_blank">Doc link</a> | <a href="https://github.com/plotly/plotly.py" target="_blank">GitHub link</a> | Plotly's Python graphing library makes interactive, publication-quality graphs. |

## :camera: 3D
| Name | Documentation | GitHub Repository | Description |
|:--------------------:|:-----------------------:|:-----------------:|:-----------------:|
|open3d| <a href="http://www.open3d.org/" target="_blank">Doc link</a> | <a href="https://github.com/isl-org/Open3D" target="_blank">GitHub link</a> | Open3D is an open-source library that supports rapid development of software that deals with 3D data. The Open3D frontend exposes a set of carefully selected data structures and algorithms in both C++ and Python. The backend is highly optimized and is set up for parallelization. |

## :wrench: Other Python libraries

| Name | Documentation | GitHub Repository | Description |
|:--------------------:|:-----------------------:|:-----------------:|:-----------------:|
|JupyterBook| <a href="https://jupyterbook.org/intro.html" target="_blank">Doc link</a> | <a href="https://github.com/executablebooks/jupyter-book" target="_blank">GitHub link</a> | Jupyter Book is an open-source tool for building publication-quality books and documents from computational material. |
|xarray| <a href="https://docs.xarray.dev/en/stable/" target="_blank">Doc link</a> | <a href="https://github.com/pydata/xarray" target="_blank">GitHub link</a> | xarray (formerly xray) is an open source project and Python package that makes working with labelled multi-dimensional arrays. |
|xarray-spatial| <a href="https://xarray-spatial.org/" target="_blank">Doc link</a> | <a href="https://github.com/makepath/xarray-spatial" target="_blank">GitHub link</a> | Xarray-Spatial implements common raster analysis functions using Numba and provides an easy-to-install, easy-to-extend codebase for raster analysis. xarray-spatial does not depend on GDAL / GEOS, which makes it fully extensible in Python but does limit the breadth of operations that can be covered. |
|rioxarray| <a href="https://corteva.github.io/rioxarray/stable/" target="_blank">Doc link</a> | <a href="https://github.com/corteva/rioxarray" target="_blank">GitHub link</a> | rioxarray extends xarray with the rio accessor. |
|Dask| <a href="https://dask.org/" target="_blank">Doc link</a> | <a href="https://github.com/dask/dask" target="_blank">GitHub link</a> | Dask is a flexible parallel computing library for analytics. |
|Geospatial| <a href="https://geospatial.gishub.org/" target="_blank">Doc link</a> | <a href="https://github.com/giswqs/geospatial" target="_blank">GitHub link</a> | A Python package for installing commonly used packages for geospatial analysis and data visualization with only one command. |

## Other useful tools
| Name | Documentation | GitHub Repository | Description |
|:--------------------:|:-----------------------:|:-----------------:|:-----------------:|
|MapColPal| <a href="https://mapcolpal.org/?seed=6690ff-cb6dce-ee665d-c58d00-66ad56-00b1ba" target="_blank">Doc link</a> | <a href="-" target="_blank">GitHub link</a> | This tool is here to help you work with color palettes for thematic maps. |

# Trainings

## GIS & Earth Observation

| Name | Link | Description |
|:--------------------:|:-----------------------:|:-----------------:|
|WEkEO| <a href="https://github.com/wekeo" target="_blank">Link</a> | Trainings provided by WEkEO DIAS. |
|Data Carpentry| <a href="https://carpentries-incubator.github.io/geospatial-python/" target="_blank">Link</a> | Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain. |
|Trainings list - EUMETSAT| <a href="https://training.eumetsat.int/course/index.php?categoryid=97" target="_blank">Link</a> | List of trainings and tutorials available from EUMETSAT. |
|Data Access Services - EUMETSAT| <a href="https://training.eumetsat.int/course/view.php?id=436" target="_blank">Link</a> | Tutorials and trainings about Data Access Services provided by EUMETSAT platform. |
|EUMETSAT Atlassian| <a href="https://eumetsatspace.atlassian.net/wiki/home" target="_blank">Link</a> | Information about EUMETSAT services, products, data format etc. |
|RUS Copernicus (Research and User Support)| <a href="https://rus-copernicus.eu/portal/the-rus-offer/training/" target="_blank">Link</a> | Trainings sessions and webinars provided by RUS Service. |
|EUMETSAT Training HUB - Jupyter Notebooks| <a href="https://trainhub.eumetsat.int/atmosphere/20_data_discovery" target="_blank">Link</a> | Jupyter notebooks available for satellite data processing and visualization. |
|Copernicus CAMS & C3S Jupyter Notebooks| <a href="https://github.com/ecmwf-projects/copernicus-training" target="_blank">Link</a> | This repository hosts Jupyter notebook training material for the Copernicus Climate Change Service (C3S) and the Copernicus Atmosphere Monitoring Service (CAMS). |
|LTPy - a Jupyter-based Learning Tool for Atmospheric Composition Datas| <a href="https://login.ltpy.adamplatform.eu/authentication/login/?next=/" target="_blank">Link</a> | LTPy is based on Jupyter notebooks and has a modular approach, with learning modules on data access, data processing, data visualization and a set of example workflows to support relevant atmospheric applications. |
|NASA Arset Trainings | <a href="https://appliedsciences.nasa.gov/join-mission/training" target="_blank">Link</a> | NASA Arset Training list related to multiple topics. |
|Copernicus Land Interactive Notebooks - Terrascope service| <a href="https://land.copernicus.eu/global/access" target="_blank">Link</a> | Interactive notebooks from Copernicus Land Terrascope. |
|geemap/leafmap tutorials| <a href="https://www.youtube.com/c/QiushengWu/videos" target="_blank">Link</a> | Youtube tutorial about geemap/leafmap and other tools/software.|
|ACGeospatial| <a href="https://github.com/acgeospatial" target="_blank">Link</a> |Earth Observation, Geospatial, GIS, Satellite imagery, Python, Julia, courses, training.|
|Pratt SAVI 810 - Intro to Python Scripting for Geospatial| <a href="https://github.com/pratt-savi-810" target="_blank">Link</a> |Introduction to Python Scripting for Geospatial analysis.|
|S5P-Tools| <a href="https://github.com/bilelomrani1/s5p-tools" target="_blank">Link</a> |Scripts to download and process air-pollution data collected by the satellite Sentinel-5P from the Copernicus Open Access Hub. The collect is based on the sentinelsat package and the API Hub Access. L3 resampling is made with HARP tools.|
|COURSE: Artificial Intelligence (AI) for Earth Monitoring| <a href="https://www.futurelearn.com/courses/artificial-intelligence-for-earth-monitoring" target="_blank">Link</a> |Explore how artificial intelligence (AI) and machine learning (ML) technologies are helping to advance Earth monitoring.|

## Computer Science

| Name | Link | Description |
|:--------------------:|:-----------------------:|:-----------------:|
|Computer Science courses| <a href="https://github.com/Developer-Y/cs-video-courses" target="_blank">Link</a> | Computer Science courses with video lectures. |