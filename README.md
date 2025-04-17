## Finance Projects Portfolio

### Table of Contents
- [Overview](#Overview)
- [Credit Card Fraud Prediction System](#Credit Card Fraud Prediction System:)
- [Credit Card Risk Analysis](#Credit Card Risk Analysis)
- [Presentation](#Presentation)
- [Source of Dataset](#Source_of_Dataset)



<img src="https://github.com/Thelma-DataNerd/finance-projects/blob/main/credit_card.jpg" width="500"/>

### Overview
This repository contains my finance-related data analysis and machine learning projects.
It showcases a variety of real-world work in the finance sector — including exploratory data analysis (EDA), predictive modeling, and data visualization.

Each project is organized in its own folder with a brief description, code notebooks, data sources, insights and reports.

----

### Credit Card Fraud Prediction System:
- Objectives: 
This project aims to develop a machine learning model for detecting fraudulent credit card transactions. 
The goal is to predict the likelihood of a transaction being fraudulent or legitimate, 
thereby reducing financial losses due to fraud and improving overall transaction security.

- Content:
The dataset shows credit card transactions from European cardholders in September 2013.
It consists solely of numerical input variables, which have been derived through a Principal Component Analysis (PCA) transformation, reducing the original feature set into a more compact and simplified form.

- Motivation
Credit card fraud is a significant concern for financial institutions and individuals alike, 
resulting in substantial financial losses annually. Traditional rule-based systems often struggle to keep pace with the evolving nature of fraud patterns. 
This project leverages machine learning techniques to build a robust fraud detection model, 
enabling more accurate and efficient identification of fraudulent transactions

- Steps_Taken:
Data cleaning, exploratory data analysis (EDA), preprocessing, logistic regression modeling, model evaluation using AUC-ROC and other metrics, comparison with decision tree and random forest models

- Results:
  * The Random forest model outperformed others in detecting fraudulanet transactions while miniizing false positives.
  * The AUC-ROC score (0.9478) for Random forest suggests high discriminatory power between fraus and non-fraud transactions.
  * Feature importance analysis revealed that V14,V4, V3, and V8 were the most significant in fraud detection.
  * The system effectively detects fraudulent transactions with high accurracy and precision.
 
### Credit Card Risk Analysis
- Objectives:
  * To evaluate the creditworthiness of individual borrowers, in other to determine the likelihood of borrowers repaying their debts on time.
  * To analyze the credit risk data, identifying trends and patterns, give insights, and recommendations.

- Content: The GermanCredit dataset consist of data of customers applying for a loan.

- Steps_Taken: Data exploration and cleaning, exploratory data analysis (EDA), visualization, presentation.

- Results:
  * Most borrowers have low checking and saving balances.
  * Most defaulting borrowers are single men.
  * Defaulting borrowers tend to have no co-applicant or gurantor, increasing loan risk.
  * Borrowers took loans primarily for car purchases, radios and furnitures, which are not income generating assests.
  * Foreign workers and skilled employees formed a significant portion of loan defaulters.
  * Features like credit history, checking balance, and loan duration had the highest influence on default predictions.

### Presentation
Credit Card Risk Analysis (Link) : https://docs.google.com/presentation/d/1rOXgQbikQ2QD6Rkuu92bj2HWmOFDrYWH/edit?usp=sharing&ouid=108132869827208861678&rtpof=true&sd=true


### Source_of_Dataset
 * Credit card fraud: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data
 * German credit: https://github.com/Thelma-DataNerd/finance-projects/blob/main/GermanCredit.csv
