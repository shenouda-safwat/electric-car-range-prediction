# 🔋 Electric Car Range Prediction

Welcome to the **Electric Car Range Prediction** project! 🚗⚡

This project uses real-world electric vehicle (EV) specifications to build a machine learning model that accurately predicts the driving range of EVs based on their technical specifications.

---

## 📂 Dataset Overview

- **Source**: EV Database ([ev-database.org](https://ev-database.org))
- **Rows**: 478 EV models
- **Columns**: 22 features including:
  - `brand`, `model`, `top_speed_kmh`, `battery_capacity_kWh`
  - `torque_nm`, `efficiency_wh_per_km`, `range_km` (target)
  - And many other car specs like dimensions, acceleration, seats, etc.

---

## 🔍 Project Pipeline

### 1. Exploratory Data Analysis (EDA)
- Handling missing values
- Visualizing feature distributions
- Correlation heatmaps

### 2. Feature Engineering
- Cleaned `cargo_volume_l` and missing values
- Selected most important features for prediction

### 3. Model Building
Tested multiple models:
- 🔹 **Linear Regression**
- 🔹 **Random Forest Regressor**
- 🔹 **Gradient Boosting Regressor**
- 🔹 **Stacking Regressor** (Best Performer)

### 4. Evaluation Metrics
Evaluated using:
- ✅ RMSE (Root Mean Squared Error)
- ✅ MAE (Mean Absolute Error)
- ✅ R² Score

### 5. Results (StackingRegressor 🧠)
```
RMSE: 16.30
MAE: 12.67
R² Score: 0.9740
```

### 6. Visualizations
- 📊 RMSE, MAE, R² comparison
- 📈 Actual vs. Predicted Range

---

## 🛠️ How to Run This Project

```bash
# 1. Clone the repository
https://github.com/shenouda-safwat/electric-car-range-prediction

# 2. Open the Colab notebook (or run locally)

# 3. Install required libraries
!pip install pandas scikit-learn matplotlib seaborn xgboost

# 4. Run each cell step-by-step 📈
```

---

## 📸 Sample Visualization
> 📌 Actual vs Predicted Electric Car Ranges
![actual_vs_predicted](assets/actual_vs_predicted.png)

---

## 🤝 Connect with Me
- 👨‍💻 **Eng. Shenouda Safwat**
- 🔗 [LinkedIn](https://www.linkedin.com/in/shenouda-safwat-bb0993259)
- 📧 shenouda.ibrahim.ai@gmail.com

---

> Made with ❤️ using Python, Pandas, Scikit-Learn & Colab.
