# modeling-scooter-rides-in-paris
How different scooter companies hit the streets of Paris

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

![](./documentation/daily_fleet_utilization_ratio.png)

Hourly fleet utilization - April 8, 2019

![](./documentation/hourly_fleet_utilization_ratio.png)

Arrondissements in Paris

![](./documentation/arrondissements.png)

Louvre

![](./documentation/louvre.png)

Point in polygon

![](./documentation/point_in_polygon.png)

Where to deploy scooters in

![](./documentation/where_to_deploy_scooters_in.png)

## Status
This project is in progress.
