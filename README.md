# WeatherPy

## Project Overview
  - Task: Collect and analyze weather data across cities worldwide.
  - Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
  - Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting,               analyzing, and visualizing the data.

## Deliverable 1

### Collect the Data

  - Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
  - Use the citipy module to list the nearest city to the latitudes and longitudes.
  - Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
  - Parse the JSON data from the API request.
  - Collect the following data from the JSON file and add it to a DataFrame:
  
        - City, country, and date
        
        - Latitude and longitude
        
        - Maximum temperature
        
        - Humidity
        
        - Cloudiness
        
        - Wind speed
        
        - Current Description
