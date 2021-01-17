# World_Weather_Analysis1

## Resources
  - Software:  Anaconda 4.9.2, Jupyter Notebook 6.0.3 , Python 3.7.6 
  - Using:  Pandas, Matplotlib, Numpy, CityPy
  - APIs:  openweathermap.org, gmaps

  
## Overview of the analysis:

Overall the aim was to:

1) Randomly generate paired longitudes and latitudes
2) Identify the nearest cities to our coordinates using CitiPy
3) Call the weather API and pull weather details for the cities including:
   - city latitude and longitude
   - max temp
   - humidity
   - clouds
   - wind speed
   - country
   - weather description
4) Parse the JSON for the details mentioned above and create a list
5) Add the data to a new Pandas DataFrame
6) Generate a CSV file from the DataFrame called WeatherPy_Database
7) Create an input box for users to enter minimum and maximum temperatures for their vacation search
8) Use the input parameters to filter the WeatherPy_Database with cities matching the min/ max teperature requirements for the vacation search
9) Create a new DataFrame with a Hotel Name column
10) Use the gmaps API to pull the first hotel listed in each city
11) Clean the data so there were no rows with missing hotel name
12) Create a new Clean Hotel DataFrame
13) Export a Vacation_Search CSV file
14) Create a map with markers and pop up infoboxes with data from our DataFrame
15) Create a new Vacation DataFrame
16) Create a new Dataframe to store all latitudes and longitudes
17) Create new infoboxes detailing: city name, country code, current weather description and max temp
18) Generate a new map with a marker layer for the locations that displays the infoboxes when locations markers are clicked
19) From the map pick 4 cities and create a vacation itinerary route to travel between the four cities
20) Using the gmaps API generate a new map that shows the route between the cities when driving
21) Generate a new map with infoboxes / marker layers for each of the four cities


## Purpose of the analysis:
In essence the purpose was to write code to create an interactive vacation planning tool using input boxes, info pull from APIs and generating maps with routes and helpful facts about the locations.



## Further Exploration
It would be really easy to reuse existing code and update the script to accomodate additional vacation search criteria (like hotel star ratings/ reviews etc.) This would be an exciting contiunuation project.

