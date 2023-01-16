# bootcamp_project_one
USA Used vehicle Market analysis - Project Team 7

Project Sceario
Our corporate client Used-Car Online Pty Ltd (UCO) is asking us to provide a comprehensive data analysis of the used car online market in the USA, according to the dataset file named ‘Vehicles.csv’. UCO requires us the following:
- Demonstrate a clear data frame to list ['id', 'region', 'price', 'year', 'manufacturer', 'model', 'condition', 'cylinders', 'fuel', 'odometer', 'title_status', 'transmission', 'drive', 'size', 'type', 'paint_color', 'description', 'county', 'state', 'lat', 'long', 'posting_date’]
- Summarize key information:
- Which type of cars were mostly listed – Anjana
- What is the most popular color listed – Deon
- Correlation between odometer (kms run) and price of the car. – Dhiraj
- The top 10 state ranking by the most cars listed and its correlation with population each state - Ina

Dataset Source from: 
- https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data?resource=download
- https://worldpopulationreview.com/states/state-abbreviations
- https://worldpopulationreview.com/states

Summary:
The top 10 states have occupied more than half of the total number of listed vehicles. Especially the top 3 states California, Florida & New York State. The top 3 states share nearly one-third of listed vehicle numbers and generally consider California will be the biggest potential market followed by Floria & New York States. And the other states in the top 10 could be covered in the 2nd stage of marketing strategical development.

The hvplot with the open map also shows the geographical location of the top 10 states by their longitude and latitude. It is obvious to find out the top 10 states mainly located on the eastern or western coasts of USA. The size of the bubble reflects the total number of listed vehicles. This will be clearly identified that Califonia held the largest number of listed vehicles followed by Florida and New York State.

The Pearson’s r is 0.89 and means a fairly strong positive relationship between the population and the number of listed vehicles. This reminds us to focus on developing online sales markets in the states with a larger population. The Pearson’s r is 0.17 only between population density and Total_listed vehicles. The value is considered to be a weak correlation between the population density of the state and the total listed vehicles. The population density will not the factor to affect the used vehicle market in USA

- Which state is the most potential market?
The top 3 potential market is California, Florida, and New York State. These top 3 states are occupied one-third of the total listed vehicles. Geographically, the states located on the western and eastern coasts will be considered the better potential markets than inland areas. The Pearson correlation coefficient of 0.89 between the population in 2022 and the total listed vehicles tell us the strong relationship and the states with larger population may be better potential markets but it will not be necessary to consider the population density of states.

