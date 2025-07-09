# 💳 Credit Card Fraud Detection using Logistic Regression

This project is focused on detecting fraudulent credit card transactions using a machine learning model. Fraud detection is a crucial task in the banking and finance sector, and this project demonstrates how to use a Logistic Regression model on a real-world dataset to tackle this problem.
---
## 📌 Project Overview

- **Project Name**: Credit Card Fraud Detection
- **Algorithm Used**: Logistic Regression
- **Dataset**: Credit card transactions dataset (with anonymized PCA-transformed features)
- **Goal**: To predict whether a transaction is fraudulent or not
- **Accuracy Achieved**: ✅ 99.93%
---
## ⚙️ Tools and Libraries Used

- `Python`
- `Pandas` – for data manipulation
- `NumPy` – for numerical operations
- `Matplotlib` & `Seaborn` – for data visualization
- `Scikit-learn` – for preprocessing, training and evaluation
- `Jupyter Notebook` – for writing and running the code
---
## 🧾 Dataset Description

- `Time`: Time elapsed from the first transaction
- `V1` to `V28`: Principal Components obtained using PCA (anonymized)
- `Amount`: Transaction amount
- `Class`: Target column (0 = Legitimate, 1 = Fraudulent)
---
## 📈 Model Training & Evaluation

### 🔄 Preprocessing Steps:
- Scaled the `Amount` feature using `StandardScaler`
- Split data into training and testing sets (80/20)
- Trained the Logistic Regression model

### ✅ Evaluation Metrics:

| Metric        | Value (approx.) |
|---------------|-----------------|
| Accuracy      | 99.93%          |
| Precision     | 91%+            |
| Recall        | 61%+            |
| F1-Score      | 73%+            |

> Note: These metrics may vary depending on the random split.

---

## 🗂️ Project Structure

# 💳 Credit Card Fraud Detection using Logistic Regression

This project is focused on detecting fraudulent credit card transactions using a machine learning model. Fraud detection is a crucial task in the banking and finance sector, and this project demonstrates how to use a Logistic Regression model on a real-world dataset to tackle this problem.

---

## 📌 Project Overview

- **Project Name**: Credit Card Fraud Detection
- **Algorithm Used**: Logistic Regression
- **Dataset**: Credit card transactions dataset (with anonymized PCA-transformed features)
- **Goal**: To predict whether a transaction is fraudulent or not
- **Accuracy Achieved**: ✅ 99.93%

---

## ⚙️ Tools and Libraries Used

- `Python`
- `Pandas` – for data manipulation
- `NumPy` – for numerical operations
- `Matplotlib` & `Seaborn` – for data visualization
- `Scikit-learn` – for preprocessing, training and evaluation
- `Jupyter Notebook` – for writing and running the code

---

## 🧾 Dataset Description

- `Time`: Time elapsed from the first transaction
- `V1` to `V28`: Principal Components obtained using PCA (anonymized)
- `Amount`: Transaction amount
- `Class`: Target column (0 = Legitimate, 1 = Fraudulent)

---

## 📈 Model Training & Evaluation

### 🔄 Preprocessing Steps:
- Scaled the `Amount` feature using `StandardScaler`
- Split data into training and testing sets (80/20)
- Trained the Logistic Regression model

### ✅ Evaluation Metrics:

| Metric        | Value (approx.) |
|---------------|-----------------|
| Accuracy      | 99.93%          |
| Precision     | 91%+            |
| Recall        | 61%+            |
| F1-Score      | 73%+            |

> Note: These metrics may vary depending on the random split.

---

## 🗂️ Project Structure
creditcard_fraud_detection/
│
├── credit_fraud_detection.ipynb # Jupyter Notebook
├── model.pkl # Trained model file
├── requirements.txt # Libraries used
└── README.md # Project description

