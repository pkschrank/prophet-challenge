# prophet-challenge

# Prophet Challenge - MercadoLibre

In this challenge we are tasked with analyzing search data from google with stock prices for MercadoLibre.

## Workflow

- Assess the google search trends
    1. Group data by hour week and month
    2. View specified time frame data
    3. Provide line charts plotting the data for each grouping
- Assess the stock closing price trends.
    1. Clean and plot the dataset
- Merge the DataFrames
    1. Combine the search data with the stock data
    2. View specific time frame of the first half of 2020
    3. Add lagged search data as a new column to the DataFrame
    4. Add calculated volatility of the stock price data to the DataFrame
- Use Prophet to forecast future data
    1. Apply the DataFrame to Prophet using 'fit'
    2. Visualize the data to see the forecasted results
    3. 
