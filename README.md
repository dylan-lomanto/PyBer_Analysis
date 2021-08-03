# PyBer_Analysis

### Overview
The clinet, the ridesharing app PyBer, has tasked me with examining ride data from urban, subrurban, and rural cities.  The goal is to determine the diffences in average fares between the city types. I have produced a summary dataframe that displays the total rides, drivers, and fares, as well as the average fare per ride and per driver for all three city types.  Additionally, I divdided the fares into weekly totals for all three city types and plotted them on a multiline plot.

### Results

Urban rides consistently have the highest weekly total fares, followedby suburban and then rural.  This is to be expected as the total number of fares follows the same pattern, as does the total number of drivers.  The percentage difference for each city type is lower for total fares than it is for total rides, however.  This is accounted for by the fact that the average fare per ride and per driver follows a reverse pattern (highest for rural cities and lowest for urban). The lines on the multiline plot never intersect and maintain roughly the same distance from one another, with similar peaks and valleys, for the duraction of the data set. This suggests that total fares for each city type follow the same patterns of growth and loss.

##### City Type Summary Data Frame
![Capture](https://user-images.githubusercontent.com/86164867/128095444-9800b84c-3033-499c-acac-a7c452341557.PNG)


##### Weekly Total Fares by City Type
![total_fare_by_city_type](https://user-images.githubusercontent.com/86164867/128094364-a3efa763-d068-43b4-9157-f849c112fceb.png)

### Summary

##### Recommendation #1
PyBer should increase marketing and the number of drivers in rural cities. Although rural cities only account for 5.3% of total rides, they make up 6.8% of total fares. This is likely due to rural rides being longer and thus more profitable.

##### Recommendation #2
PyBer should pursue more drivers in suburban cities. Suburban cities account for 26.3% of total rides, but only 16.5% of drivers. This shows that there is a demand for PyBer rides in suburban cities that may not be met with the current supply of drivers.

##### Recommendation #3
PyBer should either increase marketing to attract morse riders in urban cities or decrease the number of drivers. Urban city drivers account for 80.9% of total drivers, but only 
68.4% of total rides. 
