# Analyzing weather data using APIs

Consists of two activities - WeatherPy and VacationPy. Key activities performed include:

# [WeatherPy]
  - Visualize the weather of 500+ cities across the world of varying distance from the equator by utilizing the Citipy Python library and the OpenWeatherMap API
  - Create a series of scatter plots to showcase the following relationships:
    * Temperature (F) vs. Latitude
    * Humidity (%) vs. Latitude
    * Cloudiness (%) vs. Latitude
    * Wind Speed (mph) vs. Latitude
   - Run linear regression on each relationship, separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
    * Northern Hemisphere - Temperature (F) vs. Latitude
    * Southern Hemisphere - Temperature (F) vs. Latitude
    * Northern Hemisphere - Humidity (%) vs. Latitude
    * Southern Hemisphere - Humidity (%) vs. Latitude
    * Northern Hemisphere - Cloudiness (%) vs. Latitude
    * Southern Hemisphere - Cloudiness (%) vs. Latitude
    * Northern Hemisphere - Wind Speed (mph) vs. Latitude
    * Southern Hemisphere - Wind Speed (mph) vs. Latitude
    
# [VacationPy]
Use jupyter-gmaps and the Google Places API to:-
  * Create a heat map that displays the humidity for every city from WeatherPy
  
  * Narrow down the DataFrame to find the ideal weather condition, i.e.:
    * A max temperature lower than 80 degrees but higher than 70.
    * Wind speed less than 10 mph.
    * Zero cloudiness.
    * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
    
    
