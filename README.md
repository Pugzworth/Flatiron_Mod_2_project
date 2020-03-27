# Module 2 Modeling Project

### Repository
* Readme
- The readme file contains a brief explanation of our project goals, findings, metrics used, a comparison of our final model versus our baseline, and our recommendations. 
* Project_2_Modeling_Tim_Notebook
- Tim's jupyter notebook. It runs through his entire modeling process with explanations for each step.
* (Lenaya's Notebook)
-
* (Jesus' Notebook)
-
* kc_house_data.csv
- The csv file containing the data that we used for the project.

### Project Goals
* The goal of our project was to take data for sales of homes in King County, Washington and determine which features of home sales best predict the sales price. Our goal was to run a multivariate linear regression to determine which factors from our dataset influenced the sales price of houses the most in order to make a business based recommendation on how to build homes in order to increase profitability.

### Findings
* 

### Error Metrics
* Our main error metric was Mean Absolute Error. We also routinely used r^2, the coefficient of determination, in our notebooks, but we decided to use Mean Absolute Error as our primary metric. 
  The Mean Absolute Error is the average of the absolute differences between the predicted and actual values. We used this metric because we felt it was the most easily explainable to an audience without a statistics background. We also used it over the coefficient of determination because it is better at detecting bias in the data. 

### Final Model vs Baseline
*

### Recommendations
* Get information on the costs associated with each feature in order to better determine profitability. With square footage being the biggest factor in how much a house is sold for, this is less significant if the price of building a bigger home increases more than the sale price. This also follows for the cost of each feature of the house. For example, keeping house square footage constant, how much extra does it cost to build an extra bathroom instead of having a larger living room or kitchen?
* It would also be useful to use a model were we could link latitude and longitude. While this is possible using a GAM model with tensoring, we were unable to understand how to implement the model sufficiently to be used. This relational approach could be investigated with other features as well. For example, is adding on another bathroom more or less significant when the bathroom is paired with another bedroom?
* Obtaining more data would also be useful. Our data set stops at 2015 and it would probably be useful to have data closer to the present.