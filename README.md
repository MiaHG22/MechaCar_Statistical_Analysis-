# MechaCar_Statistical_Analysis
## Overview
AutosRUs' newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team's progress. AutosRUs' upper management is hoping that the analytics team can perform an analytical review on the production data for insights to help the manufacturing team.

## Results

## linear regression to predict the mpg 

Vehicle length and ground clearance variables repsent non-random amounts of variance as applied to the mpg values.
## Summary statistics on suspension coils
The mean is 1498.98 and the population mean is 1500.

<img width="352" alt="total_summary" src="https://user-images.githubusercontent.com/102785000/180095510-1108c2b2-ebb2-42f4-a4e3-2bc420e9f6d3.png">

The variance in Lot 3 is too high to meet the desgin specifications.
## T-test on suspension coils
Lot 1

<img width="647" alt="t_test_lot1" src="https://user-images.githubusercontent.com/102785000/180095564-953aaf6f-94a7-48f4-9813-1e5650d11a89.png">

Lot 2

<img width="574" alt="t_test_lot2" src="https://user-images.githubusercontent.com/102785000/180095600-26cbe083-e611-45ee-b3a6-4e5cde0aa183.png">

Lot 3

<img width="635" alt="t_test_lot3" src="https://user-images.githubusercontent.com/102785000/180095628-5685f932-baf4-45ca-baa3-5f3d17793428.png">

We can see that the p-value from lot 3 is statistical different from the population mean with a p-value of 0.04 while p-value in lot 1 and lot 3 are 1 and 0.6 respectively.



## Design a study comparing the MechaCar to the competition
In order to stand out from a competitive market, MechaCar needs to compare their cost, fuel effiency, horsepower, safety, etc. We can test on these metrics to see
whether the MechaCar is statistically similar to the competing models. The null hypothesis will be the MechaCar does not vary significantly in these variables compared to the competition, and the alternative hypothesis will be significantly different than the competitors. In order for us to perform these tests, we need the data from the competitors as samples and data from MechaCar to do the comparisons.


