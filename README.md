# MechaCar_Statistical_Analysis
## Overview

MechaCars has built 50 prototype cars and tested out their mpgs and suspensions. The company purposely built different variations of the prototype designs to find out the ideal mpg vehicle

Two data sets were reviewed: The MechaCar_mpg.csv and The Suspension_Coil.csv. The first file contains the mpgs of the 50 cars and finding one good prototype. The second file contains a dataset if the suspensions were consistent throughout the different types of prototypes.

## Linear Regression to Predict MPG
<img width="777" alt="Deliverable 1" src="https://user-images.githubusercontent.com/92328984/153311659-cf324b7a-0202-40d6-8bac-e1b4ac82941f.png">
The MechaCar_mpg.csv dataset contains mpg test results for 50 prototype MechaCars. As stated above, the company built various types of prototype. Different metrics, such as vehicle length, vehicle weight, spoiler angle, ground clearance and AWD, were collected for each vehicle and are all considered the independent variables in the datase and the dependable variable is mpg.

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - The variables that provied a non-random amount of variance to the mpg values in the dataset are ground clearance and vehicle length.

- Is the slope of the linear model considered to be zero? Why or why not?
  - The slope of the linear model is not considered to be zero because some of the independent variables were significant to not be a zero. In the image above, the asterisks means that there are significance in p-value.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not? 
  - The linear model effectively predicts the mpg of MechaCar prototypes because there is a 71% of accuracy.

## Summary Statistics on Suspension Coils

In the MechaCar Suspension_Coil.csv dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots. 

<img width="768" alt="Deliverable 2_Lot Summary" src="https://user-images.githubusercontent.com/92328984/153322508-b7138e0a-1299-4c52-8259-df6b16633887.png">
In the above table, a lot summary table was created to show the suspension coil’s PSI continuous variable across all manufacturing lots.
<img width="488" alt="Deliverable 2_Total Summary" src="https://user-images.githubusercontent.com/92328984/153322539-1eafd9ec-761a-4513-bb3e-50ce09b737b0.png">
In the second table, a total summary table was created to show the following PSI metrics for each lot: mean, median, variance, and standard deviation.

-The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  - From looking at the lot summary, the suspensions does not exceed 100 pounds per square inch; only 62.294 PSI is the average variance. However, in lot 3, it exceeded 100 pounds per square inch; therefore, the company should stick with lot 1 and 2.

## T-Tests on Suspension Coils
T-tests were performed to determine if the PSI across all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch. Confidence intervals or p-values can be utilized to determine whether results are statistically significant. Given that the confidence interval is 95%, the significance level is 0.05%. A confidence interval outlines the upper and lower limit for the mean.
