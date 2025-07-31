# Churn Modelling 🧠📉

A machine learning project to predict customer churn using bank data. The objective is to identify customers who are likely to leave the bank, enabling targeted retention strategies.

---

## 📊 Overview

This project involves:
- Preprocessing and exploring bank customer data
- Building and evaluating multiple classification models (Logistic Regression, SVM, Random Forest, ANN)
- Selecting the best-performing model for churn prediction
- Visualizing key insights and model performance

---

## 🗃️ Dataset

The dataset used is `Churn_Modelling.csv`, which contains the following columns:

- **Customer Information**: `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`
- **Target Variable**: `Exited` (1 if the customer left the bank, 0 otherwise)

---

## 🛠️ Tools & Libraries

- Python 3.x
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras
- Tableau (for optional dashboarding)

---

## 🧪 Model Building

Multiple classification models were implemented and evaluated:
- ✅ Logistic Regression
- ✅ Support Vector Machine (SVM)
- ✅ Random Forest
- ✅ Artificial Neural Network (ANN)

The ANN was implemented using TensorFlow/Keras and achieved an **F1-score of ~0.86**.

---

## 🧹 Preprocessing Steps

- Dropped irrelevant columns: `RowNumber`, `CustomerId`, `Surname`
- Label encoded categorical variables (e.g., Gender)
- One-hot encoded `Geography`
- Scaled features using `StandardScaler`
- Split data into training and testing sets (80/20)

---

## 📈 Model Evaluation

Metrics used:
- Accuracy
- Precision, Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve

---
## google colab link {https://colab.research.google.com/drive/1k1B6fCLiP5IBhGK992xpdJ3NEfA-6Ku5?usp=sharing}
## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/itsanik1201/Churn-Modelling-.git
   cd Churn-Modelling-
