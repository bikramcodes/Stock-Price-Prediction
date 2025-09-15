📈 Stock Price Prediction with Time Series Modeling

Forecasting stock prices using statistical time series models. This project explores multiple forecasting approaches, compares their performance, and visualizes predictions against real stock data.

🚀 Overview

The project demonstrates end-to-end stock price forecasting using ARIMA-family models. Key steps include:

🔎 Exploratory Data Analysis (EDA): Box plots, seasonal decomposition

📊 Statistical Tests: Augmented Dickey-Fuller (ADF) for stationarity, Durbin-Watson for autocorrelation

⚙️ Models Implemented: ARIMA, SARIMA, and SARIMAX

🛠️ Diagnostics: Residual analysis and validation plots

📈 Forecasting: Comparison of predictions with actual test data

The goal is to show how classical time series methods can still deliver strong predictive power for financial datasets.

🛠️ Tech Stack

Python

Pandas, NumPy – data preprocessing

Matplotlib, Seaborn – visualization

Statsmodels – ARIMA, SARIMA, SARIMAX models

Jupyter Notebook

⚡ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/bikramcodes/Stock-Price-Prediction.git
cd Stock-Price-Prediction


2️⃣ Create and activate a virtual environment

python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate


3️⃣ Install dependencies

pip install -r requirements.txt


4️⃣ Launch Jupyter Notebook

jupyter notebook

📊 Results

Seasonal decomposition revealed strong trend + seasonal patterns.

ADF test confirmed stationarity after differencing.

SARIMAX outperformed ARIMA and SARIMA in capturing seasonality.

RMSE was reduced to 2.39, showing strong predictive performance.

Forecasts closely tracked test data, demonstrating reliable predictive capability.

(Insert prediction vs. actual plot here for best effect)

🚧 Future Improvements

Extend to LSTM/GRU deep learning models for long-term predictions.

Add hyperparameter tuning automation (GridSearchCV for ARIMA).

Experiment with multivariate forecasting (including external indicators like volume, market indices).

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to add.