# Payment-Fraud-Detection
The Project implements ML algorithms for Online Payment Fraud detection.

About dataset:
isFraud - The transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

ML model:
Data cleaning including missing values, outliers and multi-collinearity is carried out. 
Data visualization is done for analysis. Label encoding is done for converting categorical data to numerical data. 
After data preprocessing, Random Forest, Decision Tree and Logistic Regression are implemented for fraud detection. Classification report and Confusion matrix are created. The accuracy score of models are compared.
