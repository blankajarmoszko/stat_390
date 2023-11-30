# stat_390
# COVID-19 Booster Vaccination Forecasting

## Project Overview
This project aims to forecast the percentage of the U.S. state and territory populations that have received their first booster COVID-19 vaccination dose. Utilizing data from the CDC, the project explores various time-series modeling techniques to achieve accurate predictions.

## Data Source
The data used in this project is sourced from the CDC's weekly-reported vaccine equity data at the state level in the United States.

## Models Used
- ARIMA
- Auto ARIMA
- Prophet (Univariate and Multivariate)
- XGBoost
- Keras LSTM

Each model is developed, trained, and tuned on the vaccination data, considering the cumulative nature of the dataset and its size.

## Key Findings
- The manually trained ARIMA model displayed the best performance in terms of RMSE.
- Overfitting was a common challenge across multiple models.
- Specific age groups' vaccination rates and manufacturers' data were crucial in predicting overall vaccination rates.
<<<<<<< HEAD

=======
>>>>>>> main
