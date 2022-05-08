# surfs_up
Module 9_Advanced Databases (SQLite and Flask)

 
# Overview
The client, Way V, wants to open a surf shop on the island of Oahu. We are carrying out a weather analysis to determine the viability of the business, especially to determine its long-term success year round. A weather database for Hawaii is provided in the SQLite format. The database contains two tables: measuremnts and stations. Measurements holds precipitation and temperature values for dates between January 2010 and August 2018 by station. The stations table holds the 9 station's infrmation such as id, name, latitude, longitude, and elevation.  
To determine the business's viability, the precipitation and temperature data is summarized using the count, mean, standard deviation, minimum, maximum, and 1st, 2nd (or median) and 3rd quartiles.  

# Results
The table below is a summary (count, mean, standard deviation, minimum, maximum, and 1st, 2nd (or median) and 3rd quartiles) of the temperatures recorded over the months of June and December.  
![image1](/Results/TempsCompared.png)  
From the table the three following conclusions and differences can be determined:   
**1.** The average temperature in the month of June is higher than the month of December, but not significantly so.  
**2.** Athough the maximum temperatures are not significantly different over the two months, the minimum temperature reached in December is lower.  
**3.** June's standard deviation is smaller, therefore the temperature values are more closely distributed around the mean in comparison to December.  

# Summary
Another query was performed to determine the precipitation values for June and December. These values are summarized in the table below as well plotted in the graphs below. Overall precipitation was higher over the month od December.  

![image2](/Results/PrcpsComparedPlot.png)  
![image3](/Results/PrcpsCompared.png)  

To examine the minimum, maximum, and average temperatures by station, a query qas performed to obtain the table below with the data for every station.  
![image4](/Results/StationsCompared.png)  

Overall., the results demonstrate that the temperatures of June and December are similar. Overall precipitation is higher during December.
