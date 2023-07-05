# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project, is to utilize the data we get from Yelp, Foursquare and Citybikes Api [ POI, Location, Rating, Price, bike station] for Toronto city to see if there is any correlation between them, and build a regression model


## Process
- Use API to load the data from Foursquer, Yelp and Citybikes in JSON format 
- Extract the required information and store it in panada DataFrame.
- Convert the categorical variabels to numeric variables.
- Apply numeric value distribution test.
- Apply independence test.
- Expolor the data using matplot and seaborn libraries visualization to see if there is any correlation or pattern.
- ![alt text](https://github.com/withabubaker/Stat_Modelling_Python/blob/main/images/image.png) is the projcet flow structure 

## Results
- Yelp API provides usfeul information like price and rating but it's limited to 500 calls per day.
- On the other hand Foursquare has less information but gives you $200 credit every month.
- I tried to see if there is any correlation between location, category of food, rating and price.
- Based on the R Squared result, seems like there is no correlation between the mentioned features.

## Challenges 
- No enough information in Foursquare
- POI was not categorized properly.
- Yelp API limited to 500 calls per day


## Future Goals
I will try another classification model like KNN.
