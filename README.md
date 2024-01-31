# Predictive Power Comparison between Technology and Healthcare Sectors Over SPY ETF

## Project Overview

This project aims to compare the predictive power of the technology and healthcare sectors in forecasting the daily return of the SPY ETF (Standard & Poor's 500 ETF). The technology sector, represented by AAPL, MSFT, AMZN, and XLK, and the healthcare sector, represented by UNH, JNJ, LLY, and XLV, are analyzed to determine which sector exhibits better predictive capabilities.

### Project Steps:

1. **Sector Representation:**
   - The technology sector is represented by AAPL, MSFT, AMZN, and XLK.
   - The healthcare sector is represented by UNH, JNJ, LLY, and XLV.

2. **Data Collection:**
   - Daily closing prices of the selected stocks and ETFs are downloaded from 2000 to 2023.

3. **Exploratory Data Analysis (EDA):**
   - EDA is performed on the collected data to understand the distribution and trends of the variables.
   - Various visualizations are created to gain insights into the relationships between the variables.

4. **Data Preparation:**
   - The data is prepared for machine learning models by cleaning and preprocessing.

5. **Model Building and Evaluation:**
   - Multiple Linear Regression, Decision Tree, Random Forest, and K-NN models are used to predict the daily return of SPY.
   - Models are trained separately using features from the technology and healthcare sectors.
   - Performance metrics such as MAE, MSE, RMSE, R-squared and MAPE are computed to evaluate the predictive power of each sector.

6. **Performance Comparison:**
   - Results indicate that the technology sector exhibits better predictive power over SPY, with an R-squared value of around 0.7.
   - The healthcare sector performs relatively poorly compared to the technology sector.

7. **Performance Improvement Techniques:**
   - Recursive Feature Elimination (RFE) and Principal Component Analysis (PCA) are deployed to enhance the predictive performance of both sectors.
   - Although there is a slight improvement in performance metrics, the healthcare sector still lags behind the technology sector.

For more details, please refer to the [PDF report].
