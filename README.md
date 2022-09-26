# Pyber Analysis
click on link to view analyzing and visualizing ridesharing data with Python : [Pyber Ridesharing Analysis](https://github.com/miralchangela/Pyber_Analysis/blob/main/PyBer_Challenge.ipynb)

## Overview of the analysis:

The purpose of analysis is to perform an exploratory analysis on Pyber dataset. Matplotlib library used for  several types of visualisation which is used to tell a compelling story of data.Jupiter Notebook and matplotlib are used to create a variety of charts that shows the relationship between city type , fare and number of drivers. Using visualisation of pyber rideshare data to improve the ride sharing services.

## Technical Analysis:
To obtain the required data frame used for line chart , the following task was performed:
1. Merge method used for to merge to datasets.
3. using groupby function we were obtained the Total rides , Total drivers , Total fares , Average fare per driver and Average fare per ride.
4. After obtained all the required data , we could create a new data frame for them. It’s image shows below :

![pyber_summary_df](https://github.com/miralchangela/Pyber_Analysis/blob/main/analysis/pyber_summary_df.png)

5. In the preceding image , we can see that its formatting doesn’t look proper.Map(.format) function used to format a dataset.

![pyber_summary_formatted_df](https://github.com/miralchangela/Pyber_Analysis/blob/main/analysis/pyber_summary_formatted_df.png)

6. Index was set to date time using the date time index function.
7. Using info function , the index of the new data frame was checked.
8. A pivot table created by the pivot function. 
9. Loc function used to organise the pivot table within given date range.
10. Resample function used to resample the pivot table.

## Results:
![pyber_summary_formatted_df](https://github.com/miralchangela/Pyber_Analysis/blob/main/analysis/pyber_summary_formatted_df.png)

As shown in preceding dataframe, the rural cities had the highest average fare per driver while the urban cities had the lowest average fare per driver. The high fare observed in rural cities due to the less number of total rides and total drivers.


![pyber_fare_summary](https://github.com/miralchangela/Pyber_Analysis/blob/main/analysis/PyBer_fare_summary.png)

As shown in multiple line chart above , the urban cities had the highest total fare within january to april where rural cities had the lowest total fare.On other hand , NaN value observed in rural cities after arranging the data into the specified date range using loc function. In addition , available data is limited to 2019 , the urban cities might also benifit from more ride allocation and this will help to meet the demands for rides in those month , increase revenue and profit.

## Summary:

Based on the analysis my business recommendations to Pyber are: 

1) Increasing the numbers of drivers in Rural areas to ensure there are enough drivers to meet ride demand. 

2) It seems like the Rural cities are underserved, but it would be neccesary to perform a market study to confirm if there is enough demand in this market segment to justify investing in hiring more drivers.
