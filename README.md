# credit-risk-classification
Module 20 Challenge

Starter Notes:  
- credit_risk_classification.ipnb and lending_data.csv are in same folder versus csv in normal resources location.
- To preserve opportunity to compare data later, added original to file name for the data file.  df_credit_original

Answer to Step 4 question is as follows:

**Question:** How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** Healthy Loan (0)
Precision for the healthy loans is 1.00.  This indicates that all the loans predicted as healthy were healthy.
Recall for healthy loans is 0.99.  This indicates very few healthy loans were mistakenly classified as high risk.
F1-Score which balances precision and recall is 1.00 demostrating excellent model performance for healthy loans

High-Risk loan (1)
Precision for the high-risk loans is 0.85.  This indicates that 85% of the loans predicted as high-risk were high risk.
Recall for  high-risk loans is 0.91.  This indicates that the model is 91% effective at identifying high-risk loans.
F1-Score for high-risk loans is 0.88 which indicates a 88% stron balance between precision and recall.  Possibly some improvement could be made.

Overall, the model shows a high level of accuracy at 99%.  The model does a great job in predicting healthy and high-risk loans.

I used class notes and ChatGPT to help me write the code.