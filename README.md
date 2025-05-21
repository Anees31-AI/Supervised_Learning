# Supervised_Learning
Predicting California housing prices using the Random Forest Regression model. Includes visualizations of model performance, residuals, and predicted vs actual price distributions.
# 🏡 California Housing Price Prediction

This project predicts California housing prices using the **Random Forest Regressor** model from scikit-learn. The dataset used is the built-in California Housing dataset. The analysis includes model training, evaluation using RMSE, and insightful visualizations of results and errors.

---

## 📊 Dataset

The [California Housing dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html) is used for this project. It includes various features such as:

- Median income
- House age
- Average number of rooms
- Latitude & Longitude
- etc.

Target variable: **Median house value**

---

## 🧠 Model Used

- **RandomForestRegressor** (200 estimators, no max depth, random state = 42)

---

## 🧪 Train-Test Split

- 80% **Testing**
- 20% **Training**

> Note: This reversed split ratio is uncommon and used here for demonstration purposes.

---

## 📈 Evaluation Metrics

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Visual Evaluation:**
  - Predicted vs Actual Scatter Plot
  - Residuals vs Predicted
  - Residuals Distribution
  - Actual vs Predicted KDE plots

---

## 📷 Visualizations

- Actual vs Predicted Prices  
- Residual Error Analysis  
- Histogram of Prediction Errors  
- KDE of Actual vs Predicted Price Distribution  

---

## 📦 Requirements

- Python 3.x
- NumPy
- pandas
- matplotlib
- seaborn
- scikit-learn


