# PyBer_Analysis

## Background
After finalizing the PyBer Analysis, V. Isualize has asked to create a summary DataFrame of the ride-sharing data by city type using Python and Pandas. Then, using Pandas and Matplotlib, to create a multiple-line graph that shows the total weekly fares for each city type. Finally, to create a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results

### Ride-Sharing Summary DataFrame by City Type

Using Python and Pandas the csv files were merged into one file using the common city column that both files shared. Then the analysis was performed by calculating independtly for each city type (rural, urban and suburban)the total number of rides, total number of drivers, and the total fares for each city type. Then using this values the average fare per ride and average fare per driver for each city type was calculated. Finally, this data was added to a new DataFrame to see the results per city type. Lastly the data in the columns were formatted to be better understood. 

![alt text](https://github.com/sandramcardona/PyBer_Analysis/blob/main/Analysis/Summary_DataFrame.png)



### Multiple-Line Graph for Total Weekly Fares for each City Type
Using your Pandas skills and two new functions, pivot() andresample(), a multiple-line graph was created that shows the total fares for each week by city type. The total fares by each week by city type was calculated by first grouping the types and dates and then adding the fares for each of the dates within the city types. The results were then used to create a pivot table with the weeks from 01-01-2019 to 04-28-2019. This data was then organized by week, city type, and total fares for each city type.

![alt text](https://github.com/sandramcardona/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

Deliverable 1: A ride-sharing summary DataFrame by city type
Deliverable 2: A multiple-line chart of total fares for each city type
Deliverable 3: A written report for the PyBer analysis (README.md)


Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

Resources: city_data.csv

✓There is a description of the differences in the ride-sharing data for ALL SIX metrics by city type. ✓There is a statement summarizing THREE business recommendations addressing disparities among the city types.

