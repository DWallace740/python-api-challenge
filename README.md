# WeatherPy and VacationPy: Weather Data Analysis and Vacation Planning

## Overview
This project involves analyzing weather data and using it to plan vacations. The workflow is divided into two main parts:

## WeatherPy (Part 1): 
Collects and analyzes weather data for cities around the world to visualize weather patterns.

## VacationPy (Part 2): 
Narrows down cities based on ideal weather conditions, finds nearby hotels using the Geoapify API, and creates interactive maps to assist in vacation planning.

## Part 1: WeatherPy

### Objective

The goal of WeatherPy is to retrieve weather data for a list of randomly generated cities and analyze relationships between weather attributes (temperature, humidity, cloudiness, wind speed) and geographic location (latitude).

### Features

1. Generate random geographic coordinates and find the nearest cities.

2. Retrieve weather data for each city using an API (such as OpenWeatherMap).

3. Perform linear regression analyses on weather attributes:
- Temperature vs. Latitude
- Humidity vs. Latitude
- Cloudiness vs. Latitude
- Wind Speed vs. Latitude

4. Create scatter plots to visualize relationships between weather attributes and latitude.

### Key Visualizations
- Global weather patterns.
- Linear regression plots for weather attributes.

## Part 2: VacationPy

### Objective

VacationPy uses the weather data from WeatherPy to plan vacations by:

1. Narrowing down cities based on ideal weather conditions.

2. Finding nearby hotels for selected cities using the Geoapify API.

3. Displaying the cities and hotels on an interactive map.

## Features

1. Filter Cities:
- Select cities with specific weather conditions (e.g., temperature range, low wind speeds, clear skies).

2. Find Hotels:
- Use the Geoapify API to locate hotels near the filtered cities.

3. Interactive Map:
- Display cities with ideal weather and their nearest hotels on a map.

- Include hover information for each city (city name, country, hotel name).

## Key Visualizations
- Global humidity map with city points.

- A map of cities with ideal weather conditions and their nearest hotels.

## Technologies and Tools

- Python: For data processing and visualization.

- Pandas: Data manipulation and filtering.

- Matplotlib: For generating scatter plots.

- hvPlot and geoViews: For interactive maps and geographic data visualization.

- Geoapify API: To locate hotels near selected cities.

- Jupyter Notebook: To run and document the project.

## Setup Instructions
### Prerequisites
1. Python installed on your system.

2. Required Python libraries:
- pip install pandas requests matplotlib hvplot geoviews

## Obtain API keys:

- Weather API Key: For collecting weather data (e.g., OpenWeatherMap).

- Geoapify API Key: For finding nearby hotels.

## Steps
Clone or download this repository.
Add your API keys in the respective notebooks:
Weather API key in WeatherPy.ipynb.
Geoapify API key in VacationPy.ipynb.
How to Use

### WeatherPy (Part 1)

1. Run WeatherPy.ipynb:

- Generate a list of cities using random geographic coordinates.

- Retrieve weather data for each city using the weather API.

- Analyze relationships between latitude and weather attributes.

- Save the results in city_data.csv.

## VacationPy (Part 2)

1. Run VacationPy.ipynb:

- Load the city_data.csv file created in Part 1.

- Filter cities based on ideal weather conditions (customizable criteria).

- Use the Geoapify API to find nearby hotels for each filtered city.

- Visualize the results on interactive maps.


## Example Outputs

## WeatherPy

### Scatter plots:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

## VacationPy
- Humidity Map: Displays global humidity levels for all cities.

- Hotel Map: Highlights cities with ideal weather and their nearest hotels, including hover information.

## Resources and Support
For this project, I used multiple resources to ensure the successful completion of the assignment:

ChatGPT (AI Assistant): For guidance on code logic, debugging, structuring the scripts, and formatting this README file.
All external resources used are listed here for transparency.

## Project Purpose
This project demonstrates how to integrate Python data analysis, visualization, and APIs to perform real-world tasks such as weather analysis and vacation planning.

## Author
This project was developed as part of a Python data analysis and visualization assignment.

## License
This project is licensed for educational purposes.