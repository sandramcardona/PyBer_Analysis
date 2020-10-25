# PyBer_Analysis

## Background
After finalizing the PyBer Analysis, V. Isualize has asked to create a summary DataFrame of the ride-sharing data by city type using Python and Pandas. Then, using Pandas and Matplotlib, to create a multiple-line graph that shows the total weekly fares for each city type. Finally, to create a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

- Resources: city_data.csv, ride_data.csv, Pandas, Matplotlib, Pyplot and Numpy.

## Results

### Ride-Sharing Summary DataFrame by City Type

Using Python and Pandas the csv files were merged into one file using the common city column that both files shared. Then the analysis was performed by calculating independtly for each city type (rural, urban and suburban)the total number of rides, total number of drivers, and the total fares for each city type. Then using this values the average fare per ride and average fare per driver for each city type was calculated. Finally, this data was added to a new DataFrame to see the results per city type. Lastly the data in the columns were formatted to be better understood. 

![alt text](https://github.com/sandramcardona/PyBer_Analysis/blob/main/Analysis/Summary_DataFrame.png)

### Multiple-Line Graph for Total Weekly Fares for each City Type
Using your Pandas skills and two new functions, pivot() andresample(), a multiple-line graph was created that shows the total fares for each week by city type. The total fares by each week by city type was calculated by first grouping the types and dates and then adding the fares for each of the dates within the city types. The results were then used to create a pivot table with the weeks from 01-01-2019 to 04-28-2019. This data was then organized by week, city type, and total fares for each city type.

![alt text](https://github.com/sandramcardona/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

## Summary

Based on this summary by city we can observe that the urban areas have the highest amount of riders,1625, among the other two cities. Urban cities have 13 times more than rural cities. The total Drivers is also high in urban areas with 2,405 drivers compared to 78 in rural cities and 490 in suburban cities.  The total fares are also high in Urban cities with a total of $39,854. However, the average fare per ride is $10 higher in rural cities than it is in Urban areas and the average fare per driver is three times more in rural cities rather than in urban areas.

Based on the multiple-line graph for total weekly fares for each city type, it can be observed that urban areas is the city with the highest total fares. The plot also shows that towards the end of February there is a spike in usage for all three cities followed by a dip in usage at the beginning of March.

Based on the results,there are three business recommendations to the CEO for addressing any disparities among the city types. The first recommendation will be to look into the rural cities and try to determine the reason why there are not so many riders using the app, whether its related to not enough marketing of the ride-sharing app or maybe not enough cell service reaching certain rural areas that prevent ride-sharing apps to work properly. The second recommendation will be to shift the amount of drivers during low usage times from rural and suburban areas to urban areas high usage times to allow for less waiting time among riders and therefore better reviews that will lead to more riders. The third recommendation will be to limit the amount of drivers in the streets during the low season or low usage times for all cities so there is not an excess of drivers and not enough riders for all of them. This can be done by gathering additional information in the type of riders using the app like geographical areas in the cities where the usage is higher per rider compared to other areas of the city, another will be the time of day the riders are using the ride share app the most so there are a lot more drivers available during those times. 

By concentrating on finding the reason why the rural areas has low riders, shifting drivers from rural and suburban areas to urban areas during busy times and reducing the amount of drivers in the street during low usage periods will allow for an increase in average fare per driver and a better understading of ride-sharing app users. 

