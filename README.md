# WeatherPy

## Project Overview
  - Task: Collect and analyze weather data across cities worldwide.
  - Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
  - Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting,               analyzing, and visualizing the data.

### Deliverable 1

[Weather Database Code](Weather_Database/Weather_Database.ipynb)

[WeatherDatabase csv](Weather_Database/WeatherPy_Database.csv)


#### Collect the Data

  - Use the NumPy module to generate more than 2000 random latitudes and longitudes.
  - Use the citipy module to list the nearest city to the latitudes and longitudes.
  - Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
  - Parse the JSON data from the API request.
  - Collect the following data from the JSON file and add it to a DataFrame:
  
        - City, country
        
        - Latitude and longitude
        
        - Maximum temperature
        
        - Humidity
        
        - Cloudiness
        
        - Wind speed
        
        - Current Description
        
### Deliverable 2: Create a Customer Travel Destinations Map

[Vacation Search Code](Vacation_Search/Vacation_Search.ipynb )

[WeatherPy vacation csv](Vacation_Search/WeatherPy_vacation.csv )


  - Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

        - Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
      
        - Create a heatmap for the new DataFrame.
     
        - Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.

        - Store the name of the first hotel in the DataFrame.
     
        - Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
     
### Deliverable 3: Create a Travel Itinerary Map

[Vacation_Itinerary Code](Vacation_Itinerary/Vacation_Itinerary.ipynb )

  - For this deliverable, we will use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s        possible travel destinations. 
  - Then, we will create a marker layer map with a pop-up marker for each city on the itinerary.

## Results 
![Test Image](/Vacation_Search/WeatherPy_vacation_map.png)

[WeatherPy vacation PNG](Vacation_Search/WeatherPy_vacation_map.png )


![Test Image](/Vacation_Itinerary/WeatherPy_travel_map.png)

[WeatherPy_travel_map PNG](Vacation_Itinerary/WeatherPy_travel_map.png )


![Test Image](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

[WeatherPy_travel_map_markers PNG](Vacation_Itinerary/WeatherPy_travel_map_markers.png )
