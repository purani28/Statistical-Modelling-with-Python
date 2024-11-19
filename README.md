# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project was to create a regression model to understand how bike availability at stations is related to nearby points of interest (POIs). I also stored the data in an SQLite database to make it easier to explore further.

## Process
Step 1. Collecting Data: First, I gathered bike availability data from the CityBikes API.
Step 2. Getting POI Data: Then, I pulled information on points of interest using the Foursquare and Yelp APIs.
Step 3. Storing Data: I combined all the data and stored it in an SQLite database.
Step 4. Building the Model: After that, I built a regression model to analyze the relationship between bike availability and nearby POIs.
Step 5. Interpreting Results: Finally, I analyzed the results to draw conclusions from the data.

## Results
1. API Comparison: The quality of the data from Yelp and Foursquare varied depending on the city. Yelp had better information on user ratings, which helped create a richer dataset to understand customer preferences comapred to Foursqaure
2. Findings: From the scatterplot, I saw a negative correlation between the number of free bikes at a station and the number of nearby restaurants. This suggests that areas with more dining and entertainment options tend to have fewer bikes available, likely because these areas have higher foot traffic and more demand for bikes.
3. Regression Model: The regression model didn’t explain much of the variation in bike availability, more data is needed to improve the model and make it more accurate.

## Challenges 
1. API Rate Limits: Both Yelp and Foursquare have limits on how many API requests you can make, so I had to carefully manage and slow down the requests to avoid hitting those limits.
2. Data Cleaning: Merging data from different sources (CityBikes, Foursquare, Yelp) was challenging because I had to clean and align the data properly.
3. Interpreting Results: Understanding the results of the regression model was tricky, as I had to consider the significance of each variable and how different POIs affected bike availability.

## Future Goals
1. Expand the Dataset: I plan to include data from more cities, which will help compare bike availability in different regions.
2. Create a Dashboard: I’d like to build an interactive dashboard that shows bike station data and POI information in real time, so users can explore trends and insights for different cities.