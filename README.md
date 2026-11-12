## XGB_Credit_Card_Fraud_Detection 
This project develops a machine learning–based credit card fraud detection system using a highly imbalanced dataset of 284,807 transactions, where only 492 are fraudulent. The data was preprocessed using feature scaling, PCA-transformed variables, and SMOTE to address class imbalance. An XGBoost model was trained with class weighting and hyperparameter tuning, and evaluated using ROC-AUC, precision, recall, and F1-score. The model achieved a test ROC-AUC of 0.967 with strong fraud detection capability, demonstrating the effectiveness of ensemble learning for real-world financial security applications.

 

### 🧑‍💻 Credit Card Fraud Detection using XGBoost

**Dataset:**

* 284,807 transactions
* 492 fraud cases (0.172%)
* Features: V1–V28 (PCA), Time, Amount

**Method:**

* Data scaling and PCA-based features
* SMOTE oversampling & class weighting
* XGBoost with hyperparameter tuning

**Results:**

* ROC-AUC (Test): **0.967**
* Fraud Precision: **87%**
* Fraud Recall: **82%**
* F1-score: **84%**

**Conclusion:**
XGBoost effectively handled extreme class imbalance and achieved strong fraud detection performance.

