**Note:** 
- _Click on each map, to see its high resolution version!_
- _All project files are available in the [data folder](/data/)._
- More data will be added after the end of this challenge.
- In case you use my map or find it insightful, please share your thoughts with me, as I would love to hear your feedback.
- For queries contact me at: 
    - [My Email](mailto:waleedgeo@outlook.com)
    - [LinkedIn](https://www.linkedin.com/in/waleedgeo)
- [Check the license of my maps here](#license-1)


## Table of Contents:

- [Day 1 Points: Global Flood Affected People](#-day-1-of-30-day-map-challenge-points)
- [Day 2 Lines: Global Shipping Routes](#-day-2-of-30-day-map-challenge-lines)
- [Day 3 Polygons: Urbanization Trends in Lagos, Nigeria](#-day-3-of-30-day-map-challenge-polygons)
- [Day 4 Bad Map: A bad map of prefecture-level divisions of China](#-day-4-of-30-day-map-challenge-bad-map)
- [Day 5 Analog Map: Floods in Pakistan](#-day-5-of-30-day-map-challenge-analog-map)
- [Day 6 Asia: Asia's River Network](#-day-6-of-30-day-map-challenge-asia)
- [Day 7 Navigation: Home to University](#-day-7-of-30-day-map-challenge-navigation)
- [Day 8 Africa: Diorama of Mount Kilimanjaro](#-day8-of-30-day-map-challenge-africa)
- [Day 9 Hexagons: Global Aridity Index](#-day-9-of-30-day-map-challenge-hexagons)
- [Day 10 North America: Drought in North America](#-day-10-of-30-day-map-challenge-north-america)
- [Day 11 Retro: A 3D Digitized Old Map of Balochistan](#-day-11-of-30-day-map-challenge-retro)
- [Day 12 South America: MANAUS City](#-day-12-of-30-day-map-challenge-south-america)
- [Day 13 Choropleth: Nighttime Light in Palestine 2023](#-day-13-of-30-day-map-challenge-choropleth)
- [Day 14 Europe: Population Exposure to Heat Hazard in Europe](#-day-14-of-30-day-map-challenge-europe)
- [Day 15 OpenStreetMap: Lahore Road Network](#-day-15-of-30-day-map-challenge-openstreetmap)
- [Day 16 Oceania: Frequency of Forest Fires in Australia](#-day-16-of-30-day-map-challenge-oceania)
- [Day 17 Flow: Pakistan Migration Flow](#-day-17-of-30-day-map-challenge-flow)
- [Day 18 Atmosphere: Nitrogen Dioxide Concentration](#-day-18-of-30-day-map-challenge-atmosphere)
- [Day 19 5 minute map: Karachi's Road Network](#-day-19-of-30-day-map-challenge-5-minute-map)
- [Day 20 Outdoors: Animation of Tai Mo Shan Hike](#-day-20-of-30-day-map-challenge-outdoors)


## 💫 Day 1 of 30-Day Map Challenge: Points

### 🗺️ Topic: Global Flood Affected People

[![Imgur](https://imgur.com/az9kzUM.png)](/data/figs/1_points.png)

📊 Since I have been working on flood modeling for over a year, I wanted to start the map challenge with the flood topic. This map shows where people were reported to be affected by major flood events between 1985-2010. The most affected regions include the US (Dallas, Pennsylvania), South America (Brazil, Bolivia), Africa (Burkina Faso, Gao, Botswana), Asia (Pakistan, India, Bangladesh), and Australia. Moreover, people in coastal cities were observed to be more frequently affected than the rest.

✨Please feel free to give suggestions & share!

📍 Data Source: 
- [Humdata](https://data.humdata.org/dataset/global-active-archive-of-large-flood-events-dfo)

🔗Download the high-resolution version: 
- [Link](/data/figs/1_points.png)

🌐 Interactive Version (ArcGIS web layer):
- [LINK](https://www.arcgis.com/home/item.html?id=557e973d9f0f453b89db6a1fd45f3307)

🎨Tools used: ArcGIS Pro and Adobe Illustrator.

---

## 💫 Day 2 of 30-Day Map Challenge: Lines

### 🗺️ Topic: Global Shipping Routes ⛴️

[![d2](https://imgur.com/EmVH2hi.png)](/data/figs/2_lines_v2.png)

The map shows the major, moderate, and minor shipping routes globally. I got inspiration from Prof. [Qiusheng Wu](https://www.linkedin.com/in/giswqs/) paper in [JOSS](https://doi.org/10.21105/joss.03414) about the Python package [Leafmap](https://leafmap.org/) for these visualizations.
While making the map, I got obsessed with these two colors so including both of them here.

NOTE:
- There is another version of this map with orange lines, which I am sharing as well. Click here to see the orange version: [LINK](/data/figs/2_lines_v1.png)

📍 Data Source: 
- [Global Shipping Lanes](https://zenodo.org/records/6361813)

🔗 High resolution map version: 
- [Link-V1 Orange](/data/figs/2_lines_v1.png) 
- [Link-V2 Blue](/data/figs/2_lines_v2.png)

🔗 Leafmap paper in JOSS:
- [LINK](https://doi.org/10.21105/joss.03414)

🎨Tools used: ArcGIS Pro and Adobe Illustrator.

---

## 💫 Day 3 of 30-Day Map Challenge: Polygons

### 🗺️ Topic: Urbanization Trends in Lagos, Nigeria (1985-2018)

[![d3](https://imgur.com/QMTnlIs.png)](/data/figs/d3_polygons.png)

Mapping urbanization patterns always fascinates me. So, for the polygon theme, I used QGIS & #geemap, created a fishnet (~1 Km), and sampled the urban pixels in each zone.
The map reveals that Lagos city has experienced rapid urbanization, with the urban area growing exponentially over the past few decades, especially after 2000's era. 

🔗 High Resolution Version
- [LINK](/data/figs/d3_polygons.png)

📍 Data Source: 
- [Tsinghua FROM-GLC Year of Change to Impervious Surface](https://developers.google.com/earth-engine/datasets/catalog/Tsinghua_FROM-GLC_GAIA_v10)

🎨Tools used: QGIS, Google Earth Engine (Geemap) and Adobe Illustrator.

 ---

## 💫 Day 4 of 30-Day Map Challenge: Bad Map

## 🗺️ Topic: A bad map of prefecture-level divisions of China

[![d4](https://imgur.com/GJ7mYnD.png)](/data/d4_badmap/d4_badmap.png)

It may be the easiest theme of the challenge, but always make sure to avoid such common mistakes in cartographic designs: 

1) Extra text is not always a good case! AVOID clusters of text, and use simple attribute labels where possible.

2) Unwanted colors: not all maps need colors, and sometimes unintentional use of colors can convey the wrong message. For instance, here, sequential choropleth colors are used based on ADM2 property, WHICH DOES NOT MAKE SENSE!
 
🔗 High Resolution Version: 
- [LINK](https://github.com/waleedgeo/30daymap-2023/blob/main/data/figs/d3_polygons.png)

🔗 All Project files for Day-4: 
- [LINK](/data/d4_badmap/)


📍 Data Source: 
- Humdata

🎨 Tools used: QGIS, Adobe Illustrator and Photoshop

 ---

## 💫 Day 5 of 30-Day Map Challenge: Analog Map

### 🗺️ Topic: Analog Map of Floods in Pakistan (2010)

_Click the image to see the timelapse:_

[![d5Foo](https://imgur.com/66u1ml5.jpg)](https://www.youtube.com/embed/Ahshgcd9FR8)


This is by far the most difficult day for me. Being a digital cartographer, I have only thought of making a map with a computer. For this day, I looked into previous year's challenges and loved how they used day-to-day things to create a map. I quickly looked around and saw some shining red beans in my kitchen, and the rest you can see 😂

📽️ Timelapse Video: 
- [LINK](https://www.youtube.com/embed/Ahshgcd9FR8)

✨ Inspiration was taken from: 
- [TWITTER LINK](https://twitter.com/issa_madjid/status/1593319907894099969)

🔗 High-Resolution Version (you probably won't need it, but just in case 😂): 
- [LINK](/data/d5_analogmap/day5_analogmap.JPG)

🔗 All Project files for Day-5:  
- [LINK](/data/d5_analogmap/)

🎨 Tools used: Shining Red Beans, Tapioca Pearl (Sabudana), and some glue.

---

## 💫 Day 6 of 30-Day Map Challenge: Asia 

### 🗺️ Topic: Asia's River Network

[![d6](https://imgur.com/wDcWknL.png)](/data/d6_asia/d6_asia.png)

Asia is well known for its river network, which is well-developed in the north, east, and south of the continent. Moreover, some of the world's largest river systems are in Asia, namely the Ganges and Brahmaputra, Yangtze, Yenisei, Lena, Ob, Amur, and Mekong.

🔗 High Resolution Version: 
- [LINK](/data/d6_asia/d6_asia.png)

📍 Data Source: 
- [GEE Awsome Community Catalog](https://gee-community-catalog.org/projects/grn_wrz/)

🎨 Tools used: ArcGIS Pro, and Adobe Illustrator

---

## 💫 Day 7 of 30-Day Map Challenge: Navigation

### 🗺️ Topic: Home to University!

[![d7](https://imgur.com/2cGvxPT.png)](/data/d7_navigation/d7_navigation.png)

Bright colors on dark canvas always fascinate me. So here's my take on visualizing a road network and a destination route. The map shows my daily travel route from my home in Shum Shui Po, to my campus, Hong Kong Baptist University. The road network in neon blue is shown for just Kowloon, in which the red lines show the route. The road network with the route was prepared using the OSMnx python package and was later edited in Adobe Illustrator.
 
🔗 High Resolution Version: 
- [LINK](/data/d7_navigation/d7_navigation.png)

🔗 All Project files:  
- [LINK](/data/d7_navigation/)

📍 Data Source: 
- [OpenStreetMap (OSM) and OSMnx python package](https://osmnx.readthedocs.io/en/stable/) 

🎨 Tools used: OSMnx Python Package, and Adobe Illustrator.

 ---

## 💫 Day 8 of 30-Day Map Challenge: Africa

### 🗺️ Topic: Diorama of Mount Kilimanjaro

[![d8](https://imgur.com/pTMp4XD.png)](/data/d8_africa/d8_africa.png)

Mount Kilimanjaro, located in Tanzania, is Africa's highest peak, standing tall at 5,895 meters. The reason I chose this place is because of Its unique blend of breathtaking beauty and iconic stature. Special thanks to John Nelson, who provided an amazing tutorial for designing 3D Diorama in ArcGIS Pro.

🔗 High Resolution Version: 
- [LINK](/data/d8_africa/d8_africa.png)

📍 Data Source: 
- [Copernicus DEM GLO-30](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_DEM_GLO30)

🎨 Tools used: ArcGIS Pro and Adobe Illustrator.

✨ John Nelson's Tutorial on Diorama: 
- [LINK](https://www.youtube.com/watch?v=kVsj6Z7UuLY&t=590s)

---

## 💫 Day 9 of 30-Day Map Challenge: Hexagons

## 🗺️ Topic: Global Aridity Index

[![d9](https://imgur.com/5cugyuA.png)](/data/d9_hexagons/d9_hexagons.png)

For today's theme, I created hexagons in ArcGIS Pro (using the Generate Tessellation tool), resampled them in Google Earth Engine with Global Aridity Index (GAI) data, and visualized them in QGIS + Illustrator. Each hexagon has a circumradius of approx. 15 Km.

GAI is an important indicator because it provides a comprehensive visual representation of areas worldwide that experience varying degrees of aridity, helping researchers and policymakers understand and address water scarcity issues. Moreover, the aridity index is a crucial metric for assessing the availability of water resources and predicting potential drought-prone regions, enabling proactive measures for water management and conservation.

🔗 High-Resolution Version: 
- [LINK](/data/d9_hexagons/d9_hexagons.png)

📍 Data Source:
- [LINK](https://gee-community-catalog.org/projects/ai0/?h=aridit)

🔗 Generate Tessellation tool: 
- [LINK](https://pro.arcgis.com/en/pro-app/latest/tool-reference/data-management/generatetesellation.htm)

🎨 Tools used: Google Earth Engine, QGIS, and Adobe Illustrator.

---

## 💫 Day 10 of 30-Day Map Challenge: North America 

### 🗺️ Topic: Drought in North America (2023)

**Click the GIF to load high resolution version**

[![d10](https://imgur.com/OzhmajT.gif)](/data/d10_north_america/d10_na_optimized.gif)

I have always admired animated maps/gifs for conveying time-series information. So, for the North American theme, I used the North American Drought Monitor (NADM) dataset in Google Earth Engine.
The animated map shows that in 2023, North America experienced significant drought variations, with regions like California and the Great Plains facing severe water scarcity, impacting agriculture and increasing the risk of wildfires.

For designing the animated map, I first assessed the NADM dataset from Awesome GEE Community Catalog, and then exported individual maps with Orthographic projection using  geemap.cartoee module. Later on, I finalized the maps in Illustrator and Photoshop.

Shout-out to Prof. [Qiusheng Wu](https://wetlands.io/) for including cartoee in geemap, and [Samapriya Roy, Ph.D.](https://www.linkedin.com/in/samapriya) for maintaining the Awesome GEE Community Catalog!

🔗 High Resolution Version: 
- [LINK](/data/d10_north_america/d10_na.gif)

📍 Data Source: 
- [LINK](https://gee-community-catalog.org/projects/nadm/?h=drought)

🔗 Geemap (Cartoee): 
- [LINK](https://geemap.org/cartoee/)

🔗 Awsome GEE Community Catalog: 
- [LINK](https://gee-community-catalog.org/)

🎨 Tools used: Google Earth Engine, Geemap, cartoee, cartopy, python, Adobe Illustrator and Photoshop

 ---

## 💫 Day 11 of 30-Day Map Challenge: Retro

## 🗺️ Topic: A 3D Digitized Old Map of Balochistan

[![d11](https://imgur.com/etHqAbQ.jpg)](/data/d11_retro/d11_retro.JPG)

As a retro theme, I choose an old map of Balochistan (Pakistan), from the Imperial Gazetteer of India (1907-1909). Since the map resolution was low, I find it quite difficult to georeference and render it in 3D but still I managed (thanks to John Nelson amazing tutorials on vintage theme maps).

🔗 High Resolution Version: 
- [LINK](/data/d11_retro/d11_retro.JPG)

📍 Data Source:
- [LINK](https://en.m.wikipedia.org/wiki/File:Map_of_Baluchistan_from_The_Imperial_Gazetteer_of_India_%281907-1909%29.jpg)

🎨 Tools used: ArcGIS Pro, and Adobe Illustrator.

---

## 💫 Day 12 of 30-Day Map Challenge: South America

### 🗺️ Topic: MANAUS City: Where Civilization Meets Wilderness

[![d12](https://imgur.com/mGTBqf4.jpg)](/data/d12_south_america/d12_sa.jpg)

A few weeks ago, I saw an aerial image of this place on social media and was instantly in love with the beauty of its landscape. So for today's theme, I chose this place called Manaus, located on the banks of the Negro River in northwestern Brazil.

For preparing this map poster, I used Maxar basemap image for 2021 and edited them directly in Adobe Photoshop and then Illustrator. I intended to print this as a wall poster and therefore processed all data in 8K resolution, which resulted in around 200 MB of image size.  Here, I am sharing the compressed version (~7 MB, and 300dpi). So, if you need that very high resolution, request it on GitHub, and I will happily provide it.

🔗 High-Resolution Version: 
- [LINK](/data/d12_south_america/d12_sa.jpg)

🔗 Google Maps Location: 
- [LINK](https://www.google.com/maps/place/Manaus,+State+of+Amazonas,+Brazil/@-3.044662,-59.9671039,12z/data=!3m1!4b1!4m6!3m5!1s0x926c1bc8b37647b7:0x2b485c9ff765a9cc!8m2!3d-3.1190275!4d-60.0217314!16zL20vMDJia2sz?entry=ttu)

📍 Data Source: 
- Maxar Basemap for 2021

🎨 Tools used: Google Earth Pro, Adobe Illustrator, and Photoshop

 ---

## 💫 Day 13 of 30-Day Map Challenge: Choropleth

### 🗺️ Topic: Nighttime Light Variation in Palestine in 2023

**Click the GIF to load high resolution version**

[![d13](https://imgur.com/r3LM1Hu.gif)](/data/d13_choropleth/d13_optimized.gif)


Nighttime light (NTL) data is vital for identifying areas affected by power outages, infrastructure destruction, and population displacement in war conflict situations. I used sequential choropleth colors to visually represent changes in light intensity and highlight active regions. Although I initially aimed to depict the NTL variation in current months, I could only access data up until September (NTL data is not available after September IDK why!). 

Nevertheless, I am sharing all available data, including rasters, individual maps, and original timelapse gifs, in the hope that it contributes to a better understanding of conflict dynamics, aids humanitarian efforts, and informs policy decisions for peace and stability in the region.

🔗 High Resolution Version: 
- [LINK](/data/d13_choropleth/d13_optimized.gif) 

🔗 All Project files: 
- [LINK](/data/d13_choropleth/) 

📍 Data Source: 
- [Nighttime Light](https://developers.google.com/earth-engine/datasets/catalog/NOAA_VIIRS_DNB_MONTHLY_V1_VCMSLCFG) 

🎨 Tools used: Google Earth Enigne, Geemap, ArcGIS Pro, Adobe Illustrator and Photoshop

## 💫 Day 14 of 30-Day Map Challenge: Europe

### 🗺️ Topic: Population Exposure to Heat Hazard in Europe

**Click the GIF to load high resolution version**

[![d14](https://imgur.com/aC4waPM.gif)](/data/d14_europe/d14_optimized.gif)

Heat stress has become a significant global concern, impacting populations worldwide. In this analysis, I focused on Europe, examining the population exposed to heat stress at the ADM 0 level. While Europe may experience lower levels of heat stress compared to other regions, there are still populations within European states facing high levels of heat stress, as depicted in the bivariate population exposure map.

For analysis, I used Global Extreme Heat Hazard (5 year interval) layer provided by World Bank, and Total Population data provided by Worldpop. For analysis, I used geemap for zonal statistics, ArcGIS Pro for maps, Illustrator for editing and Photoshop for final gif. All the individual maps and materials are available below.

🔗 High Resolution Version:
- [High Resolution Gift: ](/data/d14_europe/d14_optimized.gif)
- [High Resolution Population Map: ](/data/d14_europe/Pop.png)
- [High Resolution Heat Hazard Map: ](/data/d14_europe/Heat.png)
- [High Resolution Exposure Map: ](/data/d14_europe/bivariate.png)

🔗 All Project files:
- [LINK](/data/d14_europe/)

📍 Data Source: 
- [Heat Hazard Layer: ](https://gee-community-catalog.org/projects/heat-hazard/)
- [Worldpop:](https://developers.google.com/earth-engine/datasets/catalog/WorldPop_GP_100m_pop)

🎨 Tools used: Geemap, ArcGIS Pro, Adobe Illustrator and Photoshop

## 💫 Day 15 of 30-Day Map Challenge: OpenStreetMap 

### 🗺️ Topic: Lahore Road Network

[![d15](https://imgur.com/ummOlOa.png)](/data/d15_openstreetmap/d15_openstreetmap.png)

Am I the only one obsessed with neon color road networks on dark backgrounds 😂? I have been waiting for this day since the start of this challenge as I wanted to create this masterpiece map showing the dense road network in Lahore city. I am also planning to prepare this kind of map after the 30DayMapChallenge, so feel free to suggest some beautiful cities with prominent road networks.

For preparing the map, I used the OSMnx python package, QGIS, and Adobe Illustrator. 

🔗 High-Resolution Version:
- [LINK](/data/d15_openstreetmap/d15_openstreetmap.png)


📍 Data Source: [OSMnx](https://osmnx.readthedocs.io)

🎨 Tools used: OSMnx, QGIS, and Adobe IllustratorPhotoshop

## 💫 Day 16 of 30-Day Map Challenge: Oceania

### 🗺️ Topic: Frequency of Forest Fires in Australia (2001-2023)

[![d16](https://imgur.com/V1vAYSJ.png)](/data/d16_oceania/d16_oceania.png)

So, for day 16 theme, I choose Australia, as the country has experienced devastating forest fires that have significantly impacted its ecosystems and communities. Various factors, including extreme heat, prolonged droughts, and strong winds, have fueled these fires. The frequency and intensity of the fires have increased, resulting in widespread destruction of forests, biodiversity loss, and wildlife displacement. From the map, it can be seen that between 2001 and 2023, 3882 forest fires have been recorded.

For analysis, I used Google Earth Engine in Geemap, and exported results in ArcGIS Pro, where I designed the map. Later on, I finalized the map in Adobe Illustrator.

🔗 High Resolution Version:
- [LINK](/data/d16_oceania/d16_oceania.png)

📍 Data Source:
- [FIRMS: Fire Information for Resource Management System](https://developers.google.com/earth-engine/datasets/catalog/FIRMS)

🎨 Tools used: Google Earth Engine, Geemap, ArcGIS Pro, and Adobe Illustrator.

## 💫 Day 17 of 30-Day Map Challenge: Flow

### 🗺️ Topic: Pakistan Migration Flow (1990-2015)

[![d17](https://imgur.com/J9At5LK.png)](/data/d17_flow/d17_flow.png)

Last year, I was awarded a PhD fellowship at HKBU and had to leave Pakistan. Interestingly, during the same year, Pakistan witnessed the highest recorded number of people (280,000 individuals) leaving the country, resulting in the highest migration rate ever documented in its history. Today, I wanted to explore the theme of migration and depict the flow of people in and out of the country.

Although I couldn't find the most up-to-date comprehensive databases, I came across some valuable resources in nature papers, which I decided to utilize for my work. The map presented here illustrates the migration rates with Pakistan as the origin country and various other nations as destinations. Additionally, the barplot highlights the top 10 countries with the highest percentage of migration flow, with Saudi Arabia and the United Arab Emirates leading the list.

To create these visualizations, I utilized open-source datasets from Nature papers (figshare), cleaned the data using Python's pandas library, and geolocated the information using ArcGIS Pro.

🔗 High Resolution Version:
- [LINK](/data/d17_flow/d17_flow.png)

🔗 All Project files:
- [LINK](/data/d17_flow/)

📍 Data Source:
- [Bilateral international migration flow estimates for 200 countries](https://www.nature.com/articles/s41597-019-0089-3)
- [Bilateral international migration flow estimates updated and refined by sex](https://www.nature.com/articles/s41597-022-01271-z#Sec4)
- [Countries Codes and Lat Long](https://gist.github.com/cpl/3dc2d19137588d9ae202d67233715478)

🎨 Tools used: Python (Pandas), ArcGIS Pro, and Adobe Illustrator

## 💫 Day 18 of 30-Day Map Challenge: Atmosphere

### 🗺️ Topic: Nitrogen Dioxide Concentration variation in COVID (2019 & 2020)

[![d18](https://imgur.com/0fkDFGr.png)](/data/d18_atmosphere/d18_atmosphere.gif)

During the COVID-19 pandemic, significant changes in nitrogen dioxide (NO2) concentrations were observed globally. With lockdowns and travel restrictions, reduced industrial and transportation activities led to a noticeable decline in NO2 levels. So, for today's theme, I used Sentinel-5P NO2 data to visualize the trends in NO2 for the pre covid (2019) and during covid (2020) period. Overall, a decreasing trend is prominent from the visualization. This unprecedented reduction in NO2 levels provides a glimpse of the environmental impact of reduced human activity during the pandemic.

🔗 High Resolution Version: 
- [LINK](/data/d18_atmosphere/d18_atmosphere.gif)


📍 Data Source:
- [Sentinel-5P NRTI NO2: Near Real-Time Nitrogen Dioxide](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_NO2)

🎨 Tools used: Google Earth Engine, Geemap, cartopy (cartoee), Adobe Illustrator and Photoshop

## 💫 Day 19 of 30-Day Map Challenge: 5 minute map 

### 🗺️ Topic: Karachi's Road Network

[![d19](https://imgur.com/8Y63Jlm.png)](/data/d19_5minutemap/d19_5minutemap.png)

Python OSMnx python package is a great tool to make quick OSM visualizations. So for today's 5 minute map theme, I used the OSMnx package to visualize Karachi's road network.

🔗 High Resolution Version:
- [LINK](/data/d19_5minutemap/d19_5minutemap.png)

📍 Data Source:
- [OSMnx](https://osmnx.readthedocs.io)

🎨 Tools used: OSMnx, ArcGIS Pro and Adobe Illustrator


## 💫 Day 20 of 30-Day Map Challenge: Outdoors 

### 🗺️ Topic: Animation of Tai Mo Shan Hike

[![d20](https://imgur.com/Ow04wZR.gif)](https://youtu.be/DdjjHKh6qfs)

A few months ago, I did my first hike in Hong Kong at Tai Mo Shan, the highest peak in the region. This special adventure covered a distance of approximately 10 km and took me around 5 hours to complete.

To celebrate my love for the outdoors, I decided to create a simple animation showcasing the hiking trail of Tai Mo Shan. Using data collected from Google Earth Studio and Google Earth Pro, I edited the footage in Adobe Premiere Pro to bring the trail to life.

For those who are interested in experiencing the hike themselves, I have included the gpx file for the entire route in the [data folder](/data/d20_outdoors/).

🔗 High Resolution Version:
- [YouTube Full Animated Video](https://youtu.be/DdjjHKh6qfs)


📍 Data Source:
- [Google Earth Studio](https://www.google.com/earth/studio/)
- [Google Earth Pro](https://www.google.com/earth/versions/#earth-pro)
- [Journey Era](https://www.journeyera.com/tai-mo-shan-hike-hong-kong/)

🎨 Tools used: Google Earth Studio, Google Earth Pro, and Adobe Premiere Pro

## License

All maps are licensed under [CC BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/4.0/). 

- [See License details here if you want to copy,or use my maps.](https://creativecommons.org/licenses/by-nc-nd/4.0/)

- In case you use my map or find it insightful, please share the details with me, as I would love to hear your feedback.
- For queries contact me at: 
    - [My Email](mailto:waleedgeo@outlook.com)
    - [LinkedIn](https://www.linkedin.com/in/waleedgeo)

---

Tags:

 #30DayMapChallenge #DataVisualization #Cartography #Mapping #googleearthengine #geemap #python #arcgispro #qgis #adobeillustrator #adobephotoshop #cartoee #cartopy #geospatial #gis #remotesensing #earthengine #gee #viusalization #osmnx