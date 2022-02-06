# World_Weather_Analysis

## Deliverables Module 6
* Deliverable 1: Retrieve Weather Data
* Deliverable 2: Create a Customer Travel Destinations Map
* Deliverable 3: Create a Travel Itinerary Map
### Deliverable #1
# https://github.com/jcsargis00/World_Weather_Analysis/tree/main/Weather_Database
Go to directory Weather_Database to find files
    - Weather_Database.ipynb
    - WeatherPy_Database.csv file
#
1. Retrieve all of the following information from the API call:
    - Latitude and longitude
    - Maximum temperature
    - Percent humidity
    - Percent cloudiness
    - Wind speed
    - Weather description (for example, clouds, fog, light rain, clear sky)
#
2. Add the weather data to a new DataFrame 
#
3. Export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder 
#
### Deliverable #2
# https://github.com/jcsargis00/World_Weather_Analysis/tree/main/Weather_Database/Vacation_Search
Go to directory Weather_Database/Vacation_Search to find files:
#
    - Vacation_Search.ipynb 
    - WeatherPy_vacation.csv 
    - WeatherPy_vacation_map.png 
# Vacation_Search.ipynb code includes the following
* Input statements are written to prompt the customer for their minimum and maximum temperature preferences. 
* A new DataFrame based on the minimum and maximum temperature, and empty rows are dropped. 
* The hotel name retrieved and added to the DataFrame, rows that don’t have a hotel name are dropped. 
* The DataFrame is exported to a CSV file into the Vacation_Search folder, saved as WeatherPy_vacation.csv. 
* A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information: 
    - Hotel name
    - City
    - Country
    - Current weather description with the maximum temperature
* The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png. 
### Maximum Temperature >50 degrees and <90
![world map by temperature preferences](https://github.com/jcsargis00/World_Weather_Analysis/blob/main/Weather_Database/Vacation_Search/WeatherPy_vacation_map.PNG)
### Deliverable #3
# https://github.com/jcsargis00/World_Weather_Analysis/tree/main/Weather_Database/Vacation_Search/Vacation_Itinerary
Go to directory Weather_Database/Vacation_Search/Vacation_Itinerary to find files:
    - Vacation_Itinerary.ipynb
    - WeatherPy_travel_map.png
    - WeatherPy_travel_map_markers.png
# 
* Four DataFrames are created, one for each city on the itinerary. 
* The latitude and longitude pairs for each of the four cities are retrieved. 
* A directions layer map between the cities and the travel map uploaded as WeatherPy_travel_map.png. 
* A DataFrame with the four cities on the itinerary is created. 
* A marker layer map with a pop-up marker for the cities on the itinerary uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information: 
    * Hotel name
    * City
    * Country
    * Current weather description with the maximum temperature
#### Vacation Itinerary - four cities near the famous Skeleton Coast in Africa
![Vacation Itinerary](https://github.com/jcsargis00/World_Weather_Analysis/blob/main/Weather_Database/Vacation_Search/Vacation_Itinerary/WeatherPy_travel_map.png)






