# wireless-charging-reco-system

This web application visualizes solar energy potential across a region to help government agencies, corporates, and planners identify the most suitable locations for solar power installations. By simulating solar intensity readings, the application provides a heatmap of solar potential and automatically highlights the top locations for solar plant deployment.

The project is designed as a fully software-based solution that can be easily adapted to real-world solar sensor data in the future. It demonstrates the concept of data-driven solar site selection in a visually intuitive manner, making it ideal for hackathons, presentations, and feasibility studies.

Key Features

Solar Intensity Heatmap
Displays solar potential on a map using Leaflet.js and heatmap visualization.
Each point represents simulated solar intensity readings, normalized for display.

Top 3 Solar Locations

Automatically calculates the highest solar intensity locations.
Provides latitude, longitude, and average intensity for each top site.

Fully Software-Based

No physical hardware required; uses simulated data.
Can be extended to accept real-time data from solar sensors in the future.

Interactive Interface
Users can refresh the map or view top locations with a single click.
Clean UI suitable for presentations and hackathon demos.

Tech Stack

Backend: Python, Flask, SQLite (database for simulated solar readings)

Frontend: HTML, CSS, JavaScript, Leaflet.js (map & heatmap)

Visualization: Leaflet.heat plugin for heatmap generation

How It Works

Simulated Solar Data: The backend generates randomized solar intensity readings for demonstration purposes.

API Routes: Flask serves API endpoints for retrieving heatmap data and top locations.

Frontend Map: Leaflet.js fetches API data and displays it as an interactive heatmap.

Top Locations: Backend calculates top 3 locations based on average intensity and frontend displays markers and a panel.

Use Case / Impact

Enables data-driven decision-making for solar energy planning.
Helps planners identify high potential solar zones quickly.
Can be adapted for wireless EV charging planning by linking solar sites with charging stations.
Ideal for hackathons, academic projects, or prototype demonstrations.
