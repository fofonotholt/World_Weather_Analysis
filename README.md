# World_Weather_Analysis
Bootcamp module 6 PyWeather

## Overview
The purpose of this analysis is to create a great vacation. With help of Google APIs and Weather APIs, we created a program, in which users can input their preffered weather conditions, and get all the places in the world that meets their criteria.

## Results
Fits of all, we created 2,000 random coordinates, so we can have data from all over the world. After that we the open weathermap API to get the nearest city with their respective weather information. Next we created a DataFrame with the cities data. 
<img width="786" alt="Captura de Pantalla 2021-07-24 a la(s) 12 30 29" src="https://user-images.githubusercontent.com/85461477/126876555-a9591b94-5d70-48b0-bbb6-31dafe94e7c7.png">

With the DataFrame, we asked the user for their minimum and maximum prefered tempreature. In this case, the user chose min 75º and max 90º. With this data we filtered the antire DataFrame for cities that met that criteria. After that we used Google's API to gather add a hotel to the new DataFrame and we created a map with the given Data.
<img width="972" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/85461477/126876696-58ae8475-2773-442a-a69b-4c00fc281dde.png">

Lasty we created a great itinerary for the user. Selecting 4 cities with the users prefered weather, selcted hotels and driving routes. Again we used Google's API tto get the dedired results.
<img width="974" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/85461477/126876747-9de25400-a72f-43d9-a8bb-acecb5a006e9.png">
