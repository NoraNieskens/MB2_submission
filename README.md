MB2  submission

Title          : Analyse Tree species composition with time-series multispectral data  
Purpose        : This Script is written as a final project for the Programming and Geostatistical Analysis course (Eagle master programm, teacher Dr. Martin Wegmann     
Author         : Nora Nieskens 
Data           : Field data: Vascular plant species identity and their cover on each plot for Steigerwald and Uniforest (Source: ), Landcover raster based on Sentinel 2 from 2016 (Source: mundialis GmbH & Co. KG)             
                 Satellite data : Sentinel 2 data 2017: multi-temporal composite (will be generated in the script) of 10.05.2017,19.07.2017 and 23.08.2017
Output         : Spatial predicition of community composition (NDMS1, NDMS2) and species richness



This project was conducted in cooperation with Dr. So Yeon Bae (University of Würzburg). 
Tree species diversity and the community composition of trees is predicted. The study is based on field data about vascular plant species identity and their procentual cover of each plot in the area of Steigerwald and the forest belonging to the University of Würzburg. Using the species distribution data, a non-metric multidimensional scaling (NMDS) with Bray-Curtis distance metrics where conducted. "NMDS maps the position of sites in species space [...] onto a predefined small number of axes in an iterative search for an optimal solution." (Leutner et al. 2012)
Sentinel data is downloaded and preprocessed (L1C to L2A, mosaicing, stacking, cloud masking)  
