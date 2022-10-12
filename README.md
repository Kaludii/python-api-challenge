# Unit 6 Assignment: What's the Weather Like?


## 1st Section: WeatherPy

In this section, I created a Python script to visualize the weather of 500+ cities of varying distance from the equator using [simple Python library](https://pypi.python.org/pypi/citipy), and [OpenWeatherMap API](https://openweathermap.org/api).

The first requirement was to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot, I added a sentence or two explaining what the code is analyzing.

The second requirement was to compute the linear regression for each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

My notebook includes:

* Randomly select **at least** 500 unique (non-repeated) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed, with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.

### 2nd Section: VacationPy

* Created a heat map that displays the humidity for every city from Part 1.

* Narrowed down the DataFrame to find the ideal weather conditions.

* Used Google Places API to find the first hotel for each city located within 5,000 meters of the coordinates.

* Ploted the hotels on top of the humidity heatmap, with each pin containing the **Hotel Name**, **City**, and **Country**.