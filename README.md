# Capstone-Project-Battle-of-Neighborhoods-Madrid
Applied Data Science Capstone final project. Analyzing Madrid's trending venues


# 1. Analytic Approach
Madrid (Spain) is one of the largest cities in Europe with a metropolitan area population of approximately 6.64 million and the municipality covers 604.3 squared kilometers. The city is divided into 21 districts and 132 neighboorhoods in total. 

For this project, we should be able to answer the following question: If someone is looking to open a restaurant in the city, where would we recommend that they could open it? 

To be able to answer that question, the appropriate approach would be to cluster the city by trending places, and analyze each cluster with statistical data.

# 2. Data Requirements
For this project, we will use information provided by Wikipedia in order to retrieve the boroughs and geographical coordinates of each neighboorhood of Madrid. Then, we will access the Foursquare API features to get information of the top venues in the city, and we will do a clustering to find some common patterns. Also, we'll use statistical information about the venues per borough, and using folium and mapplotlib (both map and graph rendering libraries)  to plot the maps for making the information more readable. 

# links:
https://es.wikipedia.org/wiki/Anexo:Distritos_de_Madrid
