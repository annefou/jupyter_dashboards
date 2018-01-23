---
title: "Interactive research"
teaching: 0
exercises: 0
questions:
- "How to use jupyter dashboards for our research project?"
objectives:
- "Understand how to add interactivity with jupyter dashboards and widgets"
keypoints:
- "Take a concrete example and illustrate how to use jupyter dashboards and widgets"
---


# Storyline

Laura is just starting her PhD program as part of the [Land-Atmosphere Interaction in Cold Environments](http://www.mn.uio.no/geo/english/research/groups/latice/) (LATICE) project at University of Oslo, Department of Geosciences, Norway. She is interested in exploring
field sites data from the [Finse Research Centre](http://finse.uio.no). [Finse Alpine Research Center](http://finse.uio.no) is located in the northwestern part of the Hardangervidda mountain plateau and is of great interest for scientists in particular biologists, geologists, geophysicists.  


<script src="https://embed.github.com/view/geojson/annefou/jupyter_dashboards/gh-pages/data/Hardangervidda.geojson"></script>


putting together her dissertation proposal as a part of her PHD program in ecology at University of Boulder, CO. She is interested in exploring some of her field sites to understand how phenology of vegetation (greening in the spring summer and senescence in the winter, varies across multiple sites and through time. Her PhD advisor has given her some data for a few sites which have very different vegetation communities including Harvard Forest (Massachusetts) and San Joachin Experimental Range (California). The data include:

Vegetation greenness (NDVI) derived from the Landsat Satellite (30 meter resolution) for both sites for 2 years derived from the landsat sensor in a raster format.
Some high resolution images of the sites.
A canopy height model showing tree height
A DEM (digital elevation model) showing topography.
Site temperature, PAR (Photosynthetic active radiation), Soil temperature, Precipitation and daylength for each day over those two years
Jessica has done some of the things above using her favorite open source GIS tool - QGIS. However that workflow makes it difficult to process and look at multiple years worth of data. She wants to create an efficient reproducible workflow that she can use as she collects data for more sites and years over time to support her dissertation work. She has never opened shapefiles and rasters in a non-gui environment. She also understands what a raster is but doesn’t know where the ndvi data come from.

Jessica would like to create the following outputs to better understand her project:

Plots of temperature, precipitation, PAR and daylength over the 2 year time period (metrics which related to the greening and browning of plants) compared to NDVI (greenness).
Basemaps of her site showing
The location of the tower that measured the above variables and imagery showing what the site look like.
Tree height
Topography
A time series animation of NDVI for both sites that she can post on her blog.
