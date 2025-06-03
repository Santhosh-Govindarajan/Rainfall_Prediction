# 🌧️ Rainfall Prediction using Machine Learning

This project explores Indian rainfall data to uncover insights and train a predictive model. The dataset contains weather variables such as temperature, pressure, humidity, cloud cover, sunshine, wind direction/speed, and whether it rained.

---

## 📁 Project Files

- `Rainfall.csv`: Cleaned dataset containing day-wise weather observations.
- `Rainfall.ipynb`: A complete notebook with:
  - Data cleaning & preprocessing
  - Exploratory Data Analysis (EDA)
  - Handling class imbalance using SMOTE
  - Training an XGBoost classifier
  - Feature importance visualization

---

## 🧠 Key Techniques

- Data preprocessing with pandas
- Missing value imputation
- Encoding categorical targets
- Resampling using SMOTE from `imblearn`
- Model training with XGBoost
- Visualization with matplotlib & seaborn

---

## 📊 EDA Insights

- Daily features such as humidity, dew point, and wind speed show seasonal fluctuations.
- Categorical rainfall patterns are imbalanced (more “yes” than “no”), addressed using SMOTE.


1. Clone this repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
