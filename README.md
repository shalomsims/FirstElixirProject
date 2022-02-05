# FirstElixirProject
Overview

Using the MetaWeather API (https://www.metaweather.com/api/) find the average max temperature in Salt Lake City, Los Angeles, and Boise for a 6 day forecast. In Elixir, start a new mix project (mix new project_name) and make these API calls concurrently (you could spawn new processes, use Tasks, or Genservers). We’re looking to see how you use Elixir and specifically some of it’s functional coding features. Please use software best practices and document and test your code to a reasonable extent, consider mocking the Metaweather API for testing.



Details

The URLs to get temperatures for the 3 cities are:

 

Salt Lake City: https://www.metaweather.com/api/location/2487610/

 

Los Angeles: https://www.metaweather.com/api/location/2442047/

 

Boise: https://www.metaweather.com/api/location/2366355/

 

According to the MetaWeather API each one of these API calls will return a field called "consolidated_weather". It contains a weather forecast for the city for each day including today and the next 5 days. Each forecast includes a field called "max_temp" that is the max temperature for that forecasted day. Find the average of max_temp for all forecasts for the city.

 

Expected Output

Simply list each city with the calculated average max_temp in this form:

 

Salt Lake City Average Max Temp: 35.73

Los Angeles Average Max Temp: 29.84

Boise Average Max Temp: 32.63



Your numbers will differ slightly as forecasts can change.
