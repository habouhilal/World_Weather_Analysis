# World_Weather_Analysis
## Overview 
This project has an objective to retrieve different aspects of weather data and hotel informations for over 500 cities worldwide in real time. For this reason we used Google API to request some JSON data and create our own data to research and git and output on maps for the customer. 
The project also creates a travel itinerary. The cities are chosen from customer’s possible travel destinations. Finally, using the Google Maps Directions API, I will create a travel route between the four cities as well as a marker layer map.

## Results
This project was realized on 3 phases. Using outputs fron Phase 1 to finalize phase 2 and phase 2 outputs to realize phase 3. 

### Phase 1 
This step consist of conducting and API search on Google API. For this step we also had to create and utilize and API key. We requested Json file response and we created 2000 random longitudes and Latitudes. Then we used CITYPY module to get the nearest cities. Gathering the  all information for the city we stores it on dataframe and then CSV file to use it on the next phase. 

### Phase 2 
I Used input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.


### Phase 3 
create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

## Summary 
Using API search is very interseting to get real live information direct from the API websites. Also very relative because every API utilizes it's own documentation and parameters.
We used weather API key offered to use gmaps and get weather information. The only limitation on this project is that the user has to choose destinations from the cities created on the first random lng and lat. but that still give a large choice for the user. 
