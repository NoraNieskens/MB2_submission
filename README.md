# Analyse tree species composition with time-series multispectral data  

This Script is written as a final project for the course "Programming and Geostatistical Analysis" (Eagle master programm, teacher Dr. Martin Wegmann) by Nora Nieskens 

Field data:      Vascular plant species identity and their cover on each plot for Steigerwald (2014) and Uniforest (2017) (Source: unpublished data provided by Jörg Müller (joerg.mueller@npv-bw.bayern.de))

Satellite data : Sentinel 2 data: multi-temporal composite (will be generated in the script) of 10.05.2017,19.07.2017 and 23.08.2017 (Copernicus Sentinel data. Retrieved from Sentinel hub [10.04.2021], processed by ESA.); Landcover raster based on Sentinel2 from 2016 (Source: mundialis GmbH & Co. KG)    

Output         : Spatial predicition of community composition (NDMS1, NDMS2) and species richness

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project was conducted in cooperation with Dr So Yeon Bae (University of Würzburg). 
Tree species diversity and the community composition of trees is predicted. The study is based on field data about vascular plant species identity and their percentual cover of each plot in the area of Steigerwald and the forest belonging to the University of Würzburg. Using the species distribution data, a non-metric multidimensional scaling (NMDS) with Bray-Curtis distance metrics were conducted using the vegan package. "NMDS maps the position of sites in species space [...] onto a predefined small number of axes in an iterative search for an optimal solution." (Leutner et al. 2012)
Sentinel data of three time steps is downloaded and preprocessed (L1C to L2A, mosaicing, stacking, cloud masking). Based on extracted information of the field data and the S2 multi-temporal composite random forest models are trained to predict NMDS1, NMDS2 and the number of tree species (caret package). 
The field data can not be provided here, please contact Prof. Müller or Dr Bae if questions concerning the data arise.   

