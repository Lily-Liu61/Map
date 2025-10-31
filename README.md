# Earthquake Map Web Application

## Project Overview
This is an interactive web application built with **Mapbox GL JS** to visualize earthquake data and China's boundary data. The webpage supports loading multiple GeoJSON datasets and displays earthquake information both on the map and in a floating side panel. The side panel automatically hides on smaller screens.

---

## Features

- Fullscreen interactive map with **zoom and pan** capabilities.
- Floating side panel on the top-right corner, containing:
  - Map title
  - Sort button
  - Earthquake data table (ID, Magnitude, Timestamp)
- Supports at least two GeoJSON datasets:
  1. **`earthquakes.geojson`**: Earthquake points
  2. **`China.json`**: Polygon of China's boundary
- Earthquake points are displayed as red circles with white borders.
- China's boundary is displayed as a semi-transparent blue polygon.
- Responsive design: the side panel hides automatically when the screen width is less than 1024px.
- Table can be sorted by earthquake magnitude.

---

