python-api-challenge

Part 1: WeatherPy--------------------------------------------------------------------------------------------------------------------------------------------------

Create a Python script to visualise the weather of over 500 cities of varying distances from the equator.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Use the OpenWeatherMap API to retrieve weather data from the cities list generated. Next, create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

Next, create a series of scatter plots (include the linear regression line, the model's formula, and the r value).

Northern Hemisphere: Temperature (C) vs. Latitude
Southern Hemisphere: Temperature (C) vs. Latitude

Northern Hemisphere: Humidity (%) vs. Latitude
Southern Hemisphere: Humidity (%) vs. Latitude

Northern Hemisphere: Cloudiness (%) vs. Latitude
Southern Hemisphere: Cloudiness (%) vs. Latitude

Northern Hemisphere: Wind Speed (m/s) vs. Latitude
Southern Hemisphere: Wind Speed (m/s) vs. Latitude

After each pair of plots, explain the linear regression modelling. Describe any relationships that you notice and any other findings you may uncover.

Part 2: VacationPy---------------------------------------------------------------------------------------------------------------------------------------------------

Use your weather data skills to plan future vacations. Use the Geoapify API and the geoViews Python library to create map visualisations.
Create a map that displays a point for every city. The size of the point should be the humidity in each city. 
Narrow down the dataframe and find your ideal weather condition. For example:

A max temperature < 27 but > than 21 degrees
Wind speed less < 4.5 m/s
Cloudness = 0

Create a new dataframe to store the city, country, coordinates, and humidity. For each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.
Add the hotel name and the country as additional information in the hover message for each city in the map.

