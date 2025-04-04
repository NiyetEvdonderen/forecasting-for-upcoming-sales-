#  Appliance Sales Forecasting with Time Series (ARIMA)
This project provides a simple yet effective method to forecast the **next month's sales** for three major home appliances:

- Washing Machines  
- Dishwashers  
- Refrigerators  

The data is assumed to be **monthly sales figures**, and the forecasting is done using **ARIMA models** from the `statsmodels` library.

---

## 🔍 Features

- **Train-Test Split**: Last month’s data was collected to evaluate performance.
- **Error Metric**: Calculates RMSE to measure prediction accuracy.
- **ARIMA Forecasting**: Predicts next month’s sales value.
- **Visual Output**: Plots historical sales and the forecast.

---

## 🛠️ Requirements

```bash
pip install pandas matplotlib statsmodels scikit-learn
