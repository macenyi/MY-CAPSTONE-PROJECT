# Heart Disease Prediction - Capstone Project

## 📌 Project Overview
This project is my capstone submission for [program/course name if applicable].  
The goal is to build machine learning models that predict **heart disease** based on clinical records.  
It demonstrates end-to-end data science skills: data loading, preprocessing, feature engineering, model training, evaluation, and visualization.

---

## 📂 Dataset
- Source: *Heart Failure Clinical Records* dataset (CSV file provided).
- Key features include: `Age`, `Sex`, `ChestPainType`, `RestingBP`, `Cholesterol`, `FastingBS`, `RestingECG`, `MaxHR`, `ExerciseAngina`, `Oldpeak`, `ST_Slope`.
- Target variable: **HeartDisease** (1 = disease present, 0 = no disease).

---

## ⚙️ Workflow
1. **Data Foundation**
   - Loaded dataset into Pandas and SQLite.
   - Verified schema and column names.

2. **Feature Engineering**
   - Created new features:
     - `age_bin` (young, middle, senior)
     - `bp_ratio` (RestingBP / Cholesterol)
     - `sex_chestpain` (combined categorical feature)
   - Encoded categorical variables with one-hot encoding.
   - Scaled numerical features using `StandardScaler`.

3. **Modeling**
   - Baseline models: Logistic Regression, Decision Tree.
   - Advanced models: Random Forest, (optional: XGBoost).
   - Evaluated with accuracy, confusion matrix, and ROC curve.

4. **Insights**
   - Feature importance analysis showed predictors like **Age**, **ChestPainType**, and **RestingBP** as highly influential.
   - Confusion matrix demonstrated strong classification performance.

---

## 📊 Visuals
- **Confusion Matrix**: Showed correct vs incorrect predictions.
- **Feature Importance Chart**: Highlighted top predictors of heart disease.

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- SQLite (for structured queries)
- Google Colab (development environment)

---

## 🚀 Results
- Achieved strong accuracy with Logistic Regression and Random Forest.
- Extracted meaningful clinical insights from feature importance analysis.
- Delivered a reproducible notebook showcasing the full ML pipeline.

AUTHOR
Ndorofem Honesty MacEnyi
Data Science Enthusiast | Machine Learning Practitioner
---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-capstone.git
