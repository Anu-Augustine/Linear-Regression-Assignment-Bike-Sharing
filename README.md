
## Linear Regression Assignment - Bike Sharing
This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes

Problem Statement
Bike-sharing systems provide a convenient and sustainable transportation option by allowing individuals to borrow bikes for short-term use. These systems operate through computer-controlled docks, enabling users to rent and return bikes efficiently.

BoomBikes, a prominent bike-sharing service in the United States, has experienced a significant drop in revenue due to the COVID-19 pandemic. To recover from these losses and adapt to the changing market, the company seeks to develop a strategic business plan. This plan aims to address customer needs and optimize operations once the lockdown ends and economic conditions improve.

The primary goal is to analyze and understand the factors influencing the demand for shared bikes.
BoomBikes aims to identify:
Key Variables: Which variables are significant in predicting the demand for shared bikes.

Demand Dynamics: How well those variables describe the bike demands.

By building a robust predictive model using historical data, BoomBikes intends to:

Forecast the demand for shared bikes based on critical variables.
Adjust business strategies to meet customer demand effectively.
Leverage insights to expand into new markets and maximize profits.
This analysis will empower BoomBikes to remain competitive in the post-pandemic era by aligning their services with customer expectations and market dynamics.

## Problem Solving Methodology
-  Understanding
- Gain a thorough understanding of the data dictionary and the domain-specific uses of all columns.
- Data Visualization
- Perform Exploratory Data Analysis (EDA) to understand various variables.
- Check the correlation between the variables.
- Data Preparation
- Create dummy variables for all categorical features.
- Split the data into training and testing sets.
- Perform scaling on the data.
- Data Modeling & Evaluation
- Create a Linear Regression model using a mixed approach (RFE & VIF/p-value).
- Check various assumptions of the model.
- Evaluate the Adjusted R-Square for both training and testing data.
- Report the final model.

## Conclusions:
The model demonstrates a strong fit to the data with an R-squared (R²) of 0.836 on the training data and 0.7965 on the test data. This suggests that approximately 83.6% of the variation in the target variable (count) is explained by the model on the training data, while 79.65% is explained on the test data.
The model’s F-statistic (254.3, p < 0.0001) indicates that the overall regression model is statistically significant, meaning that the predictor variables collectively have a significant effect on predicting the target variable.
Key Predictors and Their Impact:
Positive Impact on Count:
Temperature (temp, coef: 0.5475): The strongest positive predictor. Higher temperatures lead to a significant increase in count.
Year (yr, coef: 0.2327): Count increases as the year progresses, suggesting growth over time.
Winter (coef: 0.1313) and Summer (coef: 0.0882): Both seasons show positive impacts, indicating higher counts in these seasons compared to others.
September (Sep, coef: 0.0995): Shows a positive impact.
Negative Impact on Count:
Light snow/rain (coef: -0.2877): The strongest negative predictor. Adverse weather significantly decreases the count.
Wind speed (coef: -0.1130): Higher wind speeds reduce the count.
Holiday (coef: -0.1062): Lower counts on holidays.
Misty (coef: -0.0802) and Sun (coef: -0.0497): Misty weather and sunlight reduce the count, though less substantially than light snow/rain.


## Technologies Used
Python - version 3.x


## Libraries Used
Pandas
Numpy
Matplotlib
Seaborn
sklearn
statsmodels

## Contact
Created by Anu Augustine
