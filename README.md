# Housing-Market-Analysis-A-SAS-Based-Predictive-Study
# Overview
This SAS project is done for the analysis to find which factor plays a major role in affceting the house price &amp; build a model to predict the price. The project follows a complete data analytics pipeline including data cleaning, feature engineering, exploratory data analysis, correlation analysis, and regression modelling.
# Business Problem
The price of the house depends on multiple factors. The main aim is to find the key factor that influences the house price & build a predictive model using SAS.
# Dataset
The study contains two datasets:
* HousePrice.xlsx → contains sale price and transaction details
* Characteristics.xlsx → contains property features such as living area, bedrooms, bathrooms, and garage details
Both datasets contains a common factor that is Reference ID
# Methods
* Importing both the datasets in SAS
* Data cleaning (Missing values, duplicates, Invalid Values)
* Feature Engineering (Garage size, House Age)
* Exploratory data analysis
* Correlation analysis
* Regression modelling using PROC REG
* Model validation
# Key Insights
* Living area is the strongest predictor of the House price
* Bathrooms positively affect the house price
* House age negatively affect the house price
* Bedroom count doesn't affect the house price
# Model Performance
* R² ≈ 0.72
* Model is highly significant (p < 0.0001)
* No serious multicollinearity issues
# Tools & Commands Used
* SAS on demand for acedamics
* PROC IMPORT
* PROC SGPLOT
* PROC CORR
* PROC REG
# Steps  to Run
1. Open SAS Studio (OnDemand for Academics)
2. Upload datasets into the data/ folder
3. Configure the environment
4. Run sas_code/housing_analysis.sas
5. Check outputs in outputs/ folder
# Project Highlights
- Cleaned and prepared housing market data using SAS
- Performed exploratory data analysis (EDA)
- Built a multiple linear regression model for house price prediction
- Evaluated model performance using statistical metrics
- Created visualizations to identify market trends
- Interpreted model results and generated business insights
# Author
**Ashley Ebetha**
