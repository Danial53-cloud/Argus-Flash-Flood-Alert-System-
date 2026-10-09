ARGUS — Flash Flood Risk Monitoring System

1. Project Summary

ARGUS is a web-based disaster risk management application designed to identify potential flash flood risks in Bagh District, Azad Jammu and Kashmir, Pakistan.

Mountainous areas are vulnerable to flash floods because steep slopes and intense rainfall can cause water to flow rapidly through seasonal stream channels, locally known as nalas. These ephemeral streams are often not monitored like permanent rivers, leaving nearby communities and travelers vulnerable to sudden flooding.

ARGUS addresses this problem by displaying known flood-prone channels on an interactive map and comparing forecasted rainfall with predefined risk thresholds. When forecasted rainfall exceeds a configured threshold near a mapped channel, the system flags that channel as a potential hazard.

The application aims to provide localized flood risk information to disaster management authorities to support early warnings and informed decision-making.

Project focus: Forecast-based flash flood risk identification for known ephemeral channels in Bagh District.

2. Problem Statement

Flash floods can occur shortly after heavy rainfall, particularly in mountainous regions. Although weather forecasts are available, they are not always connected to specific channels that may become dangerous during rainfall.

Since ephemeral streams are rarely monitored and may be absent from conventional stream-monitoring systems, residents and travelers may not receive warnings relevant to their immediate surroundings.

ARGUS aims to bridge this gap by combining rainfall forecasts with mapped flood-prone channels to identify potential hazards before or during periods of heavy rainfall.

3. Project Objectives

Develop an interactive map of Bagh District displaying known flood-prone channels.

Store and display flood-channel locations using GeoJSON data.

Integrate forecasted rainfall data using the Open-Meteo weather API.

Compare forecasted rainfall against predefined risk thresholds.

Flag potentially hazardous channels on the map.

Provide localized hazard information to support disaster management decisions.

4. Key Features

Interactive hazard map: Visualizes the selected region using Leaflet.js and OpenStreetMap.

Flood-prone channel mapping: Displays previously identified ephemeral stream channels as a GeoJSON hazard layer.

Weather forecast integration: Retrieves forecasted rainfall data for the Bagh region using Open-Meteo.

Threshold-based alerts: Identifies channels where forecasted rainfall exceeds configured danger thresholds.

Alert visualization: Highlights potentially hazardous channels directly on the map.

Backend processing: Uses Python and Flask to retrieve rainfall forecasts and evaluate risk conditions.

Data storage: Uses MySQL to store channel information, forecast records, and alert status.

Documentation: Records the data sources and methodology used to identify flood-prone channels.

## Technology Stack

| Technology / Tool | Purpose |
|---|---|
| HTML | Structures the web interface |
| CSS | Styles the application and provides layout |
| JavaScript | Handles user interactions and map functionality |
| Leaflet.js | Displays the interactive map and flood-prone channels |
| OpenStreetMap | Provides the base map |
| GeoJSON | Stores flood-prone channel coordinates and geographic features |
| QGIS / geojson.io | Traces flood-prone channels and exports GeoJSON data |
| Open-Meteo API | Provides rainfall forecast data for Bagh District |
| Python | Handles backend processing and risk assessment |
| Flask | Provides backend services and API endpoints |
| MySQL | Stores flood-channel data, weather forecasts, and alert status |
| Figma | Designs interface mockups and layouts |
| Git | Tracks code changes and versions |
| GitHub | Hosts the project repository and supports team collaboration |
| Visual Studio Code | Provides the development environment |

## Contributors

| No. | Name | Registration Number | GitHub Username |
|---|---|---|---|
| 1 | Rabia Irshad | NUM-BSCS-2025-46 | [@Rabia-Irshad7](https://github.com/Rabia-Irshad7) |
| 2 | Shumaila Nawaz | NUM-BSCS-2025-53 | [@Shumaila36274](https://github.com/Shumaila36274) |
| 3 | Syed Danial Hassan | NUM-BSCS-2025-56 | [@Danial53-cloud](https://github.com/Danial53-cloud) |
| 4 | Syed Saeed Raza Shah | NUM-BSCS-2025-57 | [@SaeedRaza114](https://github.com/SaeedRaza114) |
