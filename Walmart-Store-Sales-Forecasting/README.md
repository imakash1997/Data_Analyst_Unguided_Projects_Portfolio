
# CASE STUDY-RETAIL WALMART STORE SALES PREDICTION FORECASTING
This is a data analysis project that focuses on exploring and analyzing the performance of football teams in the English Premier League. The project uses Jupyter notebook with python, sql and libraries matplotlib and seaborn to gain insights from the data

## Business Context: 
The objective is predicting store sales using historical markdown data. One challenge of modelling retail data is the need to make decisions based on limited history. If Christmas comes but once a year, so does the chance to see how strategic decisions impacted the bottom line

# Project Structure
The project is organized into two main directories:

- ## Notebook
This directory contains the Jupyter Notebook file that contains all the code used for data analysis. The Notebook is named Soccer Game Analysis.ipynb and is located in the Notebook directory.

- ## Data Availability & Business Problem
You are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments, and you are tasked with predicting the department-wide sales for each store. In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modelling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.
- stores.csv: This file contains anonymized information about the 45 stores, indicating the type and size of store.
- train.csv: This is the historical training data, which covers to 2010-02-05 to 2012-11- 1. Within this file you will find the following fields:
  - Store - the store number 
  - Dept - the department number 
  - Date - the week 
  - Weekly Sales - sales for the given department in the given store 
  - Is Holiday - whether the week is a special holiday week
 

- ## Data
This directory contains all the data files used in the analysis. The data files are in SQLITE format and are located in the Data directory. The files used are:

database.sqlite: This file contains the Player,Match,League,Country,Team tables.

# Getting Started
To run this project, you will need the following:

- Python 3.x
- Jupyter Notebook
- sqlite3
- pandas
- numpy
- seaborn
- matplotlib
### Installation:

```bash
  !pip install pandas numpy seaborn matplotlib sqlite3
```
Once you have all the dependencies installed, you can open the Soccer Game Analysis.ipynb file in Jupyter Notebook and run the cells.

# Conclusion
This project provides a comprehensive analysis of football teams in the Premier Leagues. It covers various aspects such as team performance, player statistics, and match analysis. The project can be extended to include more data sources and more advanced analysis techniques to gain even more insights into the data.



