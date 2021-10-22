# python-api-challenge
Repo for Python-API-HomeworkAssignment

Part I : WeatherPy Assignment


Dependent modules are imported.

citipy is installed and imported.

Unique latitude and longitude values/location pair are generated using np.random method.

Cities for the location pair are generated using the citipy.nearest_city method.

For each city, weather details are pulled using the API calls and the information is stored in different category lists like Latitude, Longitude, Country, Temperature, Humidity, Wind SPeed and Cloudiness.

For each city, json object is created with the API calls and added to a json array.

A data frame with the weather details are created and the data is written to a csv file.

Data with humidity greater than 100 is removed from the data frame.

Scatter plots to show the following relationships are drawn.

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

Linear regression on each relationship for Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude) are plotted.

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude


Part II - VacationPy

Cities are located from the WeatherPy dataframe created which fall under ideal weather conditions.

Humidity heat map is drawn.

Using Google Places API, first hotel for each city located within 5000 meters of the city is found.


Hotels on top of the humidity heatmap are displayed with pin containing the Hotel Name, City, and Country.