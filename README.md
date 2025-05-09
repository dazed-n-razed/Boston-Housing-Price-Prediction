# 🏠 Boston Housing Price Prediction

This project predicts housing prices in Boston suburbs using various regression and classification techniques. It explores key features affecting house prices and applies both traditional and ensemble learning models to deliver accurate predictions.

---

## 📊 Dataset

- **Source**: UCI Machine Learning Repository (Boston Housing Dataset)
- **Target Variable**: `PRICE` (Median value of owner-occupied homes in $1000s)
- **Features**: CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT

---

## ⚙️ Methods Used

### 🔍 1. Data Preprocessing & EDA
- Checked for nulls and outliers
- Normalized/standardized numerical features
- Visualized data with:
  - Heatmaps
  - Correlation plots
  - Distribution graphs
- Selected top features based on correlation

---

### 🤖 2. Regression Models (Continuous PRICE Prediction)
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

#### 📈 Evaluation Metrics:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

### 🧠 3. Classification Models (PRICE → Categories)
- Converted `PRICE` into:
  - Binary: High-priced vs Low-priced homes
  - Multi-class (if applicable)
- **Models Used**:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN)

#### 🧪 Evaluation Metrics:
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Score

---

### 🔁 4. Ensemble Learning
- **Bagging**: Random Forest
- **Boosting**: Gradient Boosting / XGBoost (if used)
- Improved accuracy and reduced overfitting

---

## 🔍 Key Insights
- `RM`, `LSTAT`, and `PTRATIO` were among the most influential features
- Ensemble models like Random Forest showed the best performance
- Demonstrated flexibility by adapting regression into classification

---

## 📁 Project Structure

