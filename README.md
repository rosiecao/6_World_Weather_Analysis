# 6_World_Weather_Analysis
# Project Overview
Jack has given me the following tasks to help him adding a few changes to the PlanMyTrip app:
- Adding the weather description to the weather data
- then use input statements from the beta testers to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels.
- and from the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary.
- finally, using the Google Maps Directions API to create a travel route between the four cities as well as a marker layer map

# Results

1/ Retrieve Weather Data
A DataFrame and CSV file below is containing the updated weather data which included the current weather description for each nearest city in a set of 2,000 random latitudes and longtitudes.

![image](https://user-images.githubusercontent.com/89699219/138605810-d8a2ac28-1b02-4f2a-9a38-bff272f75378.png)
[WeatherPy_Database.csv](https://github.com/rosiecao/6_World_Weather_Analysis/files/7405959/WeatherPy_Database.csv)


2/ Create a Customer Travel Destinations Map

The CSV file below is containing potential travel destinations and nearby hotels of all citis have the temperture range from 60 to 70.

[WeatherPy_vacation.csv](https://github.com/rosiecao/6_World_Weather_Analysis/files/7405982/WeatherPy_vacation.csv)

and below is the marker layer map with a pop-up marker for each city
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/89699219/138606325-16317358-8e90-4400-9194-9a5f66f7aea7.PNG)

3/ Create a Travel Itinerary Map

The directions layer map shows the route between four cities choosen from the customer's possible travel destinations:

![WeatherPy_travel_map](https://user-images.githubusercontent.com/89699219/138606377-9fc14b90-606a-4972-9281-6caf24dcb180.PNG)

A marker layer map with a pop-up marker for each city on the itinerary:

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/89699219/138606379-38459555-4694-4dc0-b65e-08451cb4a641.PNG)
