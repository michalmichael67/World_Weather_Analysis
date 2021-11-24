# World_Weather_Analysis

This challenge is made up of 3 pieces of work. The goal of this challenge is to plan an itinerary for a trip with 4 cities based on weather criteria. 

## Creating a Weather Database
In this part of the challenge, the goal was to retrieving the weather data. 
- We generated a list of random latitudes and longitudes 
- We used citipy to find the nearest city for each lat/lng pair
- We connected to the open weather api to pulled the corresponding weather data for those locations. 
- We then output the data into a csv file 

## Vacation Search
In the second part of the challenge, the goal was to create a map with a hotel for all of the possible cities that were found in part 1 and that correspond to preferable weather patterns.
- We prompt the user to input a minimum and maximum temperature for the trip.
- Based on that number, we created a dataframe with the preferred cities.
- We then connected to the gmaps Nearby Search API to find the closest hotel for each preferred city and output this list as a CSV.
- We then used gmaps to map out the cities and hotels in a live map.

## Vacation Itinerary
In the last portion of the challenge, we identified 4 cities within a country and created a road trip between the 4 cities for the travelers. 
- We connected to the gmaps api to show the possible vacation destinations and searched the map until we found 4 cities to travel to.
- Using the direction layer from the gmaps api, we created an itinerary between the 4 cities and mapped it. We also added the hotels for each of the 4 cities in a marker layer to make the map easier to read.