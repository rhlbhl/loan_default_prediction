# loan_default_prediction

**Project Name – Loan Default Prediction** 
Financial loan services are leveraged by companies across many industries, from big banks to financial institutions to government loans. 
One of the primary objectives of companies with financial loan services is to decrease payment defaults and ensure that individuals are paying back their loans as expected. 
In order to do this efficiently and systematically, many companies employ machine learning to predict which individuals are at the highest risk of defaulting on their loans, so that proper interventions can be effectively deployed to the right audience.

## Data Exploration & Cleaning - Findings
-  Dataset is pretty clean.
-  Income, Loan Amount, Interest Rate and Age are the most important features that influence loan default status.
-  Load defaults are high for the age group between 18 to 40.
-  Load defaults are high for the income group 15000 to 35000.
  
## Modeling Findings
•	Decision Tree Classifier, Random Forest Classifier, k-NN, Gradient Boosting Classifier and AdaBoost Classifier all of them show accuracy of around 88%

**Summary**
- Based on our evaluation using ROC AUC, accuracy, precision, recall, and F1-score, the models achieve high overall accuracy (around 88%), but their precision, recall, and F1-scores remain suboptimal. 
This suggests that while the models reliably predict the majority class (non-defaulters), they struggle to correctly identify defaulters. 
Although the high ROC AUC values indicate that the models have reasonable discriminative power, the low recall and F1-scores reveal that the detection of the minority class (defaulters) is inadequate.

Therefore, further optimization—such as applying rebalancing techniques, fine-tuning model parameters, or improving calibration—is necessary to enhance the detection of loan defaulters.
