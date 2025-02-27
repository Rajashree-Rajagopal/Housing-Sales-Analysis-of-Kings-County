
# House Sales in King County, USA

This project analyzes and predicts housing prices in King County, USA, using various machine learning techniques. The dataset contains house sale prices for King County, including Seattle, for homes sold between May 2014 and May 2015.

## Table of Contents

- [Instructions](#instructions)
- [About the Dataset](#about-the-dataset)
- [Modules](#modules)
  - [Module 1: Importing Data Sets](#module-1-importing-data-sets)
  - [Module 2: Data Wrangling](#module-2-data-wrangling)
  - [Module 3: Exploratory Data Analysis](#module-3-exploratory-data-analysis)
  - [Module 4: Model Development](#module-4-model-development)
  - [Module 5: Model Evaluation and Refinement](#module-5-model-evaluation-and-refinement)

## About 

In this project, as a Data Analyst working at a Real Estate Investment Trust,  would like to start investing in Residential real estate. Task is to  determine the market price of a house given a set of features and analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on.


## About the Dataset

This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. It was taken from [here](https://www.kaggle.com/harlfoxem/housesalesprediction?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-wwwcourseraorg-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDA0101ENSkillsNetwork20235326-2022-01-01). It was also slightly modified for the purposes of this course.

| Variable      | Description                                                                                                 |
| ------------- | ----------------------------------------------------------------------------------------------------------- |
| id            | A notation for a house                                                                                      |
| date          | Date house was sold                                                                                         |
| price         | Price is prediction target                                                                                  |
| bedrooms      | Number of bedrooms                                                                                          |
| bathrooms     | Number of bathrooms                                                                                         |
| sqft_living   | Square footage of the home                                                                                  |
| sqft_lot      | Square footage of the lot                                                                                   |
| floors        | Total floors (levels) in house                                                                              |
| waterfront    | House which has a view to a waterfront                                                                      |
| view          | Has been viewed                                                                                             |
| condition     | How good the condition is overall                                                                           |
| grade         | Overall grade given to the housing unit, based on King County grading system                                |
| sqft_above    | Square footage of house apart from basement                                                                 |
| sqft_basement | Square footage of the basement                                                                              |
| yr_built      | Built Year                                                                                                  |
| yr_renovated  | Year when house was renovated                                                                               |
| zipcode       | Zip code                                                                                                    |
| lat           | Latitude coordinate                                                                                         |
| long          | Longitude coordinate                                                                                        |
| sqft_living15 | Living room area in 2015 (implies some renovations) This might or might not have affected the lot size area |
| sqft_lot15    | Lot size area in 2015 (implies some renovations)                                                            |

## Modules

### Importing Data Sets

This module involves downloading and loading the dataset into a pandas DataFrame.

### Data Wrangling

This module involves cleaning the data, handling missing values, and preparing the data for analysis.

### Exploratory Data Analysis

This module involves exploring the data, visualizing relationships between features, and identifying patterns.

### Model Development

This module involves developing machine learning models to predict house prices using various features.

### Model Evaluation and Refinement

This module involves evaluating the performance of the models and refining them to improve accuracy.