## A Spatial Analysis of the Licensed Childcare Centers in New Jersey, USA

# Md Nurul Hoque, EJB School of planning and public policy, Rutgers University.

This project aims to analyze the Licensed Childcare Centers in New Jersey, USA through Spatial Analysis tools in Python Jupyter Notebook. I have collected the dataset from the New Jersey Office of Information Technology (NJOIT) Open Data Center (source link: https://data.nj.gov/Public-Safety/Licensed-Child-Care-Centers/cru5-4rmm). The dataset was downloaded as csv file. There was no geographic coordinates information in the dataset. I had to convert the address and ZIP codes into geographic coordinates through geocoding. I also had to explore Spatial Joins, and Geoprocessing tools like Buffer, Clip, Union Overlay Operation, Unary Union etc. to make the data appropriate to generate the desired maps. Finally, I encountered a bug in the heatmap of the interactive map. I solved that issue by adjusting the heatmap layer style in the HTML codes. 

## STATIC MAPS

# NJ Licensed Childcare Centers by County  

<iframe src='static map1.png' width = '1000' height = '700' ></iframe>

# NJ Licensed Childcare Centers per 100k Residents  

<iframe src='static map2.png' width = '1000' height = '700' ></iframe>

# NJ Licensed Childcare Centers: Five Mile Transit Accessibility by County  

<iframe src='static map3.png' width = '1000' height = '700' ></iframe>

## INTERACTIVE MAP  

# NJ Licensed Childcare Centers Web Map

<iframe src='nj_childcare_centers.html' width = '1000' height = '700' ></iframe>

You can also explore [this map as its own web page here](nj_childcare_centers.html)

## FINDINGS

Monmouth County has the highest number of licensed childcare centers while Morris, Warren, Ocean, Cape May, and Salem County have the least centers. Considering the childcare centers per 100k residents, Monmouth and Mercer have the highest number of centers while Bergen, Morris, and Ocean County have the least. Finally, all the counties except Sussex, Warren, Hunterdon, and Burlington have their childcare centers within five-mile transit accessibility.     



