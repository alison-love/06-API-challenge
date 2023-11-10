# 06-API-challenge

Weather and Vacation Analysis

Overview

This project analyzes weather data across cities worldwide to explore how weather varies with latitude. Using this analysis, the project identifies potential vacation destinations with ideal weather conditions. The analysis is divided into two parts: Weather Analysis (WeatherPy) and Vacation Spot Selection (VacationPy).


Technologies Used
Python
Jupyter Notebook
Libraries: Pandas, Matplotlib, hvPlot
APIs: OpenWeatherMap, Geoapify


Part 1: Weather Analysis (WeatherPy)

In this section, weather data for almost 600 cities was gathered using the OpenWeatherMap API. The primary goal was to analyze the relationship between latitude and various weather parameters, including temperature, humidity, cloudiness, and wind speed. Key steps include:

Data Collection: Randomly selected cities' weather data was fetched from OpenWeatherMap.
Data Visualization: Scatter plots were created to illustrate the relationship between each weather parameter and latitude.
Linear Regression: Separate linear regression analyses were conducted for cities in the Northern and Southern Hemispheres to examine trends.


Part 2: Vacation Spot Selection (VacationPy)

Using weather criteria (e.g., temperature range, humidity), cities with ideal weather conditions were identified. For each of these cities, nearby hotels were found using the Geoapify Places API. The main components of this section are:

Data Filtering: Cities with ideal weather conditions were selected from the dataset.
Hotel Search: For each selected city, the nearest hotel within a specified radius was found using Geoapify.
Map Visualization: The selected cities and hotels were visualized on a map using hvplot, with interactive elements displaying detailed information.
