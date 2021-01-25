# MechaCar_Statistical_Analysis

The goal of this project is to perform a statistical analysis of the MechaCar dataset using multiple linear regression.
In this way we will be able to identify the variables in the dataset that predict the mpg of the MechaCar prototypes.

- The study will be performed using linear regression analysis to identify which variables in the dataset predict the mpg of the MechaCar prototypes.
- Perform t-tests to determine if production batches are statistically different from the mean population.
- Perform a statistical analysis to compare the vehicle performance of MechaCar vehicles with vehicles from other manufacturers.

## Delivery 1 (Linear regression)

Intercept, vehicle_length, and ground_clearance show a significant variation from the mpg values in the dataset.
the slope is not considered zero. Since the null hypothesis H0 is rejected.
The null hypothesis is rejected due to 3 variables (ntercept, vehicle_length and ground_clearance) showing a variance of significance.
such analysis suggests that there may be variables that have not been calculated by our analysis, which should be analyzed.
![alt text](https://github.com/valeria100719/MechaCar_Statistical_Analysis/blob/main/linearRegression.png?raw=true)
![alt text](https://github.com/valeria100719/MechaCar_Statistical_Analysis/blob/main/linearRsummary.png?raw=true)


## Delivery 2 (Suspension coil)

The analisys was done considering all the lots togheter and separate.

In the fist study the data suggests that the manufacturing meets the design specifications for PSI, instead if we divided the analysis for lot #, we can see that the PSI value of the lot 3 is higher than the design specifications.

![alt text](https://github.com/valeria100719/MechaCar_Statistical_Analysis/blob/main/m.m.v..png?raw=true)
![alt text](https://github.com/valeria100719/MechaCar_Statistical_Analysis/blob/main/lotsummary.png?raw=true)


## Delivery 3 (T-Test)

Since in our previous analysis we found that lot 3 is outside the limitations of the design specification.
We decided to carry out a 3 T-Test, one for each specific lot #.
Again, our study that lot1 and lot2 are within the allowed limits, while lot3 is out of range.

![alt text](https://github.com/valeria100719/MechaCar_Statistical_Analysis/blob/main/lotttest1.png?raw=true)

![alt text](https://github.com/valeria100719/MechaCar_Statistical_Analysis/blob/main/lottest2.png?raw=true)

![alt text](https://github.com/valeria100719/MechaCar_Statistical_Analysis/blob/main/lotttest3.png?raw=true)

# Study Design : MechaCar vs Competition

Our study demonstrates how the data collected for MechaCar shows that there are some key points for mpg: vehicle_length and ground_clearance. Furthermore, our study shows that there are some variables that are not taken into account but which could have a big impact on mpg.

The null hypothesis will be that there is no statistical difference in PSI between the competition and MechaCar. The alternative hypothesis will be that there is a statistical difference in PSI between the competition and MechaCar.

Our study shows that if the analysis is carried out without taking into account the batch #, the data is distorted, and it seems that MechaCar falls within the design limits, but if the study is conducted considering the single batch #, the result changes.

We also performed the t-test on the different lot numbers. This test involves the presence of two separate samples. A sample consisting of PSI data for a cluster of MechaCars. A second sample consisting of engine power data for a grouping of competition cars.
