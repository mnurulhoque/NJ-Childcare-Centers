# A Spatial Analysis of the Licensed Childcare Centers in New Jersey, USA

# Project Overview 
This project was conducted as the final project required by the 'Seminar in Public Informatcs (Command Line Geographic Information System' course at E.J. Bloustein School of Planning and Public Policy, Rutgers University. This project aims to analyze the Licensed Childcare Centers in New Jersey, USA through Spatial Analysis tools. 

# Data Sets
[NJ licensed childcare centers] as csv file (https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Childcare_Centers.csv) Source (https://data.nj.gov/Public-Safety/Licensed-Child-Care-Centers/cru5-4rmm)

[NJ counties] as geojson file (https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/NJ_Counties_NGJIN_2021.geojson)
[Bus stops of NJ transit] as geojson file (https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Bus_Stops_of_NJ_Transit_by_Line.geojson)

[Light rail stations of NJ transit] as geojson file (https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Light_Rail_Stations_of_NJ_Transit.geojson)

[Passenger rail stations] as geojson file (https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Passenger_Rail_Stations.geojson)

[Path stationlocations] as geojson file (https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Path%20Station%20Locations.geojson)

[Rail stations of NJ transit] as geojson file (https://github.com/mnurulhoque/NJ-Childcare-Centers/blob/main/Rail_Stations_of_NJ_Transit.geojson)

# Resources & Tools Used
Core programming language: Python

Development environment: Jupyter Notebook

Libraries & packages: pandas, geopandas, pygeos, arcgis, shapely, folium, mapclassify, matplotlib

# Data Wrangling 
I have collected the dataset from the New Jersey Office of Information Technology (NJOIT) Open Data Center (source link: https://data.nj.gov/Public-Safety/Licensed-Child-Care-Centers/cru5-4rmm). The dataset was downloaded as csv file. There was no geographic coordinates information in the dataset. I had to convert the address and ZIP codes into geographic coordinates through geocoding. I also had to explore Spatial Joins, and Geoprocessing tools like Buffer, Clip, Union Overlay Operation, Unary Union etc. to make the data appropriate to generate the desired maps. Finally, I encountered a bug in the heatmap of the interactive map. I solved that issue by adjusting the heatmap layer style in the HTML codes.

# Data Analysis

## STATIC MAPS

## NJ Licensed Childcare Centers by County  

<iframe src='static map1.png' width = '1000' height = '1000' ></iframe>

## NJ Licensed Childcare Centers per 100k Residents  

<iframe src='static map2.png' width = '1000' height = '1300' ></iframe>

## NJ Licensed Childcare Centers: Five Mile Transit Accessibility by County  

<iframe src='static map3.png' width = '1000' height = '1300' ></iframe>

## INTERACTIVE MAP  

# NJ Licensed Childcare Centers Web Map

<iframe src='nj_childcare_centers.html' width = '1000' height = '1000' ></iframe>

You can also explore [this map as its own web page here](nj_childcare_centers.html)
