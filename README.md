# 🎓 Predicting Student Academic Performance Using Machine Learning

## 📌 Overview

This project focuses on predicting students' final academic performance (G3) using machine learning models. The goal is to identify key factors influencing student success and provide early predictions to support better decision-making in education.

---

## 🎯 Objectives

* Predict final student grades (G3)
* Compare multiple machine learning models
* Identify most important features affecting performance
* Improve accuracy using feature engineering

---

## 📊 Dataset

* Source: UCI Machine Learning Repository
* Subjects:

  * Mathematics (`student-mat.csv`)
  * Portuguese (`student-por.csv`)
* Total Features: 30 variables

### Feature Categories:

* Demographic (age, gender)
* Family background (parent education, support)
* Academic (G1, G2)
* Behavioural (study time, absences)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Handle outliers (absences capped)
* Encode categorical variables
* Feature scaling

### 2. Feature Engineering

* Grade Improvement (G2 - G1)
* Average Early Grade
* Family Support Composite

### 3. Models Used

* Decision Tree Regression
* Random Forest Regression
* Support Vector Regression (SVR)

### 4. Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Results

* Random Forest achieved the best performance
* Feature engineering improved model accuracy
* R² score reached up to **0.86**

---

## 🔑 Key Findings

* G2 is the most important predictor
* G1 also strongly influences final grade
* Absences negatively impact performance

---

## 💡 Real-World Application

* Early Warning System (EWS)
* Identify at-risk students
* Improve academic planning

---

## 🛠️ Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib

---

## 📁 Project Structure

```
├── data/
│   ├── student-mat.csv
│   └── student-por.csv
├── notebooks/
├── src/
├── results/
└── README.md
```

---

## 👨‍💻 Authors

* Muhammad Khairul Ibad
* Mirza Nazeef
* Muhammad Syahmi


---

## ⭐ Acknowledgement

Dataset provided by UCI Machine Learning Repository.
