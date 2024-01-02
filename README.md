# Weather and Vacation Analysis

## Overview
This project involves two main parts: WeatherPy and VacationPy. The goal is to analyze weather data across over 500 cities at varying distances from the equator using the OpenWeatherMap API and to plan future vacations based on ideal weather conditions using the geoViews Python library and the Geoapify API.

## Part 1: WeatherPy

### Objectives

- **Data Retrieval**: Use the OpenWeatherMap API to retrieve weather data for a list of cities.
- **Data Visualization**: Create scatter plots to showcase relationships between weather variables and latitude.
- **Statistical Analysis**: Compute linear regression for each weather variable against latitude for both Northern and Southern Hemispheres.

### Scatter Plots

1. Latitude vs. Temperature
2. Latitude vs. Humidity
3. Latitude vs. Cloudiness
4. Latitude vs. Wind Speed

### Linear Regression Analysis

- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

### Insights

- Analysis of the linear regression models and their implications.
- Discussion of any noticeable relationships and findings.

## Part 2: VacationPy

### Objectives

- **Map Visualization**: Create a map using geoViews and Geoapify API that displays humidity levels for each city.
- **Ideal Weather Conditions**: Filter the dataset to find cities that match ideal weather conditions.
- **Vacation Planning**: Use the filtered dataset to identify potential vacation destinations.

### Key Features

- Interactive map with points representing each city.
- Points sized according to the humidity level in each city.
- Filtered dataset based on criteria such as temperature range, wind speed, and cloudiness.

### Ideal Weather Criteria

- Max temperature between 21 and 27 degrees Celsius.
- Wind speed less than 4.5 m/s.
- Zero cloudiness.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- OpenWeatherMap API
- geoViews
- Geoapify API

## Data Sources

- Weather data retrieved from OpenWeatherMap API.
- City data generated using `citipy` library.
