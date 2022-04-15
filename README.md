# PyBer Rideshare Analysis
## Purpose
Analyzation of data is an amazing way to find trends and could make the difference between a thriving company and a struggling one. In this case, we will be evaluating data from Pyber transportation services of different city types, rural, suburban, and urban.  By comparing the results and producing clear, easy to read visualizations we will be able address any major disparities. Ultimately, we will be able to provide sound recommendations with statistical backing in order to improve the business.

## Summary of Analysis Determined by City Type

With a few calculations, we were able to create the following dataframe to compare certain aspects of each city type when it comes to rides and fares.

![Pyber_df](https://user-images.githubusercontent.com/100329223/162628037-ff36ad14-18a2-4a38-8da0-073599b867b1.png)

When it comes to total rides and total drivers, rural areas have the least and urban areas have the most. In rural areas, the number of drivers is less than the number of total rides, and in urban areas there appears to be almost twice as many drivers as there where rides given. In the highly populated urban areas, the total amount of fares is almost 10 times as much as the less populated rural areas. Average fares per ride and per driver decrease as the population increases. From this information we can form a few possible conclusions:
-	Rural drivers have a higher average fare per ride due to higher rates or longer distance traveled during rides. With total drivers less than the number of total rides this means that drivers are doing multiple rides which will raise the average fare per driver.
-	Suburban statistics are comparable to rural data however on a larger scale. Averages fares are less due to possible variable such as rates, distance, and dispersal of rides among total drivers.
-	Unlike the other two areas, Urban total drivers are much greater than the number of total rides. With this information, we can conclude that not all drivers actually gave rides in the given time that is being analyzed. This may have an impact on average fares per driver. Fares per ride are lower possibly due to the same variables previously listed.

The following graph shows the trend of total fares over time for each city type. Urban cities show a higher overall total fare and rural has the lowest, which was established in the previous dataframe. Fares seem fairly consistent within each city type with number of rides starting lowest around the first weeks of January. Rides for all types seemed to have a peak last week of February.  Over the four-month period, urban and suburban cities ended with higher fare totals, and rural areas remained about the same.

![PyBer_fare_summary](https://user-images.githubusercontent.com/100329223/162628069-9fe7c95b-72eb-462a-9422-0a1489296c99.png)

## Recommendations Based on City Type Analysis

After viewing the data and analyzing different aspects of the Pyber rideshare system, there are a couple of conclusions we could reach in addressing any disparities between city types. 
-	The most revenue is present in the urban areas, therefore; this may be the best area to focus on expanding and improving business. With a higher population and need for transportation, the opportunity to excel is present. Assuming there are competitors in the area and the number of drivers is far more than the actual rides that were given, it might be a good idea to market a way to more efficiently utilize those drivers.
-	Rural areas are the lowest of the three for bringing in total revenue, however; to be a well-known service, you should have a presence in as many areas as possible. Total rides given were higher than the number of riders so there may have been situations that a driver was already giving a ride when there was another request or another driver was available but too far away.  Recruiting more drivers may be a wise choice in order to efficiently address the demands when present.
-	Suburban areas are a mix of both small and large city ride statistics so a mixture of both recommendations could improve business. Increasing the drivers and then efficiently using them seems to be a wise business choice. 
-	Although we made a visual representation of total fares for each city type over a four-month period, we aren’t able to without a doubt say there was a time that needed more drivers or provided significantly higher revenue. I would suggest to collect data for a full year and gain the knowledge of seasonal demand to provide a higher level of service to customers.

