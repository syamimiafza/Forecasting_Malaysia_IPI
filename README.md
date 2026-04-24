# 📈 Time Series Analysis: Forecasting Malaysia IPI

This project focuses on time series analysis and forecasting of Malaysia’s Industrial Production Index (IPI) using Python. The analysis uses two CSV datasets, namely ipi.csv and lfs_month_duration.csv, to study the movement of Malaysia’s industrial production together with labour force/unemployment-related data.

The main objective of this project is to explore historical monthly trends, identify patterns, and build forecasting models that can estimate future values. The ipi.csv dataset is used to analyse Malaysia’s Industrial Production Index, while the lfs_month_duration.csv dataset is used to include unemployment data for comparison and additional time series forecasting analysis.

The project begins with data preprocessing, where both datasets are imported, date columns are converted into proper datetime format, and the datasets are merged based on the monthly date column. Missing values are checked and removed to ensure the dataset is clean and suitable for analysis. Descriptive statistics such as mean, median, variance, standard deviation, minimum, maximum, and interquartile range are also calculated to understand the behaviour of the variables.

Several graphical summaries are included, such as line plots, histograms, and boxplots, to visualise the trend and distribution of IPI and unemployment data. The project then applies different time series forecasting methods, including Additive Decomposition, Multiplicative Decomposition, Double Exponential Smoothing / Holt’s Method, and Box-Jenkins models such as ARIMA and SARIMAX.

Model performance is evaluated using common forecasting accuracy metrics, including Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE). These metrics help compare how well each model predicts the actual testing data.

✨ Key Features:

📂 Uses two CSV datasets: ipi.csv and lfs_month_duration.csv

🧹 Data preprocessing and cleaning

📊 Descriptive and graphical analysis

📉 Time series decomposition

🔮 Forecasting using Holt, ARIMA, and SARIMAX

✅ Model evaluation using MAE, RMSE, and MAPE

Overall, this project demonstrates how time series techniques can be applied to analyse and forecast Malaysia’s economic indicators using real monthly data.
