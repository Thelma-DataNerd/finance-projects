## Finance Projects Portfolio

### Table of Contents
- [Overview](#overview)
- [Credit Card Fraud Prediction System](#credit_card_fraud_prediction_system)
- [Credit Card Risk Analysis](#credit_card_risk_analysis)
- [Presentation](#presentation)
- [Data Source](#data_source)



<img src="https://github.com/Thelma-DataNerd/finance-projects/blob/main/credit_card.jpg" width="500"/>

### Overview
This repository contains my finance-related data analysis and machine learning projects.
It showcases a variety of real-world work in the finance sector — including exploratory data analysis (EDA), predictive modeling, and data visualization.

Each project is organized in its own folder with a brief description, code notebooks, data sources, insights and reports.

---

### Credit_Card_Fraud_Prediction_System:
- Objectives: This project aims to develop a machine learning model for detecting fraudulent credit card transactions. The goal is to predict the likelihood of a transaction being fraudulent or legitimate, thereby reducing financial losses due to fraud and improving overall transaction security.
- Content: The dataset shows credit card transactions from European cardholders in September 2013.
It consists solely of numerical input variables, which have been derived through a Principal Component Analysis (PCA) transformation, reducing the original feature set into a more compact and simplified form.
- Tools: Python, Pandas, NumPy, Scikit-learn
- Models: Logistic Regression, Decision Tree, Random Forest
- Techniques: Data cleaning, exploratory data analysis (EDA), handling imbalanced datasets, feature engineering, data preprocessing, model building and evaluation using AUC-ROC and other performance metrics, and model comparison across different algorithm
- Outcome:
  * The Random forest model outperformed others in detecting fraudulanet transactions while miniizing false positives.
  * The AUC-ROC score (0.9478) for Random forest suggests high discriminatory power between fraus and non-fraud transactions.
  * Feature importance analysis revealed that V14,V4, V3, and V8 were the most significant in fraud detection.
  * The system effectively detects fraudulent transactions with high accurracy and precision.
- Project Link: https://github.com/Thelma-DataNerd/finance-projects/blob/main/Credit%20Card%20Fraud%20Prediction%20System.ipynb
 
 ***
 
### Credit Card Risk Analysis
- Objectives: To evaluate the creditworthiness of individual borrowers, in other to determine the likelihood of borrowers repaying their debts on time.
- Content: The GermanCredit dataset consist of customers data applying for a loan.
- Tools: Python, Pandas, NumPy, Matplotlib, Seaborn, PowerPoint (for presentation)
- Technique: Data exploration and cleaning, exploratory data analysis (EDA), visualization, insights and recommendation, presentation.

  <img src="https://github.com/Thelma-DataNerd/finance-projects/blob/main/credit_risk_image.png" width="500"/>
- Outcome:
  * Most borrowers have low checking and saving balances.
  * Most defaulting borrowers are single men.
  * Defaulting borrowers tend to have no co-applicant or gurantor, increasing loan risk.
  * Borrowers took loans primarily for car purchases, radios and furnitures, which are not income generating assests.
  * Foreign workers and skilled employees formed a significant portion of loan defaulters.
  * Features like credit history, checking balance, and loan duration had the highest influence on default predictions.
- Project Link: https://github.com/Thelma-DataNerd/finance-projects/blob/main/Credict%20Card%20Risk%20Analysis.ipynb

### Presentation
Credit Card Risk Analysis (Link) : https://docs.google.com/presentation/d/1rOXgQbikQ2QD6Rkuu92bj2HWmOFDrYWH/edit?usp=sharing&ouid=108132869827208861678&rtpof=true&sd=true

### Data Source
 * Credit card fraud: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data
 * German credit: https://github.com/Thelma-DataNerd/finance-projects/blob/main/GermanCredit.csv
