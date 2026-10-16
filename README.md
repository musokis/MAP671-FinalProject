# Food and Culture in Massachusetts

This README includes the details of my final project. My final project visualizes my study area, Boston, Massachusetts. I am interested in visualizing access to African food stores within Massachusetts. The map is a digital visualization to show store distribution within the Boston area.

## Why Food Stores in Massachusetts

This is part of a larger resaerch project that explores identity through food. The plan I had in mind while starting this project was to visualize the population distribution of African immigrants in Massachusetts and the corresponding proximity to African food stores with the future goal of understanding how these stores are frequented, as a way to maintain ties to their homelands. Population data differentiated by country of emigration was difficult to find. So, I have this map that shows the stores’ distribution. I noticed that the stores are concentrated around the Boston urban area. Perhaps this is indicative of the patrons of these stores as also living in close proximity to the stores. 

## How the Map was Made

This map was created with the Open Street Map base. The data was obtained by googling a list of African food stores in the Boston area 

<img src="Images_README/google data.png" alt=" data from google maps" width="600" height="400">

I used the stores' addresses and the OSM place search plugin to plot the store locations on the OSM map base. After plotting the store locations, I used the color blue to make sure that the point data was clearly visible against the background map. 

<img src="Images_README/plotting point data .png" alt=" plotting point data from googled store addresses" width="600" height="400">

I added the store names by editing the attribute table to include a field column with names corresponding to the plotted points. 

<img src="Images_README/creating new field.png" alt=" created new field in attributes table to include store names" width="600" height="400">

For the inset map, I initially wanted it to visualize the population distribution and density of African Immigrants in the state of Massachusetts. However, I was unable to obtain sufficient data for this exercise. So, I used the OSM place search plugin, again, to isolate and outline the state in the Atlantic northeast region. The OSM base map had the EPSG 3857- WGS 84/ Pseudo Mercator projection. For the final map, I used the EPSG: 26986 "NAD83 / Massachusetts Mainland" projection that the state of Massachusetts uses.

## Link to Webpagge

Please view the map <a href="https://musokis.github.io/MAP671-FinalProject/">here</a>

