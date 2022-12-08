# NY-Citibike

## Overview

After a trip to New York City our friends get inspired to establish bike-share program in their hometown of Des Moines. In order to prepare a proposal for a potential angel investor, now our aim is to figure out how bikesharing business actually works in New York City.

To complete the analysis we leveraged [CitiBike](https://ride.citibikenyc.com/system-data) site data and based our analysis on July 2028 trips.

Accessed Tableau workbook through the following URL: https://public.tableau.com/app/profile/armine2415/viz/NYCBikeTripAnalysis_16702368914740/NYCBikeTripAnalysis

## Results

#### The Duration of a Typical Ride: Graph 1 & 2
The very first section of our Tableau story examines the distribution of the rides based on their duration. From the charts bellow we can canclude that 5-minute rides are the most frequent and the overwhelming majority of rides, up to 90 percent last no langer than 30 minutes.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.38.30%20PM.png" width="700"/></kbd>

#### Chekout Time for Different Groups? Graph 3
In the second section the user can disaggregate the same plot based on gender, age and user tipe to compare riding patterns of different groups. 

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.38.50%20PM.png" width="700"/></kbd>

#### Weekly and Daily Patterns of the Number of Rides? Graph 4 & 5
Not all days and hours are equal. The visuals bellow allow developing assumptions of the purpose of the ride: are they recreational or business. Also this information is crucial for operational planning of the business, e.g. what is the most suitible time to repaire the bikes.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.39.14%20PM.png" width="700"/></kbd>

#### Trip Geography? Graph 6 & 7
The next section of Tableau story is devoted to the geography. As we can see from the chart below the most rides are concentrated in Manhatten and adjucent territories. Our purpose is to nderstand why business works best in certain areas.

It is also worth mentioning that the start and end points of rides are not differ much. Hence, logistics/redistribution costs are supposed not to be too high for the business.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.39.33%20PM.png" width="700"/></kbd>

#### Number of Rides per Bike? Graph 8
Not ore bike are equal either, some of them are used too often and consequently need being repaired more often.

<kbd><img src="https://github.com/ArmineKhanan/NY-Citibike/blob/main/graph_images/Screen%20Shot%202022-12-05%20at%2010.39.51%20PM.png" width="700"/></kbd>

## Summary

To major conclusions of the analysis are:

1) The typical <b>customer</b> is an adult male who is subcribed tho the service. 
2) The most typical <b>user experience</b> is up to 20 minute ride within the area of Manhatten. 

It would be also useful to add: 
* Big numers (KPIs), e.g. Average frequency of bike usage per customer, Max length of the ride daily, etc.
* Crosstabs for different dimensions such as gender, age and subscription tipe.
