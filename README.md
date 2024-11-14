# GDP-Prediction
This project focuses on predicting future GDP growth by analyzing key economic indicators from 1994-2022 across the USA, UK, China, and Japan. Utilizing LSTM and ARIMA models, it highlights significant predictors like government expenditure through interpretability analyses. The study offers insights into both long-term and short-term GDP drivers.

Project Objective
The main objective of this project is to build interpretable models using machine learning techniques, such as Long Short-Term Memory (LSTM) networks and ARIMA models, to predict GDP growth based on various economic indicators. Additionally, this project highlights the importance of different features in driving GDP growth through permutation-based feature importance analysis.

Dataset
Data Sources
The datasets used in this project were obtained from:
[The World Bank](https://data.worldbank.org/)
[Organization for Economic Co-operation and Development (OECD)](https://www.oecd.org/en/data.html)
The data spans from 1994 to 2022, providing a comprehensive view of economic trends and allowing for robust predictive modeling.

Models Implemented
Long Short-Term Memory (LSTM)
LSTM models are recurrent neural networks capable of capturing long-term dependencies in sequential data.
Implementation details include window size adjustment, optimization using the Adam optimizer, and hyperparameter tuning.

ARIMA (Autoregressive Integrated Moving Average)
Suitable for stationary or near-stationary time-series data.
Model parameters were fine-tuned to capture temporal patterns effectively.

Model Evaluation
The models were evaluated using:
Root Mean Squared Error (RMSE): Measures prediction accuracy.
Accuracy Percentage: Compares predicted values to actual GDP values.

Key Findings
Government Expenditure emerged as the most significant driver of GDP growth across all countries.
Permutation-based feature importance analysis revealed varying feature importance across different economies, highlighting the unique economic drivers for each country.

Results
ARIMA Model outperformed LSTM in terms of prediction accuracy for China, Japan, and the UK.
In the USA, the LSTM Model showed superior performance due to the complex, non-linear relationships in GDP data.

Future Scope
Incorporation of higher-frequency data (quarterly/monthly) for improved accuracy.
Exploration of probabilistic forecasting techniques.
Integration of alternative data sources, such as social media and online trends, for better predictive insights.






