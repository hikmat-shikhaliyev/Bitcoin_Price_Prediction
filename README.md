## Cryptocurrency Price Prediction with Random Forest Regression

### Introduction:
Cryptocurrency markets are known for their volatility, making them attractive yet challenging for investors. This Python project aims to predict cryptocurrency prices using machine learning techniques, specifically Random Forest Regression. By analyzing historical price and volume data of major cryptocurrencies, including Bitcoin (BTC), Ethereum (ETH), Tether (USDT), and Binance Coin (BNB), the project seeks to provide insights into potential price trends.

### Project Overview:
The project involves several stages, including data loading, preprocessing, exploratory data analysis, model building, hyperparameter tuning, and analysis of the impact of individual predictor variables on cryptocurrency prices.

### Libraries Used:

Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Matplotlib and Seaborn: For data visualization.
Scikit-learn: For machine learning algorithms and evaluation metrics.
yfinance: For obtaining historical cryptocurrency price data.
Data Loading:
Historical price and volume data for BTC, ETH, USDT, and BNB are retrieved from Yahoo Finance using the yfinance library.

### Data Understanding and Preprocessing:

Basic statistics, data types, and missing values are analyzed.
Multicollinearity among predictor variables is checked using Variance Inflation Factor (VIF).
Outliers are identified and treated using the interquartile range (IQR) method.
Data distribution is visualized through line plots and pair plots.
### Model Building and Evaluation:

The dataset is split into training and testing sets.
A base Random Forest Regressor model is built and evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.
Hyperparameter tuning is performed using randomized search cross-validation to optimize model performance.
The impact of individual predictor variables on cryptocurrency prices is analyzed through univariate analysis.
### Conclusion:
Through this project, we aim to provide insights into cryptocurrency price trends and contribute to the understanding of factors influencing cryptocurrency markets. The Random Forest Regression model serves as a valuable tool for predicting cryptocurrency prices, with potential applications in investment decision-making and risk management.
