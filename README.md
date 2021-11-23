# An Analysis of PyBer App Data
Performing analysis on ride-share app data to help V. Isualize improve access to ride-sharing services and determine affordability for underserved neighborhoods.

## Overview of the Project
In this analysis, we helped perform exploratory data analysis for PyBer - a ride-sharing app. We created visualizations to tell a compelling story about the following data: 
1. The relationship between the type of city and the number of drivers 
2. The relationship between the type of city and the number of riders
3. The percentage of total fares by type of city
4. The percentage of total riders by type of city
5. The percentage of total drivers by type of city
6. Total weekly fares by type of city

## Results

![image](https://user-images.githubusercontent.com/92613639/142992456-1491e2df-6e6c-460b-8a86-761cc7dadce4.png)

1. Rural cities have fewer drivers and total rides as compared to suburban and urban cities.
    - Based on the above summary DataFrame, we'll notice that the total number of rides in the rural cities is about 13 and 5 times lower than urban and suburban cities, respectively.
    - The total number of drivers in rural cities is 31.8 to 6.3 times less than in urban and suburban cities, respectively. 
2. Rides is rural cities are more expensive for the rider and even more profitable for the driver, per ride.
    - The average fare per ride a rider pays in the rural cities is $10 and $4 higher that urban and suburban cities, respectively.
    - The average fare drivers earn in rural cities is 3.3 to 1.4 times more per ride than in urban and suburban cities, respectively.
3. The overall volume of rides (based on total fares) in urban cities is 2 to over 9 times greater than is suburban and rual cities, respectively.

![PyBer_fare_summary](https://user-images.githubusercontent.com/92613639/142994659-2dab5f3f-c3d9-41fa-b261-f2e4457ef9c3.png)

4. Based on the above chart, for dates between 01/01/2019 and 04/28/2019, the fluctuations in fare were fairly consistent regardless of city type (e.g. all lines spike around the end of February).
5. All of the lines, though they fluctuate, never cross and maintain a somewhat stable fare across the shown time.

## Summary
Based of the results presented above, please see the following business recommendations to the CEO for addressing disparities among different types of cities.
1. The three city types presented in this analysis appear to be essentially individual markets. Urban cities clearly have more people, and therefore higher supply and demand of riders and drivers; whereas rural cities have fewer people, and therefore lower supply and demand, also resulting in higher costs for riders as well as higher pay per ride for the drivers. Based on this, you should treat the 3 city types as seperate markets and may need to come up with unique strategies for each - solutions may not be one-size-fits-all.
2. To understand why there are fewer rides in rural cities as compared to urban and suburban cities, we may need to collect further data. Is is due to the price per ride? Wait times for the next driver due to fewer drivers servicing those areas? Or is it something this study doesn't look at, such as cars owned per capita is higher in rural areas, therefore, they require fewer rides? By understanding what the motivation, or lack there of, is for using PyBer, you will be able to better understand how to come up with a solutions to increase rides in certain cities, resulting in increased profit for the company.
3. It appears as though PyBer is in some way subsidizing rides in rural cities for riders, while overcompensating the drivers for the same. This is probably PyBer's way of incentivizing drivers to frequent rural cities, while attempting to keep prices comparable for riders regardless of what city type they are in so there is no major sticker shock. Based on my point above, cost may not be the only reason for fewer drivers and riders - there may be some other reason that is yet to be uncovered. Only when that is done will PyBer be able to properly incentivize both parties to partake in PyBer's offerings (e.g. base salary for drivers).  
