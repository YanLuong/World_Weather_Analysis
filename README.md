# World Weather Analysis

This challenge consists of 3 sections:

1. **Retrieve Weather Data** - Roughly 2000 sets of random latitude and longitude is generated and then using Citipy to retrieve the nearest city. An API call is made to the OpenWeatherMap. For each of the random generated city, the current weather data is retrieved. A new dataframe is created to hold updated weather data for each city.
2. **Create a Customer Travel Destinations Map** - Input statements are used to get the customer temperature preference. With these preferences, potential travel destinations that match the criteria will be shown on google maps. These destinations are shown on a marker layer map with pop up markers.
3. **Create a Travel Itinerary Map** - Four cities chosen from a customer's possible travel destination will be used to create a travel itinerary using the Google Directions API. The route is displayed on a marker layer map with pop up markers for each city on the itinerary.

