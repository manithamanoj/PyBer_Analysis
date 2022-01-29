# PyBer_Analysis
Analyze all the rideshare data

# Introduction
   
  In this challenge we performed an exploratory analysis and
created visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.For exploratory analysis we used our Python skills and knowledge of Pandas, to create a summary DataFrame of the ride-sharing data by city type. Then, by means of Pandas and Matplotlib, we created a multiple-line graph that shows the total weekly fares for each city type.

# Analysis

   Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, got the total number of rides, total number of drivers, and the total fares for each city type. Then, calculated the average fare per ride and average fare per driver for each city type. Finally, added this data to a new DataFrame, then formatted the columns.
   
   <img width="1043" alt="Screen Shot 2022-01-28 at 5 27 41 PM" src="https://user-images.githubusercontent.com/72629108/151638918-1f46c3cc-02c3-4a66-8424-bc5eb6f1a93f.png">


## Results
   
   From the table we understood that Rural areas have the least total rides, total drivers, total fares but have the highest average fare per ride and average fare per driver. But Urban areas have the highest total rides, total drivers, total fares but have the least average fare per ride and average fare per driver.For suburban areas, all the values lies in between rural and urban areas.

   Using your Pandas skills and two new functions, pivot() and resample(), created a multiple-line graph that shows the total fares for each week by city type. Finally using the object-oriented interface method and the df.plot() method, as well as the Matplotlib "fivethirtyeight" graph style we plotted multiple-line chart 
  Code snippet
  
   <img width="1172" alt="Screen Shot 2022-01-28 at 5 25 51 PM" src="https://user-images.githubusercontent.com/72629108/151638848-1eb429c0-7a67-4124-b7e1-ec1cf6229292.png">

  
  ![PyBer_fare_summary](https://user-images.githubusercontent.com/72629108/151638744-edb186b4-9cd1-4217-9d71-dbd83124697e.png)
 

## Results
   
   We can see a hike in the fare for all the three city types during the last week of February.

# Summary

  *  Despite less total rides, total drivers, and total fare the average fare per ride and driver is high in rural areas because the miles travelled is probably more per ride. We don’t have the data to support this assumption. Our suggestion is PyBer should work to include miles travelled per ride data as part of the data collection process.
   
  *   Average fare per driver in urban areas is less so this may lead to driver attrition. Also, in urban areas the total number of rides is less than the number of drivers and the drivers are not getting enough jobs.  So Pyber must think about adopting new strategies like Ads, more offers to customers to increase total number of rides.  
   
  *  The kind of population in each city type also affects the number of rides. So Pyber should consider include those details while collecting data in future for analyzing.



