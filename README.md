# 17 Leaflet - Earthquake History

## Demo page

Check out the latest earthquake data (all events in the last 7 days): https://abgondin.github.io/leaflet-challenge/

## Background

This project visualizes real time earthquake data from the United States Geological Survey.

### Level 1: Basic Visualization

The USGS provides earthquake data updated every 5 minutes. Here, the URL of the JSON file from 'All Earthquakes from the Past 7 Days' from the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page is used for the visualization.

![4-JSON](Images/4-JSON.png)

A Leaflet map was used to plot all of the earthquakes from your data set based on their longitude and latitude.
   * The data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker.
   * Includes popups that provide additional information about the earthquake when a marker is clicked.
   * A legend that provides context for the map data.

![2-BasicMap](Images/2-BasicMap.png)

### Level 2: With tectonic plates data added

Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

A second Leaflet map was used to illustrate the relationship between tectonic plates and seismic activity.
   * Two datasets are plotted on the map.
   * A number of base maps are added.
   * The two different data sets can be separated into overlays that can be turned on and off independently.
   * Layer controls added to map.

![5-Advanced](Images/5-Advanced.png)

