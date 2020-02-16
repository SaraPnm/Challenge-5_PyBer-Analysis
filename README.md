# Challenge 5, PyBer Analysis

## Project Overview
We’ve been asked by a CEO to create an overall snapshot of the ride-sharing data. The CEO would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

The goals of this challenge are to:

1. Use Pandas functions like groupby, pivot, resample, and reset_index on a DataFrame.
2. Use Pandas methods and attributes on a DataFrame or Series.
3. Create a new DataFrame from multiple groupby() Series.
4. Format columns of a DataFrame.
5. Create a multiple-line graph.
6. Annotate and apply styling to the chart.

## Resources
- Data Source: Resources/city_data.csv & Resources/ride_data.csv
- Software: Python 3.6.1, Jupyter Notebook

# Summary
Part 1: The first part of the challenge is to create a summary for the ride-sharing data. 
Table able below shows the total rides, total drivers, and total fares as well as average fare per ride and average fare per drivers for each city type i.e. rural, suburban, and urban. 

![Table%201](analysis/Challenge%205_Summarized%20Data%20Frame.png)

The rural city type has the lowest total ride, total drivers, and total fare, and the urban city type has the highest values for these three parameters. This order goes upside down for the average fare per ride and driver. In other words, the more we get closer to the urban area from the vicinity of cities, i.e. from rural to suburban, and from suburban to urban area, the request for rides gets more, and as a result the total number of drivers serving the riders increases. This leads to a predictable higher total fares. 
Also, according to our data analysis, the more the people request for rides, the less the average fare per ride and driver. In other words, it's more expensive to ride in the rural area compared to suburban and urban area.

Part 2:
Figure below, represents total fare values for each week, over the month Jan to May for each city type. As descried in part 1, urban and rural cities have the highest and lowest total fares over the time, repectively. 
In case of rural cities, the total fare value is pretty consistent over the time varying between $0 to $500, with a maximum of $500 in the first week of April.
In case of suburban cities, the total fare value changes approximately  between $200 to $1500, with a peak on the last week of February.
In  case of urban cities, the total fare value changes between $1200 to $2500, with two peaks, one on last week of February and the onther one on second week of March.

![Figure%201](analysis/Challenge%205_Multi%20Line%20Chart.png)

The summarized data in the table and chart both agree that total fares increases as we get to more urbanized area, i.e. from rural cities to suburban cities to urban cities.
