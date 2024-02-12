# A Spatial Analysis of the Licensed Childcare Centers in New Jersey, USA

# Project Overview 
This project was conducted as the final project required by the 'Seminar in Public Informatcs (Command Line Geographic Information System' course at E.J. Bloustein School of Planning and Public Policy, Rutgers University. This project aims to analyze the Licensed Childcare Centers in New Jersey, USA through Spatial Analysis tools. 

# Data Sets
[NJ licensed childcare centers](https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Childcare_Centers.csv) as csv file 

[NJ counties](https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/NJ_Counties_NGJIN_2021.geojson) as geojson file 

[Bus stops of NJ transit](https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Bus_Stops_of_NJ_Transit_by_Line.geojson) as geojson file 

[Light rail stations of NJ transit](https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Light_Rail_Stations_of_NJ_Transit.geojson) as geojson file 

[Passenger rail stations](https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Passenger_Rail_Stations.geojson) as geojson file 

[Path stationlocations](https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Path%20Station%20Locations.geojson) as geojson file 

[Rail stations of NJ transit](https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Rail_Stations_of_NJ_Transit.geojson) as geojson file 

# Resources & Tools Used
Core programming language: Python

Development environment: Jupyter Notebook

Libraries & packages: pandas, geopandas, pygeos, arcgis, shapely, folium, mapclassify, matplotlib

# Data Wrangling 
I have collected the dataset from the New Jersey Office of Information Technology (NJOIT) Open Data Center (source link: https://data.nj.gov/Public-Safety/Licensed-Child-Care-Centers/cru5-4rmm). The dataset was downloaded as csv file. There was no geographic coordinates information in the dataset. I converted the address and ZIP codes into geographic coordinates through geocoding. I also used Spatial Joins, and Geoprocessing tools like Buffer, Clip, Union Overlay Operation, Unary Union etc. to make the data appropriate to generate the desired maps. Finally, I encountered a bug in the heatmap of the interactive map. I solved that issue by adjusting the heatmap layer style in the HTML codes.

# Data Analysis

## STATIC MAPS

## NJ Licensed Childcare Centers by County  
![static map1](https://github.com/mnurulhoque/NJ-Childcare-Centers/assets/152673435/340ebad6-df60-482f-8eeb-452bb042a8c5)

## NJ Licensed Childcare Centers per 100k Residents  
![static map2](https://github.com/mnurulhoque/NJ-Childcare-Centers/assets/152673435/6377a934-d0f5-4924-a1f4-ee463456fd94)

## NJ Licensed Childcare Centers: Five Mile Transit Accessibility by County  
![static map3](https://github.com/mnurulhoque/NJ-Childcare-Centers/assets/152673435/736c4625-79fb-4c1d-90c3-3945de4dd8ed)

## INTERACTIVE MAP  

# NJ Licensed Childcare Centers Web Map

You can explore [the interactive web map as its own web page here](https://mnurulhoque.github.io/NJ-Childcare-Centers/nj_childcare_centers.html)

# Code File
## [Data Wrangling](https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Final_Project-Part1_MNH.ipynb)

