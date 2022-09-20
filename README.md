# Fraud Detection for Credit Card Transactions

This project deals with building an end-to-end model to detect the occurrence of fraudulent transactions in a credit card company.

Dataset contains around 284,807 transactions with only 492 fraud transactions suggesting **high imbalance** in the datatset

1. **Data Preprocessing**: Data was **scaled** and **Principal Component Analysis** was applied to the data to reduce dimensionality while still retaining maximum information

2. **Model Training:** Multiple models like **Decision Tree, KNN, Logistic Regression, SVM, Random Forest, XGBoost** have been trained on the reformed dataset

3. **Model Evaluation:** Keeping in mind the high imbalance in the dataset, **F1 score** has been used to **evaluate the peformance** of the model

4. **Improvisation:** To further improve the performance of the models, **hyperparameter tuning** was conducted on each model

5. **Conclusion:** Finally, the performance of all models was compared to reveal the best performing model 
