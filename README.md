# WeatherPy - Weather Analysis and Vacation Information
## Project Overview
While working with Jack, the head of analysis at the Plan My Trip company we built a travel application to help people plan their vacations. The application helps refine their search using weather and hotel criteria. The application also allows vacationers to plan their traveling routes using google maps.  
## Resources
-	Software: Python 3.7.6, Anaconda Version 4.10.3, Jupyter Notebook
-	APIs: OpenWeatherMap, Google Maps Platform
## Results

### Weather Database Summary 
To help vacationers find a city to travel to we randomly generated 2000 coordinates using python tools. With the randomly generated coordinates we matched the nearest city using the Open Weather Application by utilizing and API. Of our initial 2000 coordinates, there were approximately 675 cities that had weather data available in the Open Weather Application. 

### Vacation Search Application Summary
Using the Weather Database we created, we were able to pull in the unique city weather data for vacationers to review. We built in a filter to allow users to refine their search results based on temperature. This feature will allow users to narrow their search results depending on what type of vacation they are looking for. For this example, we narrowed the search results down to have warmer temperatures for someone looking to escape from the winter cold. After filtering the results there were approximately 186 cities that met the temperature filters that had a hotel within a reasonable distance. Using our google API we were able to generate a map that users could easily review cites, the weather for that city and nearby hotels. 
Below is an example of the map we created: 

!Insert Map1

### Vacation Itinerary Application
Once users had selected a general area or a few cities that they would like to travel to we were able to generate a travel map, again using our google API. This feature of the application conveniently shows a directional map of how users can travel from destination to destination along with the weather for the city and nearby hotels. 
Below is and example of the map with directions that we created: 

!Insert Map 2

## Summary 
This application provides a convenient tool for vacationers to plan a trip as well as routes based on their ideal weather. It will also allow them to find nearby hotels. Overall we think that this tool will help take some of the stress out of planning a vacation. 
