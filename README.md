# -prediction-or-forecasting-system-utilizing-data-mining-techniques-Arima-Sarima-

Project Overview:
This project focuses on analyzing monthly average champagne sales data and forecasting future sales using time series analysis and forecasting techniques. Below is a detailed description of each functionality:

1. Data Preprocessing:
Functionality:
Reads the champagne sales data from a CSV file.
Handles missing values by dropping the corresponding rows.
Renames the column "Perrin Freres monthly champagne sales millions ?64-?72" to "Sales".
Converts the 'Month' column to datetime format.
2. Exploratory Data Analysis (EDA):
Functionality:
Visualizes the monthly champagne sales data to observe trends and patterns.
Plots a line chart with months on the x-axis and sales on the y-axis.
3. Stationarity Test:
Functionality:
Performs the Augmented Dickey-Fuller (ADF) test to check the stationarity of the sales data.
Outputs the ADF statistic and p-value.
Determines whether the data is stationary based on the p-value.
4. Differencing:
Functionality:
Computes first-order difference and seasonal difference to make the data stationary.
5. Autocorrelation and Partial Autocorrelation Analysis:
Functionality:
Plots autocorrelation and partial autocorrelation functions to identify the autoregressive (AR) and moving average (MA) terms for the SARIMA model.
6. SARIMA Modeling:
Functionality:
Builds several SARIMA models with different orders.
Selects the best-fitted model based on AIC/BIC values.
7. Future Prediction:
Functionality:
Forecasts future sales using the selected SARIMA model.
8. Web Application:
Functionality:
Deploys a Flask web application to display the sales forecast graphically.
Setup Instructions:
Install Required Packages: Ensure the following Python packages are installed:
pandas
numpy
matplotlib
statsmodels
flask

Clone Repository: Clone the repository from the provided URL.
Navigate to Project Directory: Move into the project directory.
Run Flask Application: Execute the Flask application.
View Results: Open a web browser and go to http://127.0.0.1:5000/ to view the forecast results.
