# python-api-challenge
Module 6 Challenge

We were tasked with identifying over 500 random cities at different distances from the equator and analyzing the weather at those different cities with respect to maximum temperature, humidity, cloudiness, and wind speed.

## Weather Analysis
### Maximum Temperature vs Latitude
![Maximum Temperature vs Latitude](https://github.com/rollernathan/python-api-challenge/blob/main/WeatherPy/output_data/Fig1.png)
As indicated in the scatterplot above, the maximum temperature south of the equator (negative values for latitude) increase as we get closer to the equator (zero latitude) and the maximum temperature north of the equator (positive values for latitude) decreases as we get further from the equator. This is in line with what we would expect to be the case. When looking at the data, perhaps it is surprising there is not a greater correlation between maximum temperature and distance from the equator.


### Humidity vs Latitude
![Humidity vs Latitude](https://github.com/rollernathan/python-api-challenge/blob/main/WeatherPy/output_data/Fig2.png)
As shown in the scatterplot above, there is no correlation between humidity and latitude, or distance from the equator.


### Cloudiness vs Latitude
![Cloudiness vs Latitude](https://github.com/rollernathan/python-api-challenge/blob/main/WeatherPy/output_data/Fig3.png)
As shown in the scatterplot above, there is no correlation between cloudiness and latitude, or distance from the equator.


### Wind Speed vs Latitude
![Wind Speed vs Latitude](https://github.com/rollernathan/python-api-challenge/blob/main/WeatherPy/output_data/Fig4.png)
As shown in the scatterplot above, there is no correlation between wind speed and latitude, or distance from the equator.



## Vacation (YAY!)
When going on vacation, I prefer no clouds, low humidity (below 30%), and not much wind (below 5 m/s). In isolating only cities from the previously generated list that meet these criteria, there are 18 cities remaining which are identified on the map below.

![Vacation Hotels](https://github.com/rollernathan/python-api-challenge/blob/main/WeatherPy/output_data/Vacation_map.png)

Of these 18 cities, only 11 have hotels within 10 kilometers of the city's given latitude and longitude. These specific hotels in each city can be provided upon request.

## Sources
Data for the weather analysis retrieved from [OpenWeatherMap API](https://openweathermap.org/api) as of July 7, 2024.

Data for local hotels retrieved from [Geoapify API](https://apidocs.geoapify.com/docs/geocoding/forward-geocoding/#api) as of July 7, 2024.
