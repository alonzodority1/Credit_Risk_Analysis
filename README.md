# Credit_Risk_Analysis


## Overview

 This analysis applies machine learning to evaluate credit card risk. Credit risk, being an inherently unbalanced classification problem, requires employing different techniques to train and evaluate models with unbalanced classes. Here "imbalanced-learn" and "scikit-learn" libraries  are used to build and evaluate models using resampling.


## ROS
Random Over Sampler

### Results
![Alt text](ROS.PNG)

2 Variables provide non-random variance: Vehicle_length & Ground_clearance

The slope is not zero as the co-effiencts that are statistically significant are greater than 0

The model predicts the mpg faily well with an adjusted R sqaured of 68 and a very small P value

## Summary Statistics on Suspension Coils

![Alt text](Total_Summary.PNG)

![Alt text](Lot_Summary.PNG)

Cummulatively the suspension coils meet the deisgn specification of a sub 100 PSI variance however mesuring the lots individually we see that lot 3 does not meet the specification with a variance of 220.

## T-Tests on Suspension Coils

![Alt text](1500_T-test.PNG)

With the very small p-value the sample mean is not significantly different from the population mean of 1500

![Alt text](Lot_1_T-Test.PNG)

With the very small p-value the sample mean is not significantly different from the Lot 1 mean

![Alt text](Lot_2_T-Test.PNG)

With the very small p-value the sample mean is not significantly different from the Lot 2 mean

![Alt text](Lot_3_T-Test.PNG)

With the very small p-value the sample mean is not significantly different from the Lot 3 mean

## Study Design: MechaCar vs Competition

To compare the MechaCar with the competition there are 3 key metrics to compare per class:

Cost
Fuel Efficency (both city & highway)
Safety Rating
Trunk Space

The anaylsis would test cost per manuifacturer as a funcition of: MPG (city & highway), Safty rating  and trunk space

Null Hypothesis: The cost of a car is not related to MPG, Safety rating or Trunk Space
ALternate Hypothesis: The cost of a car is dependat on MPG, Safety Rating and Trunk Space

I would use a multiple linear regression to determine the relationships per manufacturer as there are multiple determinate variables

We would need numnerical data show the cost in $, Fuel Effcency in MPG, Safety Rating 1-5 and Trunck space in cubic inches. 
