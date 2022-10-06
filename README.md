# WeatherPy

## Project Overview
  - Task: Collect and analyze weather data across cities worldwide.
  - Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
  - Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting,               analyzing, and visualizing the data.

## Deliverable 1

### Collect the Data

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
        
## Deliverable 2: Create a Customer Travel Destinations Map

  - Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

        - Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
      
        - Create a heatmap for the new DataFrame.
     
        - Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.

        - Store the name of the first hotel in the DataFrame.
     
        - Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city
     
## Deliverable 3: Create a Travel Itinerary Map
