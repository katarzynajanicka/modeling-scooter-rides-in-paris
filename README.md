# modeling-scooter-rides-in-paris
How different scooter companies hit the streets of Paris

<img src="https://img.shields.io/badge/python-3.8.5 -brightgreen"> <img src='https://img.shields.io/badge/pandas-1.1.1-blue'> <img src='https://img.shields.io/badge/numpy-1.19.1-blue'> <img src='https://img.shields.io/badge/geopandas-0.6.1-blue'> <img src='https://img.shields.io/badge/descartes-1.1.0-blue'> <img src="https://img.shields.io/badge/matplotlib-3.3.1 -blue"> <img src="https://img.shields.io/badge/seaborn-0.10.1 -blue"> <img src="https://img.shields.io/badge/geospatial-data%20analysis-ff69b4"> <img src="https://img.shields.io/badge/ride-data%20analysis-ff69b4"> <img src="https://img.shields.io/badge/exploratory-data%20analysis-ff69b4"> <img src="https://img.shields.io/badge/data-visualization-ff69b4">

 ## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Status](#status)

## General info
This project is an analysis of the scooter ecosystem in Paris in March and early April 2019. 
	
## Technologies
Project is created with Python - version: 3.8.5.

Python libraries:
* pandas - version 1.1.1
* numpy - version 1.19.1
* geopandas - version 0.6.1
* descartes - version 1.1.0
* matplotlib - version 3.3.1
* seaborn - version 0.10.1
  
## Setup
The input data consists of:
- a flat file (data-rides.csv, size of 744 MB) was not uploaded to GitHub
- four geospatial files used for data enrichment (arrondissements.dbf, arrondissements.prj, arrondissements.shp, arrondissements.shx)

The output data:
- modeling-scooter-rides-in-paris.ipynb (Jupyter Notebook)

## Business questions

![](./documentation/questions.png)

## Analysis

![](./documentation/table_of_contents.png)

## Main objectives

![](./documentation/main_objectives.png)

## Screenshots

Scooter fleet

![](./documentation/scooters_per_vendor_bar.png)
![](./documentation/scooters_per_vendor_line.png)
![](./documentation/scooter_fleet_agg.png)

Daily rides per company

![](./documentation/daily_rides_per_vendor.png)
![](./documentation/daily_rides_per_vendor2.png)

Haversine formula for distance approximation

![](./documentation/haversine_formula.png)

Daily fleet utilization - April 8, 2019

![](./documentation/daily_fleet_ut_def.png)

![](./documentation/daily_fleet_utilization_ratio.png)

Hourly fleet utilization - April 8, 2019

![](./documentation/hourly_fleet_ut_def.png)

![](./documentation/hourly_fleet_utilization_ratio.png)

Arrondissements in Paris

![](./documentation/arrondissements.png)

Louvre

![](./documentation/louvre.png)

Point in polygon

![](./documentation/point_in_polygon.png)
![](./documentation/shapefiles.png)
![](./documentation/geospatial_logic.png)

Where to deploy scooters in

![](./documentation/where_to_deploy_scooters_in.png)

## Status
This project is finished.
