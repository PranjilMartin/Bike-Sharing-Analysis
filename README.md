# Bike-Sharing-Analysis


## 🗒️ **Problem Statement**

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it v ry difficult to sustain in the current market scenario. So, it has decided to co me up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the ation due to Covid-19. They have planned this to prepare themselves to cater o the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on w hich the demand for these shared bikes depends. Specifically, they want to unders tand the factors affecting the demand for these shared bikes in the American market. The company wants:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## 🎯 Business Goals

The company want to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## ⏳ **DataSet** 

1. Bike Sharing Dataset

2. Assignment - Data Dictionary


## 💻 **Technologies Used**

 - Python - version 3.12.4
 - Matplotlib - version 3.10.0
 - Numpy - version 1.26.4
 - Pandas - version 2.2.3
 - Seaborn - version 0.13.2
 - Statsmodels - version 0.14.4
 - Scikit-Learn - version 1.6.1

## 📃**Approach**

 - Step 1: Import Necessary Libraries
 - Step 2: Load the Data and Understanding the Data
 - Step 3: Data Cleaning and Missing Value Chec
 - Step 4: Segmentation of Columns
 - Step 5: Exploratory Data Analysis
 - Step 6: Data Preparation Steps -- Dummy Variable Creation (One Hot Encoding)
 - Step 7: Train-Test Split
 - Step 8: Feature Scaling (Min-Max Scaling)
 - Step 9: Building the Initial Linear Model (Model 0)
 - Step 10: Feature Selection (Using RFE and Manual Selection Methods)
 - Step 11: Check and Build the Models Using Selected Features
 - Step 12: Residual Analysis of the Train Data
 - Step 13: Making Predictions Using the Final Linear Model
 - Step 14: Steps for Further Model Refinement and Optimization
 - Step 15: Model Evaluation

## 💡 **Conclusion**

The equation of the best fit line is given by:

cnt = 0.1944 + 0.2499 x year - 0.0794 x holiday + 0.4242 x Temperature - 0.1367 x spring + 0.1026 x winter - 0.0667 x december + 0.0433 x may - 0.0849 x november + 0.0648 x september - 0.0374 x Tuesday - 0.0831 x cloudy - 0.2716 x light_rain

- Analysis is been done both recursive feature elimination and Mannual elimination
- 20 features has been selected using recursive feature elimination algorithium
- The bike demand is influenced by the feature year, holiday , temperature , spring, winter, light_rain
- In final Model we have seen 84% of variability in training data and 79% of variability in testing data


