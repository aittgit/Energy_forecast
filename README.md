# Energy_forecast
This work involves short-term energy forecasting using historical energy consumption data, with a focus on creating a predictive model to estimate future power consumption. 

We begin by loading and preprocessing the household power consumption dataset, which includes energy consumption, voltage, and other power-related features. The data is cleaned by handling missing values and converting relevant columns to numeric values. We then create time-based features such as hour, day of the week, and month, as well as lag features representing the previous hour’s and the previous day’s consumption, which are crucial for time series forecasting.

Steps followed in this analysis: Data Preprocessing and Feature Engineering, Exploratory Data Analysis (EDA), Predictive Modeling with XGBoost, Forecasting Future Consumption.

The original dataset can be found here: Hebrail, Georges and Alice Berard. 2006. Individual Household Electric Power Consumption. UCI Machine Learning Repository. https://doi.org/10.24432/C58K54.
