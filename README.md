# Python-Project 
Prepared by: Payton Duran

# Description
This Python sctipt will take the given pixel area of a raster and convert it to acerage. 

# How it works:
The idea of this project is to take a certain areas Land use data and give exactly how much acreage there is in the 
pixel area. This way instead of getting pixel area you will get acerage which would be easier for spatial reference. 
the conversion !Count! *30 *30 *0.000247105 was used in order to get the acreage. The 30 * 30 is the ratio of pixel 
and meter and I multiply that by the meter to acreage conversion to get the acreage.  

# Why I wanted to do it: 
The reason I wanted to do this code is because it would help me with another one of my projects and with future 
projects because while there are set tools to give you pixel density of a raster file, I wanted to be able to see 
not the pixel density but the acreage of the pixels to get a better idea of the spatial reference. 

# How I did it: 
First I built a model that would be the base of my code. The model included code that built an attribute table for 
my raster file, a summary statistic, and add field which added the acreage field, and a calculate field which converted 
the pixels to acres. After the model was built I was able to export it to a python script and begin adding my code to it. 
I added the local varibale, the tool, and the output tables that would be provided at the end. The finished code allows 
for a raster to be added, and the code will add an acreage field and give the acres via the conversion used and as long as there is a count field in the raster it will convert.   

# Modules 
arcpy
tkinter

