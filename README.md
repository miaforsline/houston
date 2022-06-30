# # EDS 223: Spatial Analysis for Environmental Data Science - Spatial Analysis 
### Authors: Mia Forsline and Alexandra Yousefivand 
### Due date: 2021-10-24

### Course instructor: Dr. James Frew
### [Course website](https://jamesfrew.github.io/EDS_223_spatial_analysis/)

## Course description
Spatial analysis, broadly defined, is the study of the relationships between phenomena as a function of their positions and extents in two or more dimensions. When at least two of those dimensions correspond to the Earth’s surface, we are analyzing geographic information, the fundamental substrate of environmental science.

EDS 223 / ESM 267 takes a programming approach to geographic information: instead of using a geographic information system (GIS) application (e.g., ArcGIS; QGIS), we will be manipulating and analyzing geographic information by writing programs in R and Python. This approach gives you a deeper understanding of the underlying operations and data structures that support geographic information, and is also much more flexible in terms of the problems you can address—you’re not limited to the capabilities built into a particular GIS application.

## Motivation and project goal
The PROJECT GOAL is to quantify the severity of **power outages** caused by a Texas storm in February 2021. Night lights image data from **NASA's Worldview** were examined, in conjunction with **Open Street Map** data of roads and buildings, to display a blackout mask of Houston. Brightness was compared before and after the storm to calculate the number of Houston homes that were affected by the power outages.

## Intended purpose and important concepts
As this project is intended for **educational purposes**, the student creators practiced loading vector and raster data and executed simple geoprocessing operations, including spatial joins.

## Future research
FUTURE RESEARCH aims to investigate whether there is a pattern between a particular socioeconomic factor and susceptibility to the power outages caused by the recent storms. Spatial census data layered on the blackout mask may reveal new insights into which populations are more likely affected by future storm outcomes.

## Installation
The following packages were utilized during this analysis:
- `sf`
- `stringr`
- `stars`
- `rgdal`
- `dplyr`
- `tmap`
- `lintr`
- `rosm`

The original assignment instructions and raw data can be found [here](https://jamesfrew.github.io/EDS_223_spatial_analysis/assignments/2/HW2.html). 
