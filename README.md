# PyBer Analysis

## Overview of Analysis
The client has requested a ride-sharing summary Data Frame by city type (urban, suburban, rural) and a visual representation of the data by weekly fares. 

### The process
The objective was achieved by determining the total rides, total drivers, and total fares for each city type using 'groupby' with the count and sum functions.

![image](https://user-images.githubusercontent.com/114044192/200151198-b89c5bc2-f24e-4cd0-837d-7cd449f15c55.png)

Next, the average fare by city, per ride and per driver was calculated using the totals found in the first steps. 

![image](https://user-images.githubusercontent.com/114044192/200151368-03982da6-23cf-4494-ba7e-eb9f7705465f.png)

The information was then used to create a summary data frame showing hte information for each city type. 

![image](https://user-images.githubusercontent.com/114044192/200151447-6e064e02-bfd7-493b-b966-5489044877a4.png)

Lastly, a multiple line plot was created to show the total weekly fares by city type by using pivot and resampling to show total fares by week for urban, suburban and rural cities. 

![image](https://user-images.githubusercontent.com/114044192/200151618-a396ba09-855d-44a4-bd98-9b057d3f8a2c.png)

![image](https://user-images.githubusercontent.com/114044192/200151559-ecc5ce79-a5fc-43b2-8c4c-bd17efdb086e.png)

## Results

### Total Data Results
![image](https://user-images.githubusercontent.com/114044192/200151677-25933c4b-f49e-459c-ba8f-f9b554f97ba1.png)

Based on the chart above, the following can be seen:
 - Urban cities have 60% more total rides then suburban cities and a little over 92% more than urban cities. 
 - Rural cities have the highest Average fare per ride and driver while having significantly lower total fares, rides and drivers. 
 - Urban cities have the lowest Average fare per ride and driver while having significantly higher total fares, rides and drivers. 
 - Suburban cities are middle ground
  
It can be inferred that 
    - rural cities are further from destinations and have a lower population and therefore less ride-share users 
    - suburban cities are closer to detinations, but still have a longer total ride than urban and have a middle population (ride-share users) as compared to other city types
    - urban cities have a shorter trip length and a much higher ride-share users (typically a much higher population
    
### Total Fares (by month/week) by City Type
![image](https://user-images.githubusercontent.com/114044192/200152154-119330a6-6d67-4df2-a83b-f28f805c896b.png)

As seen in the above chart, the last half of February has a peak use for all city types. No other direct correlations can be seen through all three city types. 

Of notable mention: 
- Urban shows a sizeable dip every other week beginning in mid February to April. 
- Suburban cities show a more gradual peak an decline cycle over a 2 to 3 week peiod. 
- Rural cities show a more regular pattern of low, high, low, high, low, flat

## Summary
Based on the data obtained and analyzed in this data set, the following recommendations are given:
1. Reduce the number of drivers. 
  - rural drivers average approx 1.7 rides per driver
  - suburban drivers average approx 1.28 rides per driver
  - urban drivers average approx .7 rides per driver
 2. Investigate the ride patterns. They are very cyclical and data could be used to enhance planning and marketing. 
 3. Increase rates for urban cities. 
