#  Visualizing Data with Leaflet


![1-Logo](Images/1-Logo.png)

Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

# Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

visualize an earthquake data set.

1. **data set**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize Data**

    a map that plots all of the earthquakes from data set based on their longitude and latitude.

   * data markers reflect the magnitude of the earthquake by their size and and depth of the earth quake by color. Earthquakes with higher magnitudes appear larger and earthquakes with greater depth appear darker in color.

   * Includes popups that provide additional information about the earthquake when marker is clicked.

   * Legend provides context for map data.

### Level 2: More Data (Optional)

![](Images/5-Advanced.png)

second data set on map  illustrates the relationship between tectonic plates and seismic activity. <https://github.com/fraxen/tectonicplates>.


* Plot a second data set on map.

* Add number of base maps to choose from as well as separate out two different data sets into overlays that can be turned on and off independently.

* Add layer controls to map.