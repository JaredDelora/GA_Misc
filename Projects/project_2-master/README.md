# Project 2 - Ames Housing Data and Kaggle Challenge

# Problem Statement:
## Given the available data (2006-10):
## What factors most affect Property Sale Prices?
## Is it possible to accurately predict Property Sale Prices based on these factors?

### Contents:
- Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Conclusions and Recommendations


### Dictionary defining terms in the DataFrames:

|Feature|Type|Description|
|---|---|---|
|lot_area|float|Property Lot Square Footage|
|overall_qual|int|Property Quality Rating|
|overall_cond|int|Property Condition Rating|
|central_air|boolean|Property as Central Air|
|full_bath|int|Number of Full Bathrooms|
|garage_cars|int|Property Garage Capacity|
|house_age|int|Property Age|
|ms_subclass|int|Propety Type|
|neighborhood|string|Property Neighborhood|
|saleprice|float|Property Saleprice|

### Data:

[Ames Iowa Housing Data](https://www.kaggle.com/c/dsir-420-project-2-regression-challenge/data)

[Data Descriptions](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)


### Conclusions:

**A number of property features were found to strongly correlate with home price:**  
Property Quality  
Full Baths  
Garage Parking Spaces  

**Features that were less correlated to Saleprice, but also used in the model:**  
Lot Area  
Property Condition  
Central AC  
Garage Capacity  
Property Age  
Neighborhood  

**Saleprices as a function of neighborhood was also examined. Not all**
**neighborhoods had a statistical impact on the property saleprice, but**
**a good number of them did.**
**It is recommended that more data on socioeconomic factors as a function**
**of neighborhood be gathered. This should help to better understand why**
**property saleprices only sometimes depend on the neighborhood.**
