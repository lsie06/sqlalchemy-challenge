# sqlalchemy-challenge

Challenge Instructions
For this exercise you are going on a long holiday vacation in Honolulu, Hawaii. To help with your trip planning, you decide to do a climate analysis about the area. 

**Method**

For the analysis I found the most recent day in the data set provided to get the previous twelve months of the precipitation by doing a query. Selecting the date and prcp values I loaded the query results into a Pandas Data Frame and set an index to a date column, then sorted the values by date and created a plot. 

**Station Analysis**
Design a query to calculate the total number of stations in the dataset.
Design a query to find the most-active stations (that is, the stations that have the most rows). To do so, complete the following steps:
List the stations and observation counts in descending order.
Answer the following question: which station id has the greatest number of observations?
  The station id that has the greatest number of observations is USC00519281 with 2772 observations. 

After the analysis the following was determined that the lowest temperature is around 54.0 and the highest is arpund 85.0 for an average of 71.7. 
