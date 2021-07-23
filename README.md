# Flood-Risk-Zone-Map-of-Bhagalpur-Region

![MAPATHON0288_Flood zone_Map2](https://user-images.githubusercontent.com/77197538/126818399-5655de95-84ab-4c32-96e3-b23cac96d52b.jpg)

Methodology :


1. Isro Data used in my map :

Bhuvan Isro :
From Bhuvan website, I downloaded the raster data for Bhagalpur region for the DEM analysis and also the vector layer of River / water bodies and roads .

Vedas Isro :
From the Vedas website, I analysed the temperature, water bodies etc. for my map region that is helpful for making the map.


Disaster Service Bhuvan Isro :
I analysed the data about historical flood situations for Bhagalpur region from 2014 to 2020 and tried to specify the region with high to low risk from the disaster service section of Bhuvan website. It is very helpful for me to analyse my map region about flood situations.



2. Specific steps in GIS :
I used total 8 layers of vector and raster data for making my map.

i. Firstly, I got my map region easily from the resource link https://static.fossee.in/mapathon/Mapathon2020_Data/ .

ii. Using Google map, I found out the block headquarters coordinates and using coordinates, I made a point shapefile vector layer to specify the region.

iii. I downloaded the Inland Water + Road shapefile and used it in the map and also, i calculated the length of rivers that flows through the Bhagalpur city using google map.
iv. Now, I used the raster data for dem analysis for my map region and also made a hillshade raster layer that is used in the map with 50% transparency .

v. I analysed the flood data 2014 to 2020 and used a raster layer for flood to specify the region from high to low risk. I mainly wanted to highlight the region where the risk is more than 20%, so I tried to make the lowest flood risk region with white color ( with 100% transparency ) for an understandable map. Besides the lowest flood risk region, other flood risk regions are only 10% transparent.

