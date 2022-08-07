# World_Weather_Analysis

## Project Overview
PlanMyTrip is a top travel technology company that specializes in internet related services in the hotel and lodging industry. Their user interface team head of analysis has asked us to help collect and present data for customers via the search page, which they will then filter based on their preferred travel criteria in order to find their ideal hotel anywhere in the world. We are tasked to collect data of a variety of weather parameters from over 500 cities around the world, as this data will help the team predict the best time of year for people to plan their vacation. Using this data, we will be using it to choose the best cities for a vacation based on certain weather criteria. 


## Resources
Data Source: WeatherPy
Software: Anaconda, Jupyter Notebook, Pandas, APIs


## Project Summary
We used Jupyter Notebook and the CityPy module to get the cities for about 2000 random latitudes and longitudes. We then performed requests on the OpenWeather map API to retrieve the JSON weather data from those cities. The weather data was then added to a Pandas DataFrame, which we used Matplotlib to create a series of scatter plots to show the relationship between the latitude and a variety of weather parameters for those cities. Using this data, we used Jupyter G Maps and the Google Places API the cities to exhibit the data for customers to choose their ideal vacation based on certain weather criteria. 

##### Latitude vs. Max Temperature
![Screenshot 2022-08-07 000317](https://user-images.githubusercontent.com/107603065/183279382-be7201ff-de83-46e8-9d71-a80f039ca174.png)

##### Latitude vs. Wind Speed
![Screenshot 2022-08-07 000332](https://user-images.githubusercontent.com/107603065/183279386-7710bb17-cad3-4dc6-8ad2-1a1b5fe894e8.png)

##### Linear Regression on Southern Hemisphere for Humidity
![Screenshot 2022-08-07 000348](https://user-images.githubusercontent.com/107603065/183279394-ca3299a2-13e1-498f-95cb-2cf9bfdec173.png)

##### WeatherPy Vacation Map
![Weather_Py_vacation_map](https://user-images.githubusercontent.com/107603065/183279367-63818409-1ba5-49af-bfe9-8d4dee28be20.png)


##### WeatherPy Travel Map
![WeatherPy_travel_map](https://user-images.githubusercontent.com/107603065/183279482-4f72dc6b-2abb-4ddc-bd04-0ed0a07bcfcb.png)

