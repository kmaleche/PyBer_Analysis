# PyBer Analysis

## Overview

### Purpose
This project is an exploratory analysis of PyBer side-sharing data from various cities, with the intent of unveiling trends across city types that will make the app more accessible and affordable to its users. 

### Resources
The two datasets utilized consist of PyBer ride, driver, city, and fare figures for the year 2019.

## Results
<img width="651" alt="City_Type_Summary" src="https://user-images.githubusercontent.com/82285562/119397237-71323280-bc9b-11eb-8105-3ae2a31fd8ef.png">

We found a few key trends when parsing the ride-share data. 

- First, as may be expected, there are more drivers in Urban cities than are in Suburban cities, and fewer still in Rural cities. 

- Additionally, there are more rides taken in Urban cities than Suburban, and the fewest rides taken are in Rural cities.

This supply-demand relationship is reflected in the average fares per ride and per driver for each city.

<img width="968" alt="Ride-Sharing-Bubble-plot" src="https://user-images.githubusercontent.com/82285562/119397440-b9515500-bc9b-11eb-8e42-06d5966997af.png">
By plotting the same data in the bubble chart above, we see the relationship between these measures more clearly:
  
  - As the total number of rides in a city increases, the average fare decreases.
 
  - Similarly, as the total number of drivers in a city increases, the average fare also decreases.
  
  - And finally, as the total number of rides in a city increases, the driver count also increases.

![PyBer_Fare_Summary](https://user-images.githubusercontent.com/82285562/119396272-44c9e680-bc9a-11eb-9d6d-3b23dbeea92c.png)
Looking at fare by month for each city type, we see that there is an uptick in fares across all city types in the month of February. Additionally, we see that Urban cities have the most fluctuation in total fare by week, while Rural cities remain more consistent.

## Summary

In summary, there are key distinctions between the city types when it comes to driver count and average fare. Most notably, due to the relationship between driver count, ride count, and average fare, Rural cities have the highest fares in comparison to their Suburban and Urban counterparts. 

### Recommendations
It is our recommendation that PyBer considers affordability for its users in Rural areas, especially since the nature of their environment also implies that the trips they take would be a greater distance, and thus even higher in cost, with fares being the highest in these cities. 
