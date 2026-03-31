# 🎓 Student Performance Analysis & Prediction

## 📌 Overview

This project explores the factors that influence student academic performance and builds a machine learning model to predict exam scores.

Using a dataset of student characteristics (such as study habits, attendance, and demographics), the notebook performs data analysis and trains a regression model to estimate final exam results. It also simulates how changes in certain features may impact predicted performance.

---

## 🎯 Objectives

* Analyze relationships between student attributes and exam performance
* Build a predictive model for exam scores
* Evaluate model performance using standard regression metrics
* Explore how modifying input features affects predicted outcomes

---

## 🧠 Methods & Technologies

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Scikit-learn**

  * Data preprocessing:

    * `StandardScaler`
    * `OneHotEncoder`
    * `ColumnTransformer`
  * Model pipeline:

    * `Pipeline`
    * `RandomForestRegressor`
* **Train/Test Split** for evaluation

---

## 📊 Workflow

1. **Exploratory Data Analysis (EDA)**

   * Distribution of exam scores
   * Correlation analysis between numerical features

2. **Data Preprocessing**

   * Scaling numerical features
   * Encoding categorical variables

3. **Model Training**

   * Random Forest Regressor used to predict exam scores

4. **Model Evaluation**

   * Metrics:

     * RMSE (Root Mean Squared Error)
     * R² Score

5. **Simulation**

   * Generated a synthetic student profile
   * Adjusted numerical features (+1) to observe impact on predicted score

---

## 📈 Results

The model is able to capture relationships between student characteristics and exam performance, providing reasonably accurate predictions on unseen data.

---

## ⚠️ Limitations

* The model identifies correlations, not causation
* Results depend on dataset quality and feature selection
* Feature simulations do not guarantee real-world improvements

---

## 🚀 Future Improvements

* Try additional models (Linear Regression, XGBoost, etc.)
* Perform hyperparameter tuning
* Add feature importance analysis
* Deploy as a simple web app

---

## 📂 Project Structure

```
student-performance-analysis.ipynb
README.md
```

---

## 🤝 Contributions

Feel free to fork the project or suggest improvements!


