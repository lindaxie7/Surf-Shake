# Surf's Up

## Overview of Project
An investor is interested in build a Surf and Ice Cream shop in Oahu, Hawaii. We are going to analyzing the weather patterns in June and December in Oahu, Hawaii, in detail is to comparison the temperature in the two extreme months(Summer and Winter), to see if Oahu, Hawaii is a place to open a Surf and Ice Cream shop all year around. To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database.


## Results

 Key differences in weather between June and December:
 
- The mean temperature of 75°F for June is higher than the mean temperature of 71°F for December. 
![Untitled3](https://user-images.githubusercontent.com/38533045/137601607-c3fbb2aa-889a-4bf6-bf59-5079ebb64a45.png)



- Grouping the data into 12 bins, the histograms visually show how the frequency centers around the two different means. We can see that the most frequent temperature in June is around 75°F, and the most frequent temperatuer in Dec is between 70°F to 75°F. 
![Untitled26](https://user-images.githubusercontent.com/38533045/137592392-3e183272-99d5-4274-af87-7fde996af814.png)


- From the summary of the data, we can conclude that the temperatures differences are reasonably close between June and December. There is not much temperature jumps all year around and the temperature tend to be between 60°F to 85°F. 

## Summary

We can infer that a vast majority of the observations were over 67 degrees. If you count up the bins to the right of 67 degrees, you will get about 325 days where it was over 67 degrees when the temperature was observed. The data supports opening a Surf and Ice Cream shop year-round.

Two additional queries that you would perform to gather more weather data for June and December:
- We include precipitation into the dataframe column, and to analyze if there is much difference in the precipitation levels between June and December.

- We include station into the datafram column, to see if we have enough data to make the conclusion. 
