# PyBer_Analysis
# Overview
The purpose of this exercise is to perform an exploratory analysis on the rideshare data provided to showcase relationships between city type, number of drivers and riders, and total fares. This will assist PyBer in improving access and determining affordability for underserved neighborhoods.
## Analysis Results
Based on the completed analysis, urban cities appear to utilize rideshare services substantially more often than suburban or rural communities. With the total number of drivers versus rides being higher in urban cities, the average fare per ride and average fare per driver is much lower in accordance with laws of supply and demand. The opposite is true in rural communities where the total number of drivers is lower than the total number of rides and thus the average fares for both rides and drivers is higher. Suburban communities fall somewhat in the middle with the ratio of rides to drivers being the closest to 1:1. Despite this, the average fare per driver is more than double that of drivers in urban cities.
	|Total Rides|	Total Drivers|	Total Fares|	Average Fare per Ride|	Average Fare per Driver|
  |-----------|:-------------|:------------|:----------------------|:------------------------|
|Rural|	125|	78|	$4,327.93|	$34.62|	$55.49|
|Suburban|	625|	490|	$19,356.33|	$30.97|	$39.50|
|Urban|	1625|	2405|	$39,854.38|	$24.53|	$16.57|

## Final Summary
With the largest disparities being seen in urban and rural cities, it could be surmised that the rural communities are being underserved and thus rideshare services are more costly and unaffordable. In urban cities, there is a surplus of drivers to rides needed, suggesting that the rideshare market is somewhat oversaturated in urban cities. 

![FinalSummary](https://github.com/agordon16/PyBer_Analysis/blob/5c46b3495b67d570937fac252b71fb860ca5e7f6/analysis/PyBer_fare_summary.png)

### Recommendations:
  1.	Redistribute drivers from urban cities to suburban and rural communities to balance out the ratio of rides to drivers.
  2.	Average out the total cost per ride to more evenly distribute the cost of rides to make rideshare services more affordable, particularly to currently underserved communities.
  3.	Average out the total fare per driver to encourage flexibility and coverage of all city types.
