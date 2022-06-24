# Mapping_Earthquakes

## Project Overview
Maps allow us to explore, understand, and make decisions about our world. In this repository we will use javascript (GeoJSON) to create interactive maps to visualize earthquake data. GeoJSON data can be found in many apps that have a map feature such as ride-sharing, navigation, and food and package delivery services. Even location services on smart phones use GeoSJON format.

## Project Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

### Tasks
To complete this project, we use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

### Results

Each earthquake is visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake. The map has three views:

1. Street View
2. Satellite View
3. Dark View

![streetview_of_earthquake.png](https://github.com/klkanchi/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/streetview_of_earthquake.png)

![streetview_of_earthquake_tectonicplates.png](https://github.com/klkanchi/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/streetview_of_earthquake_tectonicplates.png)

![Darkview.png](https://github.com/klkanchi/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Darkview.png)

## Summary
To create the maps we used the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data.

Calling the API's alllowed us to traverse and retrieve GeoJSON earthquake data and tectonic plate data in order to populate a map. We then used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data. The viewer can toggle between different layers to view either all earthquakes, only major earthquakes (over 4.5 magnitude), and the earth's tectonic plates.

By viewing this visualization, it's clear that the majority of the major earthquakes in the last week have all occurred near or on the tectonic plates. Smaller earthquakes can occur farther away, but the major earthquakes all fall on or right next to the fault lines.
