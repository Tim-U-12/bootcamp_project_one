# bootcamp_project_one


# The different types of vehicles listed in US from the year 2000 to 2022

# Summary

* The cleaned dataset of vehicles listed in the US was used for drawing conclusions about the different types of vehicles listed in US from the year 2000 to 2022. 
* The number of different types of vehicles listed was found and the percentage of each type of vehicles was calculated.
* The top and bottom 5 types of vehicles listed were found out.
* The year-wise trend of number of different types of cars listed was plotted to understand how it has changed from 2000 to 2022.
* The top 3 manufacturers listed for vehicle types SUV and sedan were found out.
* The year-wise trend of maximum price of suv and sedan cars listed was plotted to understand how it has changed from 2000 to 2022.
* The price of the top 3 manufacturers of SUV and sedan was plotted to understand the maximum price of the vehicles listed.

# Conclusions

* From among the 13 different types of vehicles listed, SUV and sedan holds the highest percentage with 27.1% and 28.5% respectively.
* The top 5 types of vehicles that are listed are: sedan, SUV, truck, pickup and hatchback and the lowest 5 types of vehicles that are listed are: bus, offroad, wagon,convertible and  mini-van.
* The year-wise trend of number of different types of cars listed shows that over the years from 2000 to 2022, SUV and sedan are always the types with highest number of cars listed. Also, a sharp rise in the number of cars listed can be observed in 2014. This was due to the lower gas prices in US. 
* The top 3 manufacturers of suv are Ford, Jeep and Chevrolet and the top 3 manufacturers of sedan are Chevrolet, Toyota and Honda.
* The maximum price of suv and sedan have been rising over the years since 2000. There was a sharp rise in the price in 2009 and 2014. This was because of the weak economy and falling supply of new cars.
* In the case of SUV, Ford has the maximum price listed and in the case of sedan, Chevrolet has the maximum price listed.

## USA Used Vehicle Market Analysis - Project Team 7

## Project Scenario
Our corporate client Used-Car Online Pty Ltd (UCO) is asking us to provide a comprehensive data analysis of the used car online market in the USA, according to the dataset file named ‘Vehicles.csv’. UCO requires us the following:
- Demonstrate a clear data frame to list ['id', 'region', 'price', 'year', 'manufacturer', 'model', 'condition', 'cylinders', 'fuel', 'odometer', 'title_status', 'transmission', 'drive', 'size', 'type', 'paint_color', 'description', 'county', 'state', 'lat', 'long', 'posting_date’]
- The top 10 state ranking by the most cars listed and its correlation with population each state - Ina
- Correlation between odometer (kms run) and price of the car – Dhiraj
- The different types of vehicles listed in US from the year 2000 to 2022 – Anjana
- Observations based on comparing the Color of the Vehicles listed with the number of listings, prices of listings and manufacturer – Deon

## Dataset Source from: 
- https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data?resource=download
- https://worldpopulationreview.com/states/state-abbreviations
- https://worldpopulationreview.com/states

## Which state is the most potential market? - Ina
The top 10 states have occupied more than half of the total number of listed vehicles. Especially the top 3 states California, Florida & New York State. The top 3 states share nearly one-third of listed vehicle numbers and generally consider California will be the biggest potential market followed by Floria & New York States. And the other states in the top 10 could be covered in the 2nd stage of marketing strategical development.

The hvplot with the open map also shows the geographical location of the top 10 states by their longitude and latitude. It is obvious to find out the top 10 states mainly located on the eastern or western coasts of USA. The size of the bubble reflects the total number of listed vehicles. This will be clearly identified that Califonia held the largest number of listed vehicles followed by Florida and New York State.

The Pearson’s r is 0.89 and means a fairly strong positive relationship between the population and the number of listed vehicles. This reminds us to focus on developing online sales markets in the states with a larger population. The Pearson’s r is 0.17 only between population density and Total_listed vehicles. The value is considered to be a weak correlation between the population density of the state and the total listed vehicles. The population density will not the factor to affect the used vehicle market in USA

The top 3 potential market is California, Florida, and New York State. These top 3 states are occupied one-third of the total listed vehicles. Geographically, the states located on the western and eastern coasts will be considered the better potential markets than inland areas. The Pearson correlation coefficient of 0.89 between the population in 2022 and the total listed vehicles tell us the strong relationship and the states with larger population may be better potential markets but it will not be necessary to consider the population density of states.

## Correlation between odometer (kms run) and price of the car – Dhiraj
Higher the Odometer reading, lower the price of the car. We can see that from the graph above.
Vehicles plotted on the botom right hand corner.
These vehicles are very high on the their odometer reading and hence the price of the vehicle has depreciated.
Vehicles plotted on the top left hand corner.
These vehicles are very low on the their odometer reading and hence the price of the vehicle is high.
Other factors to take into consideration while analysing this relation:
Year of manufacture is also have a bearing on the price of the vehicle.

## The different types of vehicles listed in US from the year 2000 to 2022 - Anjana
### Summary
  •	The cleaned dataset of vehicles listed in the US was used for drawing conclusions about the different types of vehicles listed in US from the year 2000 to 2022.
  
  •	The number of different types of vehicles listed was found and the percentage of each type of vehicles was calculated.
  
  •	The top and bottom 5 types of vehicles listed were found out.
  
  •	The year-wise trend of number of different types of cars listed was plotted to understand how it has changed from 2000 to 2022.
  
  •	The top 3 manufacturers listed for vehicle types SUV and sedan were found out.
  
  •	The year-wise trend of maximum price of suv and sedan cars listed was plotted to understand how it has changed from 2000 to 2022.
  
  •	The price of the top 3 manufacturers of SUV and sedan was plotted to understand the maximum price of the vehicles listed.
### Conclusions
  •	From among the 13 different types of vehicles listed, SUV and sedan holds the highest percentage with 27.1% and 28.5% respectively.
  
  •	The top 5 types of vehicles that are listed are: sedan, SUV, truck, pickup and hatchback and the lowest 5 types of vehicles that are listed are: bus, offroad, wagon,convertible and mini-van.
  
  •	The year-wise trend of number of different types of cars listed shows that over the years from 2000 to 2022, SUV and sedan are always the types with highest number of cars listed. Also, a sharp rise in the number of cars listed can be observed in 2014. This was due to the lower gas prices in US.
  
  •	The top 3 manufacturers of suv are Ford, Jeep and Chevrolet and the top 3 manufacturers of sedan are Chevrolet, Toyota and Honda.
  
  •	The maximum price of suv and sedan have been rising over the years since 2000. There was a sharp rise in the price in 2009 and 2014. This was because of the weak economy and falling supply of new cars.
  
  •	In the case of SUV, Ford has the maximum price listed and in the case of sedan, Chevrolet has the maximum price listed.

## Observations based on comparing the Color of the Vehicles listed with the number of listings, prices of listings and manufacturer – Deon
### Observations
 - White Color Vehicles are the most listed with 17,790 listings.
 - Followed by Black(13,038), Silver(11,058), Grey(9082), Blue(7414) and Red(6649) Color Vehicles.
 - The Vehicle Color with the fewest listings is Purple with 173 listings.

 - White Color Vehicles had the largest sum price of listings (USD 295.8 million).
 - Followed by Black(USD 190.4 million), Silver(USD 119.5 million), Grey(USD 115.4 million), Red(USD 84.9 million) and Blue(USD 82.6 million) Color Vehicles.
 - Even though there are 765 more Blue Vehicles listed than Red Vehicles, the sum price of listings of Red Vehicles is greater than that of Blue Vehicles by USD 2.3 million.
 _ The Vehicle Color with smallest sum price of listings is Purple with USD 1.6 million.

 - The Vehicle Manufacturer with the largest number of White Vehicles listed is Ford with 5468 listings.
 - The second largest is Chevrolet with 3110 White Vehicles Listed.
 - Both these manufacturers are American owned.
 - The third largest is Toyota with 1167 White Vehicles Listed. (Japanese Owned)
