# PyBer_Analysis


## Project Overview
Module 5 taught us how to plot and visualize data using Pandas and Matplotlib.
The data was collected by V. Isualize, and they have asked us to further analyze the ride-sharing data by city type.
We created a new dataframe summary of ride-sharing data based on city type.
Using Pandas and Matplotlib, we generated a multiple-line graph showing the total weekly fares for each city type.



## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.6.1, junyper notebook

## Results

### What are the differences in data based on City type?


The table below describes the differences in data based on city type.
![Graph](/Resources/Table.PNG)

Total Rides:  The Rural rides were much lower than the Urban rides.  Therefore, there were many more people riding in the Urban centers.
And the Suburban rides were about 5 times higher than the rural rides, but still about 2.5 times lower than the Urban centers.
This is what we would expect given the higher population in the Urban centers.  We could validate the ratio of rides if we had more specific population
date for each city and city type.  

Total Drivers:  To meet the corresponding demand, there were more drivers in the Urban centers than there were in the rural centers.  
Again, the suburban driver count was in between the rural and Urban count.
And important data point to view is the ratio of rides to drivers.  In this analysis, the Rural Total Rides to Total Driver ratio is 1.60.
But the Urban Total Rides to Total Driver ratio is 0.67.  This indicates that there may be an over supply of drivers in the Urban cities, or an
undersupply of drivers in the Rural cities.


Total Fares:
The total fares is higher for the Urban city types and lower for the Rural City types.
And the Suburban total fares is in between the Rural and Urban Total fares. 
This is aligned with the number of total rides for each city type.

![Graph](/analysis/PyBer_fare_summary.png)


Average Fare Per Ride:
The average fare per rider is higher in the Rural area, and lowest in the Urban cities.
the Suburban avg fare per rider is inbetween the Rural and Urban numbers.
This means that the rural rides are either longer than the Urban rides, or that the price per km for the rural rides is more expensive than the urban rides.


Average Fare Per Driver:
The average fare per  driver is significantly lower for the Urban drivers, and highest for the Rural drivers.  
And the average fare per driver for Urban cities is lower than the average fare per ride in Urban cities.
This implies that there may be an oversupply of drivers in the Urban center, and that some drivers earned no fares.


### Summary

Three business Recommendations to the CEO include:

1.  We should study the population of the rural vs urban cities to ensure the ratios of rides to drivers is aligned with the population.
If not, we could then determine where we may want to add, or restrict, the numbers of drivers.

2.  We should confirm that the mileage reimbursement rate is constant between the urban, suburban, and rural cities.  If not, we need to account
for this difference in the average fare per ride and average fare per driver.

3.  We should consider that there may be an oversupply of drivers in the urban cities.  In this regard, we need to study why the average fare per driver
is lower than the average fare per ride in Urban cities.  Even if there were multiple people in the vehicle, the average fare per driver should not be less than the average
fare per ride unless there were drivers who were not working.
