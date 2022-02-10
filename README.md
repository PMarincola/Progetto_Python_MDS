# Progetto_Python_MDS
### PyWorldTemp - 01 2022

## Description
This Python project comes with many libraries installed like 
- pandas, numpy for dataset pre-processing.
- scipy, seaborn, matplotlib for statistics analysis and graphs.
- geopy, geopandas for geospatial analysis and data visualization.
- tqdm for barchart support.

## Requirements
This project require a specific dataset.
Look here to download [climate](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data) dataset.

Before run the cell, user should change .csv file repository path:
```bash
file = './Dataset_archive/GlobalLandTemperaturesByCity.csv'
```

## Dataset Analysis
1) Analysis filtering by City : select City hardcoding the string
```bash
stat_Df = CityStats(city_name = 'InsertCityNameHere!!!',dataframe = df)
```
  - 1.1: Look observation (count) , mean, min , max
  - 1.2: Use scypy library for linear regression.analysis. 
  - 1.3: Use seaborn for graph analysis on Linear Regression.
  - 1.4: Use matplotlib for simple histogram
  
  2) Analysis with Geopandas: All the cities are involved in this analysis.
   - 2.1: Create dict data type named location_map = {} to store cities lat & long coordinates and for each city store the termic excursion.
  - 2.2: Visualize data in world image.

## Errors/Warnings
Slicing a positional slice with .loc is not supported:
To be verify
Not clear how to avoid warning for .loc


# Author
Pietro Marincola - 
Master DSE
