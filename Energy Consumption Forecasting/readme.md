# **Energy Consumption Forecasting with Exogenous Factors**

## **Overview**
This project analyzes energy consumption patterns using time series analysis (TSA) techniques while integrating exogenous factors such as weather conditions and holiday indicators. The aim is to build a robust forecasting model that provides insights into energy demand fluctuations over time. The dataset combines daily energy usage records from households, detailed weather data, and UK bank holidays to create a comprehensive understanding of the factors influencing energy consumption.


## **Key Learnings**

1. **Data Preprocessing**:
    
    - Combining datasets from multiple sources (energy, weather, holidays) requires meticulous preprocessing to ensure consistency and accuracy.
    - Handling missing values and creating derived features, such as average energy per household, were critical steps in enriching the dataset.
2. **TSA Methodology**:
    
    - Testing for stationarity and performing differencing were essential to ensure the series met model assumptions.
    - Decomposition into trend, seasonality, and residuals helped uncover hidden patterns in the data.
3. **Model Development**:
    
    - SARIMAX proved to be an effective tool for time series forecasting when combined with external predictors.
    - The importance of hyperparameter tuning (e.g., order of ARIMA terms and seasonal components) was evident in achieving optimal model performance.
4. **Visualization and Insights**:
    
    - Time series visualizations allowed for clear interpretation of seasonal and weather-related trends.
    - Correlation matrices provided valuable insights into how weather variables impact energy consumption.
