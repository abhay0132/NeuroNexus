# 🛡️ Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using various machine learning models. It handles the class imbalance problem using **SMOTE** and compares the performance of **Logistic Regression**, **Random Forest**, and **XGBoost** classifiers.

---

## 📁 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Transactions**: 284,807
- **Fraud Cases**: 492 (highly imbalanced)
- **Features**: 30 (including anonymized `V1-V28`, `Amount`, `Time`, and `Class`)

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- imbalanced-learn
- xgboost
- matplotlib, seaborn

---

## 🧠 Models Implemented

| Model               | Description                                  |
|--------------------|----------------------------------------------|
| Logistic Regression| Baseline linear classifier                   |
| Random Forest       | Ensemble model with decision trees           |
| XGBoost             | Gradient boosting classifier for performance |

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

All models are compared using the metrics above and visualized with a bar chart.

---

## ✅ Steps Performed

1. **Data Loading** from CSV
2. **Exploratory Data Analysis** (EDA) & Preprocessing
3. **Feature Scaling** for the `Amount` column
4. **Class Imbalance Handling** using SMOTE
5. **Train/Test Split**
6. **Model Training**: Logistic Regression, Random Forest, XGBoost
7. **Performance Evaluation & Comparison**
8. **Visualization of Model Scores**

---

## 📈 Sample Results

| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 0.94     | 0.93      | 0.94   | 0.93     |
| Random Forest      | 0.99     | 0.99      | 0.99   | 0.99     |
| XGBoost            | 0.99     | 0.99      | 0.99   | 0.99     |

*Note: Scores may vary slightly depending on random state and split.*

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
