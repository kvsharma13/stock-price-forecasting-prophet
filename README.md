📈 Stock Price Trend Forecasting using Prophet
This project forecasts the future stock prices of any public company (e.g., AAPL, TSLA, etc.) using Facebook Prophet, a powerful time series forecasting model. The application pulls real-time historical stock data via Yahoo Finance and provides visualizations along with performance metrics.

🚀 Features
📊 Real-time stock price data fetching

🔮 Forecasting future prices (e.g., next 6 months)

📅 Trend, seasonality, and forecast visualization

✅ Accuracy evaluation using MAE and RMSE

📉 Actual vs Predicted plot for visual performance check

🛠 Tools & Technologies
Python

Prophet

yfinance

matplotlib, pandas, scikit-learn

📊 Model Accuracy

Metric	Value	Relative Error
MAE	6.22 USD	~4.1%
RMSE	7.97 USD	~5.3%
Relative error calculated based on AAPL's average price (~$150) in the training period.

📂 How to Run

pip install yfinance prophet matplotlib scikit-learn pandas

Run the notebook or Python script:

python forecast_stock.py


🧠 Future Improvements
Add external regressors (e.g., trading volume, news sentiment)

Include option to test other models like XGBoost or ARIMA

Streamlit dashboard version for interactive usage
