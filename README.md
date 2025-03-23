The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. 
Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.
The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. 
They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. 
In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.
Earthquake Visualization Map

This interactive web map displays recent earthquake data using Leaflet.js, D3.js, and OpenStreetMap tiles.
The project uses live data from the USGS GeoJSON Feed and includes optional tectonic plate boundaries.

Features
Interactive Map with zoom, pan, and multiple base layers
Circle Markers sized and colored by earthquake magnitude and depth
Live Earthquake Data pulled from USGS every time the page loads
Legend showing depth color scale
Layer Controls to toggle between base maps and data overlays
Tectonic Plates Layer 

Data Sources
Earthquake Data:
USGS Earthquake GeoJSON Feed
Map Tiles:
Default: OpenStreetMap
Optional: Humanitarian OpenStreetMap Team (HOT)

Technologies Used
Leaflet.js — interactive maps
D3.js — fetching GeoJSON data
HTML, CSS, JavaScript
