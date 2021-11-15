# World_Weather_Analysis

## Background
Retrieve world weather data with OpenWeatherMap, and create a Customer Travel Destinations Map using input statements to filter data for their weather preferences, and identify potential travel desitnations and nearby hotels. From the generated list of recommentions, the user could choose four cities to create a travel itinerary. Finally, use Google Maps Directions API to create a travel route between the four cities as well as a marker layer map.

## Analysis

### Retrieve Weather Data
Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data gathered in this module, use API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

* See folder [Weather_Database](Weather_Database/) for corresponding scripts and files.: 

    * [Weather_Database.ipynb](Weather_Database/Weather_Database.ipynb) for the Jupyter Notebook file created to retrieve the weather data.

    * The output DataFrame as a CSV file named [WeatherPy_Database.csv](Weather_Database/WeatherPy_Database.csv).

### Create a Customer Travel Destinations Map
Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

* See folder [Vacation_Search](Vacation_Search/) for the following scripts and files.:

    * [Vacation_Search.ipynb](Vacation_Search/Vacation_Search.ipynb) for the Jupyter Notebook file with th script to filter the DataFrame for the creation of a marker layer map.

    * The output DataFrame as a CSV file named [WeatherPy_vacation.csv]().

    * The output image of the marker layer map named [WeatherPy_vacation_map.png]().

![WeatherPy_vacation_map.png]().

### Create a Travel Itinerary Map
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

* See folder [Vacation_Itinerary](Vacation_Itinerary/) for the following scripts and files.:

    * [Vacation_Itinerary.ipynb]() for the Jupyter Notebook file with th script to retrieve four travel itineraries and marker layer maps. 

    * The output image of a directions layer map between the cities and the travel map is named [WeatherPy_travel_map.png]().

    ![WeatherPy_travel_map.png]()
    
    * The output image of the marker layer map with a pop-up marker for the cities in the itinerary created is named [WeatherPy_travel_map_markers.png]().

    ![WeatherPy_travel_map_markers.png]()

---

