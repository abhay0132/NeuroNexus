#Credit Card Fraud Detection
</br>
This project detects fraudulent transactions using machine learning models. We handle class imbalance using SMOTE and compare the performance of Logistic Regression, Random Forest, and XGBoost classifiers.
</br>
##Dataset##
</br>
Source: Kaggle - Credit Card Fraud Detection
</br>
Size: 284,807 transactions with 492 frauds.
</br>
Features: 30 (anonymized principal components + Time, Amount, Class)
</br>
##Technologies Used##
</br>
1)Python
</br>
2)Jupyter Notebook
</br>
3)pandas, numpy
</br>
4)scikit-learn
</br>
5)imbalanced-learn (SMOTE)
</br>
6)xgboost
</br>
7)matplotlib, seaborn
</br>
| Model               | Description                                  |
| ------------------- | -------------------------------------------- |
| Logistic Regression | Simple baseline model                        |
| Random Forest       | Ensemble model, generally high performance   |
| XGBoost             | Gradient boosting model, powerful & scalable |

</br>
##Evaluation Metrics##
</br>
Each model is evaluated using:
</br>
Accuracy
</br>
Precision
</br>
Recall
</br>
F1 Score
</br>
A comparison chart is plotted for visual analysis.

##Steps Performed##
</br>
1)Data loading and preprocessing
</br>
2)Feature scaling (Amount)
</br>
3)Class imbalance handling with SMOTE
</br>
4)Train/test split
</br>
5)Model training

</br>
| Model               | Accuracy | Precision | Recall | F1-Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 0.94     | 0.93      | 0.94   | 0.93     |
| Random Forest       | 0.99     | 0.99      | 0.99   | 0.99     |
| XGBoost             | 0.99     | 0.99      | 0.99   | 0.99     |

Performance evaluation and comparison
