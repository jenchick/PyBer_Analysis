# PyBer_Analysis
## Overview 
PyBer, a ride-sharing service, has requested an analysis of their data to determine if there are disparities in program usage, specifically in underserved neighborhoods. 
Two data files were provided:
- City data: contains city, number of drivers, and type of city (Urban, Suburban, Rural)
- Ride details: contains city, date of ride, cost of fare, and ride identification number

The data files were (left) joined to capture a full picture of the ride share details.  Visualizations, using Matplotlib, were created to provide a graphic depiction of the data.

## Results 
### Ride Sharing Data by City Type
Three city types were analyzed to determine ride-share use.  The chart below indicates that the ride-share program is utilized most in Urban areas.  In a four month time period, there were 1,000 more Urban rides than Suburban rides and 1,500 more than Rural rides.  In addition, Urban drivers make up 80.9% of the total driver population.  

![image](https://user-images.githubusercontent.com/102322707/170837066-e23ae22b-3de8-4f40-b30b-44a9f9940e25.png) ![image](https://user-images.githubusercontent.com/102322707/170837146-4242cff9-524b-4585-a706-0150b19ec37d.png)

Surprisingly, Rural drivers have the highest average fare per ride ($34.62) and average fare per driver ($55.49). Supply and demand is most likely a culprit in the disparities between cities, drivers, and fares.

![image](https://user-images.githubusercontent.com/102322707/170836818-10ad2e4f-6988-42ed-bfba-c9e8bed31006.png)

The following chart shows Total Fare by City Type, indicating that although Rural drivers are making more money per fare, they are not catching enough rides and thus, their income is very low in comparison.

![image](https://user-images.githubusercontent.com/102322707/170837489-c00bc6ee-20d0-465c-982b-ee69a49ad08d.png)

## Summary 
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.
- Business Reason 1
- Business Reason 2
- Business Reason 3

## Resources
Data Sources: city_data.csv, ride_data.csv

Software: jupyter notebook, Python 3.7 (64-bit), pandas, matplotlib
