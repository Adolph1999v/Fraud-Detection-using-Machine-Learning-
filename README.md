# **Fraud Detection using Machine Learning**  

This project builds a **Random Forest Classifier** to detect fraudulent transactions. Since fraud cases are rare, special focus was given to handling class imbalance and ensuring the model can actually detect fraud rather than just predicting “non-fraud” all the time.  

---

## **Project Highlights**  
- Data cleaning and preprocessing (removing useless columns, encoding categorical variables).  
- Balanced the dataset to improve fraud detection.  
- Trained and tested a Random Forest model (80/20 split).  
- Evaluated the model using accuracy, precision, recall, F1-score, and AUC.  
- Identified top features that help predict fraud.  

---

## **Key Results**  
- **Accuracy:** 99.4%  
- **AUC:** 0.9996 (almost perfect fraud detection)  
- High recall: nearly all fraudulent cases are detected.  

---

## **Insights**  
- Transaction amount, transaction type (CASH_OUT/TRANSFER), and unusual balance changes are the strongest predictors.  
- These factors make sense because fraudsters often move large sums and trigger irregular account balances.  

---

## **Note**  
The **dataset is not included** in this repository. The notebook contains the full workflow, results, and visualizations (e.g., confusion matrix, feature importance chart).  
