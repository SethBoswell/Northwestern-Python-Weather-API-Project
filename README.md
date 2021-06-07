# World_Weather_Analysis
Python API Project Folder
## Purpose of Repository
This repository first uses the OpenWeatherMap API to find the nearest city from a list of randomly generated latitute and longitude values. Next, the code creates a dataframe that includes the city name, latitude, longitude, max temperature, humitidy, cloudiness, windspeed, and weather description for each city. I stored this data in the Weather_Database folder as "WeatherPy_Database.csv".

In the Vacation Search folder, I then take these cities and find the nearest hotel for cities within temperature ranges specified by the user. The code plots information for these cities on on a map using the Google Maps API with markers denoting each city. Users can interact with the map by clicking on the markets, which will detail the city's nearest hotel, name, country, and current weather description. An image of this map is included in the "WeatherPy_vacation_map.png" image in the Vacation Search Folder.

Finally, in the Vacation Itinerary folder, I use the Google Maps API to create a map that connects 4 cities in Spain to show the user what route to take for this trip. This route is pictured in "WeatherPy_travel_map.png." Finally, I created the marker map again, but only for these 4 cities, which is included in "WeatherPy_travel_map_markers.png"
