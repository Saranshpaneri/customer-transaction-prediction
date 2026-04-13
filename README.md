# Customer Transaction Prediction

## 📌 Project Overview

This project predicts whether a customer will make a transaction based on anonymized numerical features. The dataset contains high-dimensional data with weak signals and class imbalance.

---

## 🎯 Objective

To build a machine learning model that accurately predicts customer transactions while handling class imbalance and optimizing performance.

---

## 📊 Dataset

* 200,000 rows
* 200 anonymized numerical features
* Target variable (0 = No Transaction, 1 = Transaction)

---

## ⚙️ Workflow

1. Data Understanding
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Model Building
5. Model Evaluation
6. Model Optimization

---

## 🤖 Models Used

* Logistic Regression ✅ (Final Model)
* Random Forest
* XGBoost

---

## 📈 Final Model Performance

* Recall (Class 1): ~0.68
* ROC-AUC Score: ~0.86
* Improved balance using threshold tuning

---

## 🧠 Key Insights

* Features are mostly normally distributed
* Low correlation between features
* Class imbalance affects model performance significantly
* Logistic Regression performed best for weak signal data

---

## 💾 Model Saving

The final model and scaler are saved using pickle for future use and deployment.

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Advanced models
* Feature engineering

---

## 👤 Author

Saransh Paneri
