# **King County House Pricing Analysis - README**
<img src="./images/housing.jpg" alt="Drawing" style="width: 900px;height:300px;float: left;"/>

### Project Overview

This project aims to assist a real estate agency in providing valuable advice to homeowners regarding the potential impact of home renovations on the estimated value of their properties. Homeowners often seek guidance on which renovations are likely to yield the highest returns on investment when selling their homes. By analyzing historical real estate data and employing predictive modeling techniques, this project aims to provide data-driven insights to address this business problem.


### Business Problem:

The real estate agency faces a significant challenge in assisting homeowners with optimizing the value of their properties through strategic renovations. Homeowners often consider making improvements to their homes before selling them, but they lack data-driven insights on which renovations will yield the highest return on investment (ROI) and by how much. This problem affects both homeowners who may make costly renovations that don't add value and the agency itself, which may struggle to provide valuable guidance to clients.

### The Data

This project uses the King County House Sales dataset, which can be found in  `kc_house_data.csv` in the data folder in this assignment's GitHub repository. The description of the column names can be found in `column_names.md` in the same folder. As with most real world data sets, the column names are not perfectly described, so you'll have to do some research or use your best judgment if you have questions about what the data means.

It is up to you to decide what data from this dataset to use and how to use it. If you are feeling overwhelmed or behind, we recommend you **ignore** some or all of the following features:

* `date`
* `view`
* `sqft_above`
* `sqft_basement`
* `yr_renovated`
* `zipcode`
* `lat`
* `long`
* `sqft_living15`
* `sqft_lot15`


### Project Objective

#### Develop a pricing model:
The model should incorporate the factors such as living room square feet, number of bathrooms/bedrooms, grade ratings. This should help the agency to accurately price their properties.
Evaluate the model's performance using appropriate regression metrics.

#### Improve marketing strategies:
For example, the house sale agency can develop focused marketing initiatives highlighting the key factors influencing price, such as the quantity of bathrooms, living space, and condition and grade rate.

#### Assist Homebuyers in Making Informed Decisions:
Empower homebuyers with accurate price estimates so they can make informed decisions and negotiate effectively.

#### Identify Key Features
Determine house which features have the most significant impact on house prices.
Explore correlations and relationships between different features and the target variable (price).



#### Data Exploration & Understanding:
Import relevant libraries
Load the data 
Data Cleaning and analyzing the dataset to identify trends and correlations between renovations and property prices. Create visualizations to present insights effectively.

#### Data Modelling
The baseline model, utilizing a bivariant analysis, established the initial understanding of the relationship between the square footage of living space and Bathroom.

In the second model simple linear regression was introduced which certainly improved from the baseline model.  The R2 is at 45%.

The final model, a multilinear regression, incorporated additional features to improve the predictive power. Evaluation metrics such as R-squared and F-statistic were used to assess the model's performance and significance. The model R2 is 61% and has a Mae of 119,189.00


### Conclusion
The final model - Multilinear Regression Model - identifies key factors influencing house prices and explains 61% of the price variations.

Important factors affecting house prices include living room square footage, number of bedrooms, bathrooms,floors and property grade.



#### Recommendations
Focus on key features analyzed when setting house prices i.e  square footage, bathroom renovations, property maintenance, and modernization.

Consider Multi-Story Design: explore the possibility of adding additional floors or converting existing space into additional stories.

Consider each property's unique characteristics and consult with real estate professionals for personalized advice based on local market dynamics.

See the full analysis in the [Jupyter Notebook](https://github.com/Lngige01/PHASE2_-GROUP-3_PROJECT/blob/main/Project_Phase2.ipynb) or review this [presentation](https://github.com/Lngige01/PHASE2_-GROUP-3_PROJECT/blob/main/Phase%202%20Project%20Presentation.pdf).



