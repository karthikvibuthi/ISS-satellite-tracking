![ISS](./iss_tracking-Copy1.html)

# ISS Satellite Tracking and Mapping with Folium

## Project Overview

In this project, I've created a dynamic and interactive Jupyter notebook application that tracks the real-time location of the International Space Station (ISS) and displays its path on a world map. The project utilizes live data from NASA's Open Notify API to provide up-to-the-minute coordinates of the ISS.

## Key Features

- **Real-time Tracking**: The project streams live data from NASA's Open Notify API, providing the current coordinates of the ISS. I update the ISS's position at regular intervals, simulating real-time tracking.

- **Interactive Mapping**: I've used the Folium library, a Python wrapper for Leaflet.js, to create an interactive and visually appealing world map. The map serves as the canvas for displaying the ISS's location and path.

- **Displaying the Path**: As the ISS moves, I plot its path by connecting the coordinates of its previous positions using a PolyLine on the map. This provides a visual representation of the ISS's trajectory.

- **Time-Limited Tracking**: To keep the demonstration concise and meaningful, I've limited the tracking to a specific time frame, e.g., 30 seconds, while updating the position every 5 seconds. This helps showcase the satellite's high-speed movement effectively.

## How it Works

1. The project begins by initializing an interactive map centered around coordinates (0, 0) with an initial zoom level of 3.

2. I fetch the initial location of the ISS from the Open Notify API and create a PolyLine with an empty list to represent the satellite's path.

3. The code then enters a loop where it periodically retrieves new ISS coordinates, updates the map's markers, and appends the new coordinates to the path.

4. The map is displayed within the Jupyter notebook cell, providing a dynamic and visually appealing representation of the ISS's movement and its trajectory.

## Use Cases

- **Education**: This project can be used for educational purposes to help students visualize the movement of satellites in real-time.

- **Space Enthusiasts**: Space enthusiasts can use this project to keep track of the ISS's location and appreciate its incredible speed and coverage.

- **Demonstrations**: It can be used in presentations or demonstrations to showcase real-time data visualization and the capabilities of Python libraries like Folium.

## Requirements

- Python 3.x
- Requests library for making HTTP requests
- Folium library for creating interactive maps
- Jupyter Notebook or Jupyter Lab environment

## Conclusion

This project provides an engaging and educational way to track the ISS and display its path using Folium and Jupyter Notebook. It offers a dynamic visualization of the ISS's high-speed movement and is a valuable tool for education, space enthusiasts, and presentations. By combining real-time data and interactive mapping, this project highlights the capabilities of Python and relevant libraries for data visualization and tracking.
