# Product Sales Prediction Using Multiple Forecasting Models

## Project Objective
The goal of this project is to explore various quantitative forecasting methods to predict the sales of products in the given dataset. The project compares **time series models** and **regression-based approaches** to identify the most accurate model for sales forecasting.

---

## Steps Performed
1. Conducted **time series analysis** to explore trends, seasonality, and patterns in the sales data.  
2. Applied multiple forecasting models on the **training dataset**, including:
   - Seasonal Naïve Model
   - Holt-Winters (Triple Exponential Smoothing)
   - ARIMA and Seasonal ARIMA Models
   - Linear Regression Model  
3. Evaluated model performance and selected the best-performing model to forecast sales on the **test dataset**.

---

## Models Used
- **Seasonal Naïve Model:** Uses last season’s observations as forecasts for the next season.  
- **Holt-Winters Model:** Triple exponential smoothing to capture trend and seasonality.  
- **ARIMA & SARIMA Models:** Autoregressive integrated moving average models for time series forecasting.  
- **Linear Regression Model:** Regression-based approach assuming historical patterns will repeat.

---

## Conclusion
The **Linear Regression model** outperformed the time series models for this dataset. The dataset displayed **highly seasonal behavior with a linear trend**, making regression an effective choice for forecasting future sales.

---

## Key Takeaways
- Regression models can outperform classical time series models when datasets have linear trends and seasonality.  
- **Model selection** is critical for accurate forecasting.  
- Performing **exploratory data analysis** is essential to understand data patterns before modeling.

---

## Tools & Technologies
- Python (Pandas, NumPy, scikit-learn, statsmodels)
- Excel / CSV data handling
- Jupyter Notebook for analysis and visualization
