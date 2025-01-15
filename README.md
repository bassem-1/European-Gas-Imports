 # European Natural Gas Imports Prediction

## Project Overview
This project aims to predict European natural gas imports from various countries using time series analysis. It utilizes an ARIMA model to forecast imports based on historical data, enhancing decision-making processes in energy trading and supply chain management.

## Table of Contents
- [Background](#background)
- [Data](#data)
- [Technologies Used](#technologies-used)
- [Model Implementation](#model-implementation)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion and Insights](#conclusion-and-insights)
- [Contributions](#contributions)
- [License](#license)]

## Background
With the growing demand for natural gas in Europe, accurately predicting import volumes is crucial for optimizing supply chain operations. This project leverages statistical methods to provide insights into future import trends.

## Data
The dataset used in this project consists of historical daily natural gas import data for the European Union. The data is sourced from Bruegel, a European think tank (https://www.bruegel.org/dataset/european-natural-gas-imports), covering the period from [01.08.2018] to [20.10.2024]. The dataset includes:
- Date
- Country
- Daily import volumes

## Technologies Used
- **Python**: The primary programming language.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization.
- **Statsmodels**: For time series modeling (ARIMA).
- **Scikit-learn**: For model evaluation metrics.

## Model Implementation
The ARIMA (AutoRegressive Integrated Moving Average) model is used for forecasting. The steps taken in the implementation include:
1. Data loading and preprocessing.
2. Performing the Augmented Dickey-Fuller (ADF) test for stationarity.
3. Plotting ACF and PACF for determining ARIMA parameters.
4. Fitting the ARIMA model and making predictions.
5. Evaluating the model's performance.

## Evaluation Metrics
The model's performance is evaluated using:
- Mean Squared Error (MSE)
- R-squared (R²)

## Conclusion and Insights
Concluding Insights
- **Predictive Power**: The ARIMA model effectively forecasts future natural gas EU imports by leveraging historical data and capturing temporal relationships through lagged values. Metrics such as Mean Squared Error (MSE) and R-squared (R²) demonstrate the model's effectiveness in capturing import patterns.
- **Key Markets**: Analysis focused on major suppliers like Azerbaijan and Libya, highlighting the impact of their import fluctuations on European gas supply dynamics.
- **Strategic Implications**: Accurate forecasts provide valuable insights for traders and policymakers, aiding in decision-making and supply chain management in the commodities market.
- **Future Work**: Future research could enhance predictive accuracy. Vector AutoRegression could look into patterns between different variables (imports from different countries) to increase forecasting accuracy. Correlation analysis could be helpful to understand how and why variables are correlated. Adding other variables (e.g. weather, sentiment analysis about geopolitical factors,...) and using ML techniques could be beneficial.


## Contributions
Contributions are welcome.

## License
This project is licensed under the MIT License.
