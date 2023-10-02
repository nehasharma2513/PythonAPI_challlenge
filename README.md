# PythonAPI_challlenge
 Module 6 challenge

## WeatherPy
The Python script is written to visualize the weather of a large number of cities across the world of varying distance from the equator using citipy library, and the OpenWeatherMap API.

The visualizations are a series of scatter plots to show the relationship between Latitude and following weather variables:

1. Temperature
2. Humidity
3. Cloudiness
4. Wind Speed

Linear Regression is computed for each of the above Relationships.

## VacationPy

The Python script is written to perform the following steps using the Geoapify API :

1. Create a map that displays a point for every city in the city_data_df DataFrame 

2. Narrow down the city_data_df DataFrame to find your ideal weather conditions (i.e A max temperature lower than 27 degrees but higher than 21, Wind speed less than 4.5 m/s and Zero cloudiness)

3. For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates

4. Add the hotel name and the country as additional information in the hover message for each city in the map
