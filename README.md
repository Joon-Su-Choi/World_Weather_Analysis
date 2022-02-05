# World_Weather_Analysis

We will be using the Google Maps Directions API to create a travel route between four cities in California as well as a marker layer map. The cities are Pacifica, Half Moon Bay, Pleasanton, and Salinas.

## Retrieve Weather Data

In our Weather_Database folder we generated a set of 2,000 random latitudes and longitudes to retrieve the nearest city and performed an API call with OpenWeatherMap. We were able to retrieve current weather desciptions for each city.

![weather_description](https://user-images.githubusercontent.com/95505596/152648440-728e8819-2bc1-47f6-8eee-9cc87aa626a8.png)

## Customer Travel Destinations Map

By retrieving the customer's weather preferences we identified potential travel destinations and nearby hotels. We made a marker layer map with pop-up markers for each city.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/95505596/152648645-311c0df4-b3cd-4947-a696-bfa6b5205b15.png)

## Travel Itinerary Map

Using the Google Directions API we created a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. We then created a marker layer map with a pop-up marker for each city on the itinerary.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/95505596/152649022-81d6ed50-70ec-4fa9-9619-ccfbf553c054.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/95505596/152649026-455bfb28-bb01-4b6c-b9f6-106145d96313.png)
