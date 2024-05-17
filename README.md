# leaflet_challenge
# Earthquake Visualization 

This code is designed to visualize earthquake data obtained from the USGS API. Below is a brief overview of the code functionality:

## Features
- The code fetched earthquake data from the USGS API endpoint: [USGS Earthquake Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson).
- It defined functions to determine marker size based on earthquake magnitude and marker color based on earthquake depth.
- The retrieved earthquake data is logged to the console and then passed to the `createFeatures` function.
- The `createFeatures` function created GeoJSON layers representing earthquake data with markers on a Leaflet map.
- Each earthquake marker on the map is clickable, providing details such as location, date, magnitude, and depth in a popup.
- The map is styled with grayscale tiles from Mapbox and overlaid with earthquake data.

## Usage
1. Cloned the repository.
2. Opened the `index.html` file in a web browser.
3. The map rendered with earthquake data displayed as colored markers.
4. Detailed information about the earthquake can be viewed by clicking on any marker.

## Dependencies
- [Leaflet.js](https://leafletjs.com/): A JavaScript library for interactive maps.
- [D3.js](https://d3js.org/): A JavaScript library for data visualization.
- [Mapbox](https://www.mapbox.com/): A mapping platform for custom designed m
