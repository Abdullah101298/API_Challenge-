# Analyzing Weather Data using an API

<img src="https://www.mapsofworld.com/style_2019/images/world-best-continents-map.jpg" width="1000" height="400">

## Part 1 - WeatherPy 

Objective: We created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.

First, we built a series of scatter plots to showcase the following relationships:

    (1) Temperature (F) vs. Latitude
    (2) Humidity (%) vs. Latitude
    (3) Cloudiness (%) vs. Latitude
    (4) Wind Speed (mph) vs. Latitude

Next, we ran a linear regression to showcase the correlation between 

    (1) Northern Hemisphere - Temperature (F) vs. Latitude
    (2) Southern Hemisphere - Temperature (F) vs. Latitude
    (3) Northern Hemisphere - Humidity (%) vs. Latitude
    (4) Southern Hemisphere - Humidity (%) vs. Latitude
    (5) Northern Hemisphere - Cloudiness (%) vs. Latitude
    (6) Southern Hemisphere - Cloudiness (%) vs. Latitude
    (7) Northern Hemisphere - Wind Speed (mph) vs. Latitude
    (8) Southern Hemisphere - Wind Speed (mph) vs. Latitude


## Part 2 - VacationPy 

Objective: Let's plan a future vacations by seperating the cities by our ideal weather conditions. 

First, we create a heatmap. Next, we specified our ideal weather conditions and listed our ideal cities that fit this weather criteria. 

Next, we use Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

Lastly, we plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
