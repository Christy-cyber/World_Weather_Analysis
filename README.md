# World Weather Analysis
## Overview and Deliverables
- Retrieve weather data for potential vacation travel destinations
- Create a travel destinations map that includes a marker layer map and pop-up markers for cities meeting certain temperature criteria
- Create a travel itinerary map with pop-up markers with weather and hotel information for selected cities on the vacation itinerary. 

## Resources
- Data and Information Sources: OpenWeather API 2022 (https://openweathermap.org/api); Google Maps Platform API  2022 (https://mapsplatform.google.com/); Google Maps Platform--Directions API  2022 (https://mapsplatform.google.com/maps-products/#directions)
- Software and Programming Languages: Jupyter Notebook v. 6.4.6; Python v. 3.8.3 :: Anaconda, Inc.; conda v. 4.11.0; Matplotlib v. 3.5.0; Citipy v. 0.0.5 

## Weather and Itinerary Results
- A database (.csv file) of 694 cities produced from randomly selected latitude and longitude coordinates was created that included information on latitude/longitude, maximum temperature, cloudiness, wind speed, and current weather description.

- A travel destinations map was created from the database based on customer temperature preferences for a travel destination.  This included a marker layer map with a pop-up for each city that included weather information (Fig 1.).

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/95387273/151462484-f679a23a-a45e-4895-a988-5cdea66a7010.png)
Fig. 1.  Travel destinations with marker layer map based on customer temperature preferences.  Created by account holder on 26 Jan 2022 with Google Maps Platform API.


- A travel itinerary map with pop-up markers with hotel information was included for the specific travel itinerary (Fig. 2).

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/95387273/151463286-5b90f55e-7566-4f0a-9fc3-f6e6df86cb30.png)
Fig. 2.  Trip itinerary with marker layer map and pop-up markers.  Created by account holder on 27 Jan 2022 with Google Directions API (https://mapsplatform.google.com/maps-products/#directions).
