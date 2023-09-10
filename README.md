# **King County House Pricing Analysis - README**
<img src="https://img.freepik.com/free-photo/finances-elements-wooden-cubes-arrangement_23-2148793814.jpg?w=900&t=st=1694343586~exp=1694344186~hmac=82a6c9d431ab39bc6e2a8c30f8be1a3e51b35676d42ae1a5c9ba374ac1cdd769" alt="Drawing" style="width: 1000px;height:500px;"/>

### Project Overview

This project aims to assist a real estate agency in providing valuable advice to homeowners regarding the potential impact of home renovations on the estimated value of their properties. Homeowners often seek guidance on which renovations are likely to yield the highest returns on investment when selling their homes. By analyzing historical real estate data and employing predictive modeling techniques, this project aims to provide data-driven insights to address this business problem.


### Business Problem:

The real estate agency faces a significant challenge in assisting homeowners with optimizing the value of their properties through strategic renovations. Homeowners often consider making improvements to their homes before selling them, but they lack data-driven insights on which renovations will yield the highest return on investment (ROI) and by how much. This problem affects both homeowners who may make costly renovations that don't add value and the agency itself, which may struggle to provide valuable guidance to clients.

### The Data

This project uses the King County House Sales dataset, found in  `kc_house_data.csv`. The description are discussed below:

 Column Names and Descriptions for King County Data Set
* `id` - Unique identifier for a house
* `date` - Date house was sold
* `price` - Sale price (prediction target)
* `bedrooms` - Number of bedrooms
* `bathrooms` - Number of bathrooms
* `sqft_living` - Square footage of living space in the home
* `sqft_lot` - Square footage of the lot
* `floors` - Number of floors (levels) in house
* `waterfront` - Whether the house is on a waterfront
  * Includes Duwamish, Elliott Bay, Puget Sound, Lake Union, Ship Canal, Lake Washington, Lake Sammamish, other lake, and river/slough waterfronts
* `view` - Quality of view from house
  * Includes views of Mt. Rainier, Olympics, Cascades, Territorial, Seattle Skyline, Puget Sound, Lake Washington, Lake Sammamish, small lake / river / creek, and other
* `condition` - How good the overall condition of the house is. Related to maintenance of house.
  * See the [King County Assessor Website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r) for further explanation of each condition code
* `grade` - Overall grade of the house. Related to the construction and design of the house.
  * See the [King County Assessor Website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r) for further explanation of each building grade code
* `sqft_above` - Square footage of house apart from basement
* `sqft_basement` - Square footage of the basement
* `yr_built` - Year when house was built
* `yr_renovated` - Year when house was renovated
* `zipcode` - ZIP Code used by the United States Postal Service
* `lat` - Latitude coordinate
* `long` - Longitude coordinate
* `sqft_living15` - The square footage of interior housing living space for the nearest 15 neighbors
* `sqft_lot15` - The square footage of the land lots of the nearest 15 neighbors


## Project Objective

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



## Data Exploration & Understanding:
Import relevant libraries
Load the data 
Data Cleaning and analyzing the dataset to identify trends and correlations between renovations and property prices. Create visualizations to present insights effectively.

#### Data Modelling
The baseline model, utilizing a bivariant analysis, established the initial understanding of the relationship between the square footage of living space and Bathroom.

In the second model simple linear regression was introduced which certainly improved from the baseline model.  The R2 is at 45%.

The final model, a multilinear regression, incorporated additional features to improve the predictive power. Evaluation metrics such as R-squared and F-statistic were used to assess the model's performance and significance. The model R2 is 61% and has a Mae of 119,189.00


## Conclusion
The final model - Multilinear Regression Model - identifies key factors influencing house prices and explains 61% of the price variations.

Important factors affecting house prices include living room square footage, number of bedrooms, bathrooms,floors and property grade.



## Recommendations
Focus on key features analyzed when setting house prices i.e  square footage, bathroom renovations, property maintenance, and modernization.

Consider Multi-Story Design: explore the possibility of adding additional floors or converting existing space into additional stories.

Consider each property's unique characteristics and consult with real estate professionals for personalized advice based on local market dynamics.

See the full analysis in the [Jupyter Notebook](https://github.com/Lngige01/PHASE2_-GROUP-3_PROJECT/blob/main/Project_Phase2.ipynb) or review this [Presentation](https://github.com/Lngige01/PHASE2_-GROUP-3_PROJECT/blob/main/Phase%202%20Project%20Presentation.pdf).



