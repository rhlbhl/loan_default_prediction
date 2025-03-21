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

                Accuracy  Precision    Recall  F1-Score
Decision Tree   0.885295   0.550481  0.038814  0.072514
Random Forest   0.886509   0.685714  0.032542  0.062136
k-NN            0.875269   0.330202  0.077458  0.125481
Gradient Boost  0.887174   0.648707  0.051017  0.094595
AdaBoost        0.886920   0.614679  0.056780  0.103957
Interpretation:The table presents the performance metrics of five different classification models: Decision Tree, Random Forest, k-NN, Gradient Boost, and AdaBoost. The results indicate that all models exhibit high accuracy (~88%), but their precision, recall, and F1-score are relatively low. This suggests that while the models are good at predicting the majority class (likely non-default cases), they struggle to correctly identify defaulters. Among the models, Random Forest and Gradient Boosting have the highest precision


**Summary**
- Based on our evaluation using ROC AUC, accuracy, precision, recall, and F1-score, the models achieve high overall accuracy (around 88%), but their precision, recall, and F1-scores remain suboptimal. 
This suggests that while the models reliably predict the majority class (non-defaulters), they struggle to correctly identify defaulters. 
Although the high ROC AUC values indicate that the models have reasonable discriminative power, the low recall and F1-scores reveal that the detection of the minority class (defaulters) is inadequate.

Therefore, further optimization—such as applying rebalancing techniques, fine-tuning model parameters, or improving calibration—is necessary to enhance the detection of loan defaulters.
