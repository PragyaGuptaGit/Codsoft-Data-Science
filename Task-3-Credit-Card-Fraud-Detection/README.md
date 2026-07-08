# Credit Card Fraud Detection

## Project Overview

This project aims to detect fraudulent credit card transactions using Machine Learning. The dataset contains transaction details labeled as either legitimate or fraudulent. The objective is to build classification models that can accurately identify fraudulent transactions.

## Dataset

* Dataset Name: Credit Card Fraud Detection Dataset
* File: `creditcard.csv`
* Features: 31 columns (including Time, Amount, V1–V28, and Class)
* Target Variable:

  * 0 = Legitimate Transaction
  * 1 = Fraudulent Transaction

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Data Preprocessing

The following preprocessing steps were performed:

* Loaded the dataset.
* Explored dataset information and summary statistics.
* Checked for missing values.
* Removed duplicate records.
* Standardized the Amount column using StandardScaler.
* Split the data into training and testing sets.

## Machine Learning Models Used

1. Logistic Regression
2. Random Forest Classifier

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, and F1-Score)

## Results

* Logistic Regression successfully classified the transactions but achieved lower performance compared to Random Forest.
* Random Forest Classifier achieved the best performance with very high accuracy and better fraud detection capability.

## Conclusion

This project demonstrates that Machine Learning can effectively detect fraudulent credit card transactions. Among the models tested, the Random Forest Classifier produced the best overall performance and is the preferred model for this dataset.

## Author

Pragya Gupta
Machine Learning Internship – CodeSoft
