# World_Weather_Analysis
Analyze weather patterns using JSON data to show best cities to take a vacation based on certain weather criteria.

Click here to view the analysis files: [WeatherPy.ipynb](https://github.com/ChicletKeyboard/World_Weather_Analysis/blob/eebee5ef9c638903fd43545f5e84ee00e8645774/WeatherPy.ipynb) | [VacationPy.ipynb](https://github.com/ChicletKeyboard/World_Weather_Analysis/blob/eebee5ef9c638903fd43545f5e84ee00e8645774/VacationPy.ipynb)

## Purpose
This project analysis was to create a vacation map that allows users to apply weather criteria to identify potential travel destinations. By utilizing Google API's we also provided the user with recommendations of ideal hotels within there preferred travel destinations.

## Overview
In order to create the vacation map, we generated a list of 2,000 random latitudes and longitudes. With the coordinates, we retrieved and compiled a list of the nearest cities using the citipy module. Then, we used the OpenWeatherMap API to request the current weather data from each unique city on the list. The resulting map provides users with descriptions of the destinations found on our list, including: hotel name, city, country, and current weather and description.
