# NY-Citibike

## Overview
After a trip to New York City, our friends get inspired to establish a bike-share program in their hometown of Des Moines. To prepare a proposal for a potential angel investor, we have to first figure out how the bike-sharing business works in New York City.

To complete the analysis, we leveraged CitiBike site data and based it on July 2019 trip data. Access the Tableau workbook through the following URL: https://public.tableau.com/app/profile/armine2415/viz/NYCBikeTripAnalysis_16702368914740/NYCBikeTripAnalysis

## Results

#### The Duration of a Typical Ride: Graphs 1 & 2
The very first section of our Tableau story examines the distribution of the rides based on their duration. From the charts below, we can conclude that 5-minute rides are the most frequent, and the overwhelming majority of rides, up to 90 percent, last no longer than 30 minutes.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.38.30%20PM.png" width="700"/></kbd>

#### Chekout Time for Different Groups? Graph 3
In the second section, the user can disaggregate the same plot based on gender, age, and user type to compare the riding patterns of different groups.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.38.50%20PM.png" width="700"/></kbd>

#### Weekly and Daily Patterns of the Number of Rides? Graphs 4 & 5
The heatmaps below allow developing assumptions of the purpose of the ride: are they recreational or business? Also, this information is crucial for operational measures, e.g., what is the most suitable time to repair the bikes.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.39.14%20PM.png" width="700"/></kbd>

#### Trip Geography? Graphs 6 & 7
The next section of Tableau story is devoted to geography. As we can see from the chart below, most rides are taking place in the borough of Manhatten and its adjacent territories. Our purpose is to understand why business works best in certain areas.
It is also worth mentioning that the start and end points of the rides do not differ much. Hence, logistics/redistribution costs are not too high for the business.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.39.33%20PM.png" width="700"/></kbd>

#### Number of Rides per Bike? Graph 8
Not ore bikes are equal either. Some of them are used too often and consequently need repairing more often.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.39.51%20PM.png" width="700"/></kbd>

## Summary

To major conclusions of the analysis are:

1) The typical <b>customer</b> is an adult male who is subcribed tho the service. 
2) The most typical <b>user experience</b> is up to 20 minute ride within the area of Manhatten. 

It would be also useful to add: 
* Big numers (KPIs), e.g. Average frequency of bike usage per customer, Max length of the ride daily, etc.
* Crosstabs for different dimensions such as gender, age and subscription tipe.
