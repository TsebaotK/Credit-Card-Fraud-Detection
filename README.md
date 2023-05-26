# project-4

# Credit Card Fraud Detection
This repository contains code and resources for a credit card fraud detection project using machine learning techniques. The project aims to develop an effective fraud detection system to minimize financial losses, protect consumers, and enhance the security of financial transactions.
## Dataset
The dataset used in this project consists of credit card transactions that occurred over a two-day period. Unfortunately, due to confidentiality issues, we cannot provide the original features or additional background information about the data. However, the dataset includes numerical input variables obtained through a PCA transformation. The non-transformed features include 'Time' (seconds elapsed between each transaction and the first transaction) and 'Amount' (transaction amount). The target variable 'Class' indicates whether a transaction is fraudulent (1) or legitimate (0).
Please note that the dataset is highly imbalanced, with fraudulent transactions accounting for only 0.172% of all transactions. Due to this class imbalance, it is essential to use appropriate evaluation metrics such as Area Under the Precision-Recall Curve (AUPRC) rather than accuracy.
## Models
The repository includes implementations of several machine learning models for credit card fraud detection:
1. K-Nearest Neighbors (KNN) Classifier with SMOTE 
2. Hyperparameter Tuning with K-Nearest Neighbors (KNN) Classifier
3. Decision Tree Classifier with and without hyperparameter tuning
4. Random Forest Classifier with Balanced Class Weights

Presentation link: https://docs.google.com/presentation/d/1c4cz43iADzM5Gun6E6-Our7qfFsNdLne/edit?usp=sharing&ouid=107556487375136811101&rtpof=true&sd=true

The CSV was too large to add to the repository, so the link it is here on the Kaggle page: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The evaluation results and performance metrics of each model are provided in the project documentation.
