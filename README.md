# World_Weather_Analysis

## Vacation planning using a combination of google APIs and weather information. 

## The Weather_Database folder with the following:

- The Weather_Database.ipynb file - Gets weather # Starting URL for Weather Map API Call url = "http://api.openweathermap.org/data/2.5/weather?units=Imperial&APPID=" + weather_api_key
- The WeatherPy_Database.csv file

## The Vacation_Search folder with the following:

- The Vacation_Search.ipynb file -     # 6d. Set up the base URL for the Google Directions API to get JSON data.
    base_url = "https://maps.googleapis.com/maps/api/place/nearbysearch/json" Make request and retrieve the JSON data from the search. hotels = requests.get(base_url, params=params).json()
- The WeatherPy_vacation.csv file
- The WeatherPy_vacation_map.png image

## The Vacation_Itinerary folder with the following:

- The Vacation_Itinerary.ipynb file - # 8. To create a marker layer map between the four cities. Combine the four city DataFrames into one DataFrame using the concat() function. 
- The WeatherPy_travel_map.png image
- The WeatherPy_travel_map_markers.png image
