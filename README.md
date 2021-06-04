# World_Weather_Analysis

Weather Analysis using API

![Figure1](Heatmap.png)

## Purpose:

**Weather Database**

![Figure2](Weather_Database/City_weather.png)
*Table1: List of random locations with their latitude,longitude and weather conditions.*

The main purpose of the Weather Database is to create a weather App and help travelers choose travel locations based on weather conditions and temperature. For this project 2000 random location coordinates (latitude and longitude) were generated. Based on the coordinates generated and using Open weather API key, the City, Country, Max Temp, Current Weather conditions, Humidity, Cloudiness and Wind speed data was obtained and converted into a dataframe.

**Vacation Search**

![Figure3](Vacation_Search/WeatherPy_vacation_map.png)

*Google map 1: Travel destinations based on temperature input along hotel names, city and temp.*

The purpose of this project is to create a Customer Travel Destination App, where based on the customer input of desired maximum and minimum temp a list of city names are created. Using the Google Map Platform, searchnearby API, the nearest hotel name is added to the dataframe. The new dataframe now has the City name, Country, Max Temp, current description, coordinates( lat a nd lng) and Hotel name. After creating a clean dataframe with hotel names a google map marker layer is created with locations and hotel info.

**Vacation Itinerary**

![Figure3](Vacation_Itinerary/WeatherPy_travel_map.png)

*Google map 2: Travel itinerary based on 4 cities.*

In this project, a four city vacation itinerary is created using Google maps directions API. Followed by the directions map, a marker map is also created using Google map marker, including the Hotel name,City, country, Current description and Max Temp.

![Figure4](Vacation_Itinerary/WeatherPy_travel_map_marker.png)

*Google map 2: Vacation Itinerary including hotel name, city name and temperature of the 4 cities.*
