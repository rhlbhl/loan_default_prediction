# loan_default_prediction

**Project Name – Loan Default Prediction** 
Financial loan services are leveraged by companies across many industries, from big banks to financial institutions to government loans. One of the primary objectives of companies with financial loan services is to decrease payment defaults and ensure that individuals are paying back their loans as expected. In order to do this efficiently and systematically, many companies employ machine learning to predict which individuals are at the highest risk of defaulting on their loans, so that proper interventions can be effectively deployed to the right audience.

## Data Exploration & Cleaning - Findings
-  Dataset is pretty clean.
-  Income, Loan Amount, Interest Rate and Age are the most important features that influence loan default status.
-  Load defaults are high for the age group between 18 to 40.
-  Load defaults are high for the income group 15000 to 35000.

## Modeling - Findings

In this analysis, we analysed the performance of six machine learning classifiers on provided dataset. 

1. Decision Tree Classifier - The Decision Tree classifier showed an accuracy of 77%
2. Random Forest Classifier - The Random Forest classifier showed an accuracy of 80%
3. Logistic Regression Model - The Logistic Regression showed highest accuracy score of 86% among all classifiers and also showed highest precision of 100%
4. k-Nearest Neighbors (k-NN) - KNN Classifier showed lowest accuracy of 67%. 
5. Gradient Boosting Classifier - Gradient Boosting Classifier showed accuracy of 82%.
6. AdaBoost Classifier - AdaBoost Classifier showed accuracy of 69%

**Summary**
                                                                                                                                                         
Logistic Regression and Gradient Boosting Classifier showed higher accuracy but due to high precision Logistic Regression proved to be the best model fit.
 
