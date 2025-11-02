This project demonstrates how to build an interactive web map using Mapbox GL JS and asynchronous GeoJSON data loading. It is part of Lab 3 for GEOG 495 / Web GIS coursework.

earthquake.html

Implements asynchronous data loading with fetch().
Loads and displays two GeoJSON datasets:
japan.json — Prefectural polygons of Japan.
earthquakes.geojson — Earthquake points.
Provides a side panel table with earthquake ID, magnitude, and timestamp.
Includes a “Sort by Magnitude” button to reorder the table dynamically.


index.html

Uses Mapbox’s navigation-night-v1 style for a dark full-screen map.
Keeps the side panel hovering in the top-right corner over the map.
Fully responsive — the side panel hides automatically on smaller screens.
Displays the same datasets with different symbology for visual contrast.
