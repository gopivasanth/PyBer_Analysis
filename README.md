# PyBer_Analysis
---
## Overview of Project
The purpose of this project is to create a report that represents weekly fares across city types using pandas and matplotlib. Using these libraries we can intend to generate a report to explain how the fares differs by city type and shows how this data can then be used by those making the decisions at PyBer.

### Purpose
The purpose of this project is to create a summary DataFrame showing the ride-sharing data by the city type and present a multiple-line graph with the weekly trend of fares for each city type.

## Analysis

The Jupyter Notebook for this project is

[PyBer_Challenge.ipynb](https://github.com/gopivasanth/PyBer_Analysis/blob/c62eca0a5835c5781ce5bb2e6f13923883f9abc2/PyBer_Challenge.ipynb)

## PyBer Analysis Results

### Summary Ride-sharing Data

Below we can see the Ride-sharing DataFrame:

![Summary_DataFrame.PNG](https://github.com/gopivasanth/PyBer_Analysis/blob/88f0217863ea20eb80e64f9e1d5a356458069e7f/analysis/PyBer_Summary.png)

1. Rural Cities
- the rural cities have the lowest number of rides and drivers
- hence the average fare per ride and average driver wage being the highest at $34.62 and $55.49, respectively
- as the total fare for rural cities is the lowest at $4,327.93.

2. Urban Cities
- urban cities have the highest amount of rides and drivers 
- hence the highest total fares at $39,854.38
- hence the lowest avg fare per ride and driver at $24.53 and $16.57, respectively.

Below we can see the summary multiple-line graph showing the weekly fares for each type of city between Jan 2019 to the end of April 2019.

![PyBer_fare_summary.png](https://github.com/gopivasanth/PyBer_Analysis/blob/88f0217863ea20eb80e64f9e1d5a356458069e7f/analysis/PyBer_fare_summary.png)

1. From this graph we observe that the total fares for all three types of cities increased and peaked on the third week of Feb. 
2. After this the total fares for suburban and rural cities decreased and stayed flat through Mar,  while the fares for urban cities oscillated then through April and then flattened and slowly declined
3. During the month of April the suburban and rural cities no longer followed the same pattern where rural cities reached a peak at the begining of the month and then decline in fares there after. Suburban cities on the other hand hit a low during the second week of April, the following weeks however, had a sharp increase in fares.

## PyBer Analysis Summary

Business recommendations addressing any disparities among the city types would include:

1. Create incentives for drivers in suburban and rural cities - With more drivers the average fare per ride may decrease, incentivizing riders to use the service more often; this might prove particularly useful in suburban cities.

2. Conversely, in urban cities there are more drivers than riders. This means that it is possible some drivers may NOT have rides. It may be useful for the company to spend more on advertising or incentives for riders to use the service more.

3. Tracking miles traveled per ride may also prove fruitfull as it is posible that the disparity in average fares are due to distances travelled. Rural cities are more spread out therefore rides may be longer than un urban communities, this may be driving the fares to be higher per ride. 