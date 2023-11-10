## Table of Content:

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


## 💫 Day 1 of 30-Day Map Challenge: Points

### 🗺️ Topic: Global Flood Affected People

![Imgur](/data/figs/1_points.png)

📊 Since I have been working on flood modeling for over a year, I wanted to start the map challenge with the flood topic. This map shows where people were reported to be affected by major flood events between 1985-2010. The most affected regions include the US (Dallas, Pennsylvania), South America (Brazil, Bolivia), Africa (Burkina Faso, Gao, Botswana), Asia (Pakistan, India, Bangladesh), and Australia. Moreover, people in coastal cities were observed to be more frequently affected than the rest.

✨Please feel free to give suggestions & share!

📍 Data Source: https://data.humdata.org/dataset/global-active-archive-of-large-flood-events-dfo

🔗Download the high-resolution version: [Link](/data/figs/1_points.png)

🌐 Interactive Version (ArcGIS web layer): https://www.arcgis.com/home/item.html?id=557e973d9f0f453b89db6a1fd45f3307

🌐Github Page of project: https://github.com/waleedgeo/30daymap-2023

🎨Tools used: ArcGIS Pro and Adobe Illustrator.

👉 Next theme: Lines!

---

## 💫 Day 2 of 30-Day Map Challenge: Lines

### 🗺️ Topic: Global Shipping Routes ⛴️

![d2](/data/figs/2_lines_v2.png)

![d2](/data/figs/2_lines_v1.png)

The map shows the major, moderate, and minor shipping routes globally. I got inspiration from Prof. [Qiusheng Wu](https://www.linkedin.com/in/giswqs/) paper in [JOSS](https://doi.org/10.21105/joss.03414) about the Python package [Leafmap](https://leafmap.org/) for these visualizations.
While making the map, I got obsessed with these two colors so including both of them here.

📍 Data Source: https://zenodo.org/records/6361813

🔗 High resolution map version: [Link-V1 Orange](/data/figs/2_lines_v1.png) - [Link-V2 Blue](/data/figs/2_lines_v2.png)

🔗 Leafmap paper in JOSS: https://doi.org/10.21105/joss.03414

🎨Tools used: ArcGIS Pro and Adobe Illustrator.
👉 Next theme: Polygons

 #30DayMapChallenge #DataVisualization #Cartography #Mapping #globalshipping #visualization #lines

---

## 💫 Day 3 of 30-Day Map Challenge: Polygons

### 🗺️ Topic: Urbanization Trends in Lagos, Nigeria (1985-2018)

![d3](/data/figs/d3_polygons.png)

Mapping urbanization patterns always fascinates me. So, for the polygon theme, I used QGIS & #geemap, created a fishnet (~1 Km), and sampled the urban pixels in each zone.
The map reveals that Lagos city has experienced rapid urbanization, with the urban area growing exponentially over the past few decades, especially after 2000's era. 

🔗 [High Resolution Version](/data/figs/d3_polygons.png)

📍 Data Source: [Tsinghua FROM-GLC Year of Change to Impervious Surface](https://developers.google.com/earth-engine/datasets/catalog/Tsinghua_FROM-GLC_GAIA_v10)

🎨Tools used: QGIS, Google Earth Engine (Geemap) and Adobe Illustrator.

 #30DayMapChallenge #DataVisualization #Cartography #Mapping #visualization #spatialanalysis #lagos #nigeria #urbanization

 ---

## 💫 Day 4 of 30-Day Map Challenge: Bad Map

## 🗺️ Topic: A bad map of prefecture-level divisions of China

![d4](/data/d4_badmap/d4_badmap.png)

It may be the easiest theme of the challenge, but always make sure to avoid such common mistakes in cartographic designs: 

1) Extra text is not always a good case! AVOID clusters of text, and use simple attribute labels where possible.

2) Unwanted colors: not all maps need colors, and sometimes unintentional use of colors can convey the wrong message. For instance, here, sequential choropleth colors are used based on ADM2 property, WHICH DOES NOT MAKE SENSE!
 
🔗 High Resolution Version: [LINK](https://github.com/waleedgeo/30daymap-2023/blob/main/data/figs/d3_polygons.png)

🔗 All Project files for Day-4: [LINK](/data/d4_badmap/)

Note: for this project, I have uploaded all files (shapefile, QGIS project files etc. You can check the [GitHub repo above](/data/d4_badmap/))

📍 Data Source: Humdata (data also provided on GitHub)

🎨 Tools used: QGIS, Adobe Illustrator and Photoshop

 #30DayMapChallenge #DataVisualization #Cartography #Mapping #30DayMapChallenge #BadMap #China #QGIS #Carto #Cartography #GIS #Geospatial #DataViz

 ---

## 💫 Day 5 of 30-Day Map Challenge: Analog Map

### 🗺️ Topic: Analog Map of Floods in Pakistan (2010)

_Click the image to see the timelapse:_

[![d5Foo](/data/d5_analogmap/day5_analogmap.JPG)](https://www.youtube.com/embed/Ahshgcd9FR8)


This is by far the most difficult day for me. Being a digital cartographer, I have only thought of making a map with a computer. For this day, I looked into previous year's challenges and loved how they used day-to-day things to create a map. I quickly looked around and saw some shining red beans in my kitchen, and the rest you can see 😂

📽️ Timelapse Video: [LINK](https://www.youtube.com/embed/Ahshgcd9FR8)

✨ Inspiration was taken from: [TWITTER LINK](https://twitter.com/issa_madjid/status/1593319907894099969)

🔗 High-Resolution Version (you probably won't need it, but just in case 😂): [LINK](/data/d5_analogmap/day5_analogmap.JPG)

🔗 All Project files for Day-5:  [LINK](/data/d5_analogmap/)

🎨 Tools used: Shining Red Beans, Tapioca Pearl (Sabudana), and some glue.

 #30DayMapChallenge #DataVisualization #Cartography #Mapping

---

## 💫 Day 6 of 30-Day Map Challenge: Asia 

### 🗺️ Topic: Asia's River Network

![d6](/data/d6_asia/d6_asia.png)

Asia is well known for its river network, which is well-developed in the north, east, and south of the continent. Moreover, some of the world's largest river systems are in Asia, namely the Ganges and Brahmaputra, Yangtze, Yenisei, Lena, Ob, Amur, and Mekong.

🔗 High Resolution Version: [LINK](/data/d6_asia/d6_asia.png)

📍 Data Source: https://gee-community-catalog.org/projects/grn_wrz/

🎨 Tools used: ArcGIS Pro, and Adobe Illustrator

#30DayMapChallenge #DataVisualization #Cartography #Mapping #asia #river #rivernetwork

---

## 💫 Day 7 of 30-Day Map Challenge: Navigation

### 🗺️ Topic: Home to University!

![d7](/data/d7_navigation/d7_navigation.png)

Bright colors on dark canvas always fascinate me. So here's my take on visualizing a road network and a destination route. The map shows my daily travel route from my home in Shum Shui Po, to my campus, Hong Kong Baptist University. The road network in neon blue is shown for just Kowloon, in which the red lines show the route. The road network with the route was prepared using the OSMnx python package and was later edited in Adobe Illustrator.
 
🔗 High Resolution Version: [LINK](/data/d7_navigation/d7_navigation.png)

🔗 All Project files:  [LINK](/data/d7_navigation/)

📍 Data Source: OpenStreetMap (OSM) and [OSMnx python package](https://osmnx.readthedocs.io/en/stable/) 

🎨 Tools used: OSMnx Python Package, and Adobe Illustrator.

 #30DayMapChallenge #DataVisualization #Cartography #Mapping #navigation #osm #openstreetmap

 ---

## 💫 Day 8 of 30-Day Map Challenge: Africa

### 🗺️ Topic: Diorama of Mount Kilimanjaro

![d8](/data/d8_africa/d8_africa.png)

Mount Kilimanjaro, located in Tanzania, is Africa's highest peak, standing tall at 5,895 meters. The reason I chose this place is because of Its unique blend of breathtaking beauty and iconic stature. Special thanks to John Nelson, who provided an amazing tutorial for designing 3D Diorama in ArcGIS Pro.

🔗 High Resolution Version: [LINK](/data/d8_africa/d8_africa.png)

📍 Data Source: [Copernicus DEM GLO-30](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_DEM_GLO30)

🎨 Tools used: ArcGIS Pro and Adobe Illustrator.

✨ John Nelson's Tutorial on Diorama: [LINK](https://www.youtube.com/watch?v=kVsj6Z7UuLY&t=590s)

#30DayMapChallenge #DataVisualization #Cartography #Mapping #kilimanjaro #diorama #3d #arcgispro

---

## 💫 Day 9 of 30-Day Map Challenge: Hexagons

## 🗺️ Topic: Global Aridity Index

![d9](/data/d9_hexagons/d9_hexagons.png)

For today's theme, I created hexagons in ArcGIS Pro (using the Generate Tessellation tool), resampled them in Google Earth Engine with Global Aridity Index (GAI) data, and visualized them in QGIS + Illustrator. Each hexagon has a circumradius of approx. 15 Km.

GAI is an important indicator because it provides a comprehensive visual representation of areas worldwide that experience varying degrees of aridity, helping researchers and policymakers understand and address water scarcity issues. Moreover, the aridity index is a crucial metric for assessing the availability of water resources and predicting potential drought-prone regions, enabling proactive measures for water management and conservation.

🔗 High-Resolution Version: [LINK](/data/d9_hexagons/d9_hexagons.png)

📍 Data Source: [LINK](https://gee-community-catalog.org/projects/ai0/?h=aridit)

🔗 Generate Tessellation tool: [LINK](https://pro.arcgis.com/en/pro-app/latest/tool-reference/data-management/generatetesellation.htm)

🎨 Tools used: Google Earth Engine, QGIS, and Adobe Illustrator.

 #30DayMapChallenge #DataVisualization #Cartography #Mapping #hexagon #aridity #globalaridityindex #drought

---

## 💫 Day 10 of 30-Day Map Challenge: North America 

### 🗺️ Topic: Drought in North America (2023)

![d10](/data/d10_north_america/d10_north_america_optimized.gif)

I have always admired animated maps/gifs for conveying time-series information. So, for the North American theme, I used the North American Drought Monitor (NADM) dataset in Google Earth Engine.
The animated map shows that in 2023, North America experienced significant drought variations, with regions like California and the Great Plains facing severe water scarcity, impacting agriculture and increasing the risk of wildfires.

For designing the map I first assessed the NADM dataset from Awesome GEE Community Catalog, and then exported individual maps with Orthographic projection using  geemap.cartoee module. Later on, I finalized the maps in Illustrator and Photoshop.

Shout-out to Prof. [Qiusheng Wu](https://wetlands.io/) for including cartoee in geemap, and [Samapriya Roy, Ph.D.](https://www.linkedin.com/in/samapriya) for maintaining the Awesome GEE Community Catalog!

🔗 High Resolution Version: [LINK](/data/d10_north_america/d10_north_america.gif)

📍 Data Source: [LINK](https://gee-community-catalog.org/projects/nadm/?h=drought)

🔗 Geemap (Cartoee): [LINK](https://geemap.org/cartoee/)

🔗 Awsome GEE Community Catalog: [LINK](https://gee-community-catalog.org/)

🎨 Tools used: Google Earth Engine, Geemap, cartoee, cartopy, python, Adobe Illustrator and Photoshop

 #30DayMapChallenge #DataVisualization #Cartography #Mapping #GoogleEarthEngine, #Geemap, #cartoee, #cartopy

 ---
