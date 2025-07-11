# ⚡ Electricity Price Forecasting (France & Germany)

This project models and explains daily variations in electricity futures prices for France and Germany using weather, commodity, and energy exchange data.

---

## 📊 Objective

To **explain and predict short-term electricity price variations** using a diverse set of real-world indicators:
- Weather (temperature, rain, wind)
- Energy production (nuclear, hydro, gas, solar, etc.)
- Electricity imports/exports (cross-border flows)
- Commodity futures (carbon, coal, gas)

---

## 🧠 Machine Learning Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- K-Nearest Neighbors (K-NN)
- Decision Tree Regressor
- ✅ **Random Forest Regressor (Best)**

### 🔍 Best Model Performance (Random Forest):
- **Spearman Correlation**: 0.5299
- **R² Score**: 0.5377  
- **RMSE**: 0.6939  

---

## 📈 Feature Engineering & EDA

- Outlier removal using Z-score & box plots
- Heatmaps for correlation analysis
- Scatter plots of features vs target variable
- One-hot encoding for `COUNTRY` column
- Standardization (mean = 0, std = 1)

📌 Conclusion

Random Forest performed best in identifying important features such as wind energy, residual load, and gas prices that heavily influence short-term electricity pricing in both France and Germany.
