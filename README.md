# Linear Regression Project for Predicting HDFC Bank Stock Prices

## Overview
This project utilizes linear regression to predict the stock price of HDFC Bank based on its opening price and the previous day's closing price. The dataset spans from January 1, 2000, to April 30, 2021, comprising 5303 data points.

## Model Performance
- **Regression Score (R-squared):** 0.9991329315822302
- **Mean Absolute Error:** 4.968142797254361

## Insights and Considerations
- **High Regression Score:** The high R-squared value indicates a strong correlation between the input features (opening price, previous closing price) and the predicted stock prices.
- **Historical Trends:** The model captures various market conditions, including significant fluctuations such as those observed during the 2008 financial crisis and the 2019-2020 COVID-19 pandemic.
- **Unpredictable Events:** Certain events, like financial crises or pandemics, can lead to unpredictable stock price movements, causing significant dips that are challenging for the model to forecast accurately.
