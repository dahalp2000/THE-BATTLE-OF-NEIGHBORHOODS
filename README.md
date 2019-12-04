# THE-BATTLE-OF-NEIGHBORHOODS
FIND OUT BEST LOCATION TO OPEN INDIAN RESTAURANT IN EDMONTON, CANADA

THE BATTLE OF NEIGHBORHOODS

FIND OUT BEST LOCATION TO OPEN INDIAN RESTAURANT IN EDMONTON, CANADA

PRABIN DAHAL
12/3/2019

1.	INTRODUCTION
1.1	BACKGROUND
Being a Canadian citizen and living in Edmonton for more than 7 years, I want to focus my project work within same city. My project will help for Restaurant business owners who wants to start their business career in Edmonton city and looking for better business location within this city to open an Indian restaurant. 


1.2	BUSINESS PROBLEM
Anyone who wants to start business in new city is challenging if they are not familiar with the location and they are not aware if business is targeted for the community within the neighborhood. Searching a best location for Restaurant is not an easy task in today’s world as there are several requirements needed to fulfill to get this task done. On top of that, we need to find better place where targeted customers are interested in your business. At present scenario, there are multiple restaurant businesses operating in almost each location. Customer are so selective that they want to visit/order from restaurant where they can find food of their choice.

1.3	Target
As a student of data science, I want to provide some research so that it will be easier for anyone who wants to start their career in this field as Restaurant owner and overcome this extra headache to find proper location for business. I will provide recommendation based on finding that they can consider before opening new restaurant.




DATA SECTION

1.	Data section introduction
I will provide recommendation based on finding that new restaurant owners can consider before opening new Indian restaurant, my goal will be to find location that is most suitable to open new Indian restaurant in Edmonton. For the purpose, I will collect data with highest number of Indian community and perform data analyses to find the result.


2.	Background 
Edmonton has a total of 12 borough and 400 neighborhoods with total population of 97,2223 (2019). In order to segment the neighborhoods and explore them, we will essentially need a dataset that contains the 12 boroughs and the neighborhoods that exist in each borough as well as the latitude and longitude coordinates of each neighborhood. 


3.	Data mining
From the data obtained, I will convert addresses into their equivalent latitude and longitude values. Also, will determine Indian community within each location. After merging these files and finding most dense Indian community I will select this denser location and use the Foursquare API to explore neighborhoods in Edmonton city. I will also use the explore function to get the most common venue categories in each neighborhood, and then use this feature to group the neighborhoods into clusters. I will use the k-means clustering algorithm to complete this task. Finally, I will use the Folium library to visualize the neighborhoods in Edmonton City and their emerging clusters.

4.	Import libraries
For purpose of data analysis, I will import several libraries to perform the project that includes but not limited to below:
Numpy to handle data in vectorized manner
Pandas for data analysis
Json to handle json files
Nominatim to convert address in latitude and longitude values
Requests to handle requests
Json normalize to tranform JSON file into a pandas dataframe
Matplotlib and associated plotting modules
import k-means from clustering stage
folium as map rendering library

5.	Data collection
For the purpose of required data of location, Neighborhood, ward, household, particular community information, I will get grab the data from “2016 Census - Dwelling Unit by Language (Neighborhood/Ward)” with html address https://data.edmonton.ca/Census/2016-Census-Dwelling-Unit-by-Language-Neighbourhoo/jsc3-gmwb data provided by City of Edmonton and API Endpoint https://data.edmonton.ca/resource/jsc3-gmwb.json. I will select Indian community information from this data. 
I will get geographical location information from City of Edmonton - Neighborhoods (Centroid Point), data provided by City of Edmonton and add latitude and longitude information based on that information.

6.	Download and explore dataset
Download data files as json files and or csv files and merge files together to create a data frame we were looking for with information of ward numbers, neighborhoods, latitude and longitude of location and community within each location. Transform the data into a pandas data frame. Create a map of Edmonton with neighborhoods superimposed on top.

7.	Segmenting and clustering neighborhoods in Edmonton city.

8.	Exploring neighborhoods.
Explore the neighborhoods that has highest number of Indian communities. Get latitude and longitude of the neighborhoods and explore top venues falls within that neighborhoods.

9.	Analyze each neighborhood.
Get neighborhoods info with top venues information.

10.	Cluster neighborhoods.
Run k-means to cluster the neighborhood
Analyze top venues for each neighborhood.
Visualize clusters

11.	Examine clusters
Examine each cluster and determine the discriminating venue categories that distinguish each cluster




 








 
