# macro_trends
Objective: 
As a data analyst, I want to be able to extract stock market information and plot against macro economic indicators to find correlation and relationships. Further analysis is possible using the dataframe created

# Requirements
* Get API key from https://www.alphavantage.co/support/#api-key
* Get ticker symbol of your favourite stock
* Get list of macro indicators from https://fred.stlouisfed.org/

Currently the script is leverage pandas data reader to extract data from FRED. AlphaVantage is also possible, see more linked here: https://pandas-datareader.readthedocs.io/en/latest/index.html

# Outputs
* A table with stock ticker and appended with the macro indicators
* Simple correlation heatmap and line chart