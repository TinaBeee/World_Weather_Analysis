## World Weather Analysis & Hotel Search
Uses APIs to generate weather data for hundreds of randomly generated city coordinates around the world and searches for nearby hotels

### Resources
- Data Sources: OpenWeather API, Google Maps API, Gmaps
- Software: Jupyter Notebook 6.3.0, Pandas library, Citipy library

### Project Overview
- Generated 2,000 random longtitude and latitude coordinates. 
- Then used the Citipy library to locate nearby cities, resulting in a total of 786 cities around the world. 
- Generated weather data for those locations using the OpenWeather API. 
- Narrowed the selection of cities by limiting based on temperature.
- Used Google's Nearby Places API to locate hotels near those selected cities.
- Used Gmaps to create maps and label markers for the hotels inside the map
