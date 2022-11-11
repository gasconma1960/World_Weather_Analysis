# World_Weather_Analysis
Using Python, Jupyter Notebook and API Call from Google Maps API's be able to analyze a travel preferences

## **Background**

  Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they've recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data.
  
## **Purpose** 

  Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.I'll employ input statements to retrieve customer weather preferences. Next, I'll use those preferences to identify potential travel destinations and nearby hotels. Finally, I'll show those destinations on a marker layer map with pop-up markers.  
  
  
## Deliverable 1: Retrieve Weather Data

  Retrieve the following information from the API call.
  - The latitude and longitude
  - The Max temperature
  - The % humidity
  - The % cloudiness
  - The Wind speed
  - The Weather description, i.e., cloudy, fog, light rain, clear sky, etc.
  
 ***Screen shot below shows the DataFrame displaying all the information retrive using an API Call***

![image](https://user-images.githubusercontent.com/112348240/201305009-5028250f-2d92-4a30-b8f0-8cd2961dcf34.png)

## Deliverable 2: Create a Customer Travel Destinations Map

  For this deliverable, I wrote two input statements that prompt the user to enter their minimum and maximum temperature criteria for their vacation. Also,  Use a for loop to iterate through the hotel_df DataFrame, retrieve the latitude and longitude of each city to find the nearest hotel based on the search parameters provided, then add the hotel name to the hotel_df DataFrame. If a hotel isn't found, skip to the next city. Then, drop any rows in the hotel_df DataFrame where a hotel name is not found and store the resulting data into a new DataFrame named clean_hotel_df.

![image](https://user-images.githubusercontent.com/112348240/201306219-e6e844c7-9f85-4c38-8305-6b6414e33b89.png)

***The screen shot below shows The marker layer map with a pop-up marker for each city***

![image](https://user-images.githubusercontent.com/112348240/201305981-ca9233ee-66b0-4008-b714-58b6abe0870a.png)


## Deliverable 3: Create a Travel Itinerary Map
  For this deliverable, you'll use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, you'll create a marker layer map with a pop-up marker for each city on the itinerary.
  The four destinations choosen were :
  - Watertown,
  - Palmer, 
  - Bethel, and
  - Mastic Beach
 
 ***The screen shot below shows the directions layer map*** 

![WeatherPy_travel_map](https://user-images.githubusercontent.com/112348240/201307091-9f534884-9251-4d70-b989-483b7eb51e55.png)

***The screen shot below shows The marker layer map with a pop-up marker for each city choose for this Vacation Itinerary*** 

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/112348240/201307128-b04bf7b4-ebfb-421b-b5c4-6ea482150ad1.png)
