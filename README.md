
# Phishing URL Detection using Machine Learning

This project explores the development and evaluation of various machine learning models to enhance the efficiency of phishing URL detection. It involves:

1. **Feature Extraction**: Analyzing URLs to extract lexical and web-scraped features that can distinguish between phishing and legitimate URLs.

2. **Modeling**: Implementing and comparing different machine learning algorithms, including K-Nearest Neighbors, Naive Bayes, Logistic Regression, Decision Trees, Random Forests, AdaBoost, XGBoost, and Support Vector Machines.

3. **Performance Evaluation**: Assessing the models based on metrics such as accuracy, precision, recall, and F1-score to determine the most effective approach.


### Need for Phising URL Detection System

Phishing poses a substantial threat to individuals and organizations, leading to identity theft and financial fraud. Traditional detection methods are often inadequate due to the constantly changing nature of phishing tactics. Therefore, there is a critical need for more sophisticated and adaptive detection mechanisms to better protect users from phishing attempts.

## Requirements
    requests == 2.31.0
    whois == 1.20240129.2
    scikit-learn == 1.4.0
    pandas == 2.1.3
    python == 3.10.11

## Dataset Description

- Dataset is available at https://web.cs.hacettepe.edu.tr/~selman/grambeddings-dataset/

- Dataset contains 400K legitimate and 400K Phishing URLs.

- We use 350000 URLs for our Classification/Modeling purpose.

## Feature Extraction
A total of 100 features (lexical and web-scrapped features) are extracted from the URLs.

- Separate URLs from class annotation column into a new CSV.
- Run Extraction.ipynb

## Modeling

We use a number of ML models from Scikit-Learn Library for the purpose of modeling to predict if an URL is Phishing or Non-Phishing.

- K-Nearest Neighbours Algorithm
- Support Vector Machine
- Naive Bayes algorithm
- Logistic Regression
- Decision Tree
- Random Forest
- Adaboost
- XGBoost

For Preproccessing and Modeling run **URL Phishing Detection.ipynb**



