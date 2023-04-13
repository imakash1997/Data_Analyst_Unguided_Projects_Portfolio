
# <span style="color:#0e86db;">CASE STUDY-RETAIL WALMART STORE SALES PREDICTION FORECASTING</span>

## Business Context: 
The objective is predicting store sales using historical markdown data. One challenge of modelling retail data is the need to make decisions based on limited history. If Christmas comes but once a year, so does the chance to see how strategic decisions impacted the bottom line

# Project Structure
The project is organized into two main directories:

- ## Notebook
This directory contains the Jupyter Notebook file that contains all the code used for data analysis. The Notebook is named Soccer Game Analysis.ipynb and is located in the Notebook directory.

- ## Data Availability & Business Problem
You are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments, and you are tasked with predicting the department-wide sales for each store. In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modelling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.
- <b>stores.csv:</b> This file contains anonymized information about the 45 stores, indicating the type and size of store.
- <b>train.csv:</b> This is the historical training data, which covers to 2010-02-05 to 2012-11- 1. Within this file you will find the following fields:
  - Store - the store number 
  - Dept - the department number 
  - Date - the week 
  - Weekly Sales - sales for the given department in the given store 
  - Is Holiday - whether the week is a special holiday week
  
- <b>test.csv:</b> This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file. 
- <b>features.csv:</b> This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:
  - Store - the store number 
  - Date - the week 
  - Temperature - average temperature in the region 
  - Fuel Price - cost of fuel in the region 
  - MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. Mark Down data is only available after Nov 2011, and is not available for       all stores all the time. Any missing value is marked with an NA.
  - CPI - the consumer price index 
  - Unemployment - the unemployment rate 
  - Is Holiday - whether the week is a special holiday week

# Getting Started
To run this project, you will need the following:

- Python 3.10.7
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- xgboost
- pickle-mixin
### Installation:

```bash
  !pip install pandas numpy seaborn matplotlib sklearn xgboost pickle-mixin
```
Once you have all the dependencies installed, you can open the Soccer Game Analysis.ipynb file in Jupyter Notebook and run the cells.

# Conclusion
After comparing the accuracy score of the regression models(Decision Tree,Random Forest,XGBoost,Linear Regression)
<b>Decision has highest accuracy score</b>
<h2>Decision tree is winner here!!</h2>



