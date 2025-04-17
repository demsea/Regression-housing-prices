# Regression-housing-prices
## 🏡 House Price Prediction - Kaggle Competition

This project was developed for a **Kaggle competition** focused on predicting house prices using **Supervised Machine Learning**.

The dataset included **~80 features per house**, such as physical attributes, location, and condition, with the goal of accurately estimating each house’s sale price.

---

### 🧠 Approach

- **Data Preprocessing:**
  - `SimpleImputer` for handling missing values
  - `OrdinalEncoder` and `OneHotEncoder` for encoding categorical features
  - `SelectKBest` for selecting top features based on univariate statistical tests

- **Model Training:**
  - Trained the model on the processed dataset
  - Evaluated performance using a separate test set

---

### ✅ Key Highlights

- Used **feature selection** to improve model performance and reduce noise
- Applied consistent preprocessing for both numerical and categorical data
- Evaluated model accuracy and performance on unseen data

---

This project showcases a full **regression pipeline** for tabular data, combining preprocessing, feature selection, and modeling in a structured and scalable way.


