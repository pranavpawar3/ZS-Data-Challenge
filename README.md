## ZS-Data-Challenge
### Problem Statement

Mekktronix is a global premium electronics manufacturing companies provides electronic devices across globe through their large distributor channel. Recently company is observing lot of fluctuations in their demand forecasting across geographies affecting their revenue. The company has reached out to build a machine learning driven forecasting solution to predict sales accurately. 
### Datasets Description
To test the power of AI/ML, company has provided data sales data at distributor X Week resolution is given in train datset.
Feature Description of training data

    Year: Year

    Month: Month

    Week: Week Number

    Sales: Price in Local Currency (Target Variable)

    Mechant_ID : Distributor ID

    Product_Types: Product category

    County: Country name

The company has also provided holiday and marketing expense dataset. Expense data can be visulaized from promotional_expense.csv and holidays data from holiday.xlxs

Feature Description of hoilday dataset:

    Date: Date in YYYY, MM, DD format

    Country: Country Name

    Holiday: Holiday detail



Feature Description for expense dataset

    Year: year of marketing expense

    Month: Month of marketing expense

    Country: Country

    Product_type: Product ID

    Expense_Price: Expense in local currency

The client has asked for forecast at Country X Product X Month resolution. 
The companies have also provided an additional dataset of estimated expense at country x product_ID resolution for majority of the countries. The summary of expense details is provided in promotional_expense.csv
The final forecast must be provided at monthly resolution for Country X Product level.

## Approach and Techniques
The problem can be approached by using conventional methods of Time-series and as we can see it is a forcasting problem , time series application will be best! You can use ARIMA Time Series Model for forcasting of sales for such kind of datasets.
But in this notebook I have tried to predict sales using Machine Learning Algorithms. I have used random forests regressor algorithm for this purpose. We need to do feature engineering on given datasets to extract promising features for our algorithm. 
 
