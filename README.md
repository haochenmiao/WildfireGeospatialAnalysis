# Wildfire Geospatial Analysis Project

## Overview
This project focuses on the exploration and analysis of wildfire occurrences using Python geospatial libraries. The analysis is divided into two main parts, with each part addressing different facets of wildfire data handling, analysis, and visualization.

## Part 1: Wildfire Data Preparation and Conversion
### Objectives
* Introduction to geospatial data types relevant to wildfire analysis.
* Reading and writing geospatial wildfire data.
* Converting wildfire data files to various formats for analysis.
* Downloading and integrating external wildfire data sources.
### Tools and Libraries Used
* GeoPandas
* Fiona
* Rasterio
* GDAL
### Key Activities
1. Setting up the geospatial analysis environment with necessary libraries.
2. Managing vector data related to wildfires from shapefiles and GeoJSON.
3. Exporting analyzed data into different geospatial formats.
4. Visualizing wildfire locations and attributes.
### Jupyter Notebook
Filename: WildfireDataPreparation_Conversion.ipynb

## Part 2: Advanced Wildfire Analysis and Visualization

### Objectives
* Conducting advanced analysis on wildfire occurrences.
* Applying spatial operations to identify trends and patterns.
* Utilizing map projections for accurate geographic representations.
* Generating maps to visualize wildfire intensity and distribution.
### Tools and Libraries Used
* GeoPandas
* Fiona
* Shapely
* Matplotlib for mapping
### Key Activities
1. Detailed examination of vector data for wildfire trend analysis.
2. Merging wildfire occurrences with geographical boundaries for state-wise analysis.
3. Adjusting data projections to standardize analysis across datasets.
4. Creating choropleth and density maps to illustrate wildfire counts and intensity.
### Datasets
Detailed wildfire occurrence data for two distinct periods: 1985-1999 and 2000-2014.
Geospatial boundaries of states for overlay analysis.
### Analysis Steps
1. Ensuring all datasets are in the same coordinate reference system (CRS).
2. Associating wildfire data points with specific states through spatial joins.
3. Aggregating wildfire occurrences by state and time period.
4. Visualizing analysis results through various map visualizations.
### Jupyter Notebooks
Filename for 1985-1999 & 2000-2014 Analysis: WildfireAnalysis_1985_1999_2000_2014.ipynb

## Conclusion
The Wildfire Geospatial Analysis Project demonstrates the effective use of Python's geospatial libraries to process, analyze, and visualize wildfire data. Through spatial joins, data reprojecting, and mapping, we have gained insights into wildfire patterns, distributions, and trends across different states and time periods, contributing to a deeper understanding of wildfire dynamics.