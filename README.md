# Titanic Survival Prediction 🚢

## 📌 Overview
This project implements an end-to-end Machine Learning pipeline to predict passenger survival on the Titanic dataset.

---

## ⚙️ Workflow
- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Training
- Model Evaluation
- Model Comparison

---

## 📥 Dataset

The dataset used in this project is the Titanic dataset.

Source:
https://www.kaggle.com/competitions/titanic/data

---

## 🤖 Models Used
- Logistic Regression
- Random Forest
- XGBoost

---

## 📊 Results

| Model | Accuracy | F1 Score |
|------|--------|--------|
| Logistic Regression | 0.776 | 0.718 |
| Random Forest | 0.770 | 0.705 |
| XGBoost | **0.799** | **0.731** |

---

## 🏆 Best Model
XGBoost performed best based on both Accuracy and F1 Score.

---

## 📈 Key Insights
- Ensemble methods performed better than linear models
- XGBoost captured complex patterns effectively
- Proper preprocessing significantly improved performance

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

---

## 📂 How to Run
1. Clone the repository
2. Install required libraries
3. Run the Jupyter Notebook

---

## 🔁 Reproducibility

To reproduce results:
1. Download dataset from Kaggle link
2. Place `train.csv` in project directory
3. Run the notebook

---

## 📌 Conclusion
XGBoost is the most effective model for this dataset due to its boosting mechanism and ability to handle non-linear relationships.
