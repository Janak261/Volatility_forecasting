# Volatility_forecasting
Objective: The goal of this project was to predict the one-week-ahead volatility of Nifty
Fifty stocks using various machine learning models, specifically GARCH, univariate LSTM,
and multivariate LSTM.
Data Collection: Data for the Nifty Fifty stocks were sourced from Yahoo Finance using the
yfinance library. The dataset included historical price data, from which a 30-day volatility
column was derived.
Data Preprocessing:
1. Volatility Calculation: A 30-day rolling volatility measure was computed for each
stock.
2. Scaling: The volatility data was normalized using the MinMax Scaler to ensure
uniformity across different scales.
Modeling:
1. GARCH Model: Applied for capturing time-series volatility.
2. Univariate LSTM: Used for predicting future volatility based solely on past
volatility data.
3. Multivariate LSTM: Leveraged additional features alongside past volatility for
improved prediction accuracy.
Evaluation: The models' performance was assessed using Root Mean Squared Percentage
Error (RMSPE) and Root Mean Squared Error (RMSE). The project achieved an RMSPE of
0.4 and an RMSE of 0.02, indicating high predictive accuracy.
Conclusion: The project successfully demonstrated the capability of machine learning
models, particularly LSTM, in predicting stock volatility. The findings suggest that
incorporating additional market features can significantly enhance prediction accuracy, which
can be valuable for traders and financial analysts in making informed decisions.
