# Mecha Car Statistical Analysis

## Summary
In this project, we are comparing how MechaCar performs in a variety of tests against its competition. In the first part of our analysis, we will be testing a linear regression model to see how vehicle length and weight, spoiler angle, ground clearance, and AWD affects its MPG. Our goal is to see how each of the aspects affects the MPG.

In the second test, we will first be checking the statistical differences in the PSI of suspension coils from 3 manufacturing lots. Secondly, we will use a t-test to determine if there are any statistical differences between the three lots.

## Linear Regression
#### Multiple Linear Regression Model
![Linear regression](https://github.com/benlew3/MechaCar_Statistical_Analysis/blob/main/Images/LM-formula.PNG)
#### Multiple Linear Regression Model Summary
![Multiple Regressions](https://github.com/benlew3/MechaCar_Statistical_Analysis/blob/main/Images/summary%20of%20LM.PNG)

In our statistical analysis, we can see that vehicle length and ground clearance show a higher coefficient that can affect MPG on cars based on the p-values. The intercept also indicates that there are values that we did not test that would show a statistical significant that was not a part of this model. 

## Statistics on Suspension Coils
#### PSI Statistical totals
![PSI Statistics](https://github.com/benlew3/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.PNG)<br>
#### PSI Statistics by lots
![PSI stats by lot](https://github.com/benlew3/MechaCar_Statistical_Analysis/blob/main/Images/Lot_Summary.PNG)

In this statistical analysis, we can see that Lot 3 has the highest range of variance, with a PSI over 170. This is shown to exceed the requirement. Lot 1 and 2 show lower variance and would meet the design specifications. With the 3 lots together, we can see that Lot 3 is an outlier on its variance, being that the standard deviation is only at 7.89. 

## T-tests on Suspension Coils
#### T-test All Lots Against PSI
![t test](https://github.com/benlew3/MechaCar_Statistical_Analysis/blob/main/Images/t-test%20comparison.PNG)<br>
Here we can see that the p-value is above .05 which means we cannot conclude that a significant difference exists when reading all three lots together. <br>
![lot 1](https://github.com/benlew3/MechaCar_Statistical_Analysis/blob/main/Images/Lot1.PNG)<br>
For Lot 1, we see that the p-value is 1. This means we cannot conclude that a significant difference exists. <br>
![lot 2](https://github.com/benlew3/MechaCar_Statistical_Analysis/blob/main/Images/Lot%202.PNG)<br>
Lot 2's p-value is at .61, which means we cannot conclude that a significant difference exists. <br>
![lot 3](https://github.com/benlew3/MechaCar_Statistical_Analysis/blob/main/Images/lot%203.PNG)<br>
In Lot 3, the p-value is at .04, which means we can reject the null hypothesis that there's no difference between the means and conclude that a significant difference does exist

## Study Design: MechaCar vs Competition
#### Hypothesis
Null Hypothesis: MechaCars have no difference when compared to cost in comparison to their competition. <be>
Alt. Hypothesis: There is a difference in cost for MechaCars when compared to competition.

#### What tests
By using multiple linear regressions and t-tests, we are able to look at the p-values when comparing MechaCar to its competition. 
On the multiple linear regression, we test the fuel efficiency against various aspects of the car. We check the p-value for significant relevance and to find what aspects are not of significant importance. For the t-tests, we are comparing multiple variables against each other. We are verifying which manufacturing lot works best for our car with the least statistical variance.

#### Required data
Data we need for these tests are as followed: dataset of MechaCars and its competition, fuel efficiency, Horsepower, engine size, and car cost would help to generate a more complete statistical analysis. We would be able to see how the distribution of values would fall and which would fall to a normally distributed values. 
