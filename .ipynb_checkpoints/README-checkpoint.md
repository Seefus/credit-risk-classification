# credit-risk-classification
Module 20 Challenge
We developed an analytical model to assess whether a loan is healthy or high-risk. The model uses several variables as predictors: loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. Using these variables alongside known loan statuses, we trained and tested the model.

The classification report is as follows:
                precision    recall  f1-score   support

  healthy loan       1.00      0.99      1.00     18765
high-risk loan       0.85      0.95      0.89       619

      accuracy                           0.99     19384
     macro avg       0.92      0.97      0.94     19384
  weighted avg       0.99      0.99      0.99     19384

Overall, the model achieved high accuracy at 99%, with particularly strong recall scores for both healthy loans and high-risk loans. High-risk loans reached a recall of 95%, despite representing only 3% of the dataset. This level of precision and recall suggests that the model is well-suited for identifying high-risk loans.

While this model can serve as a useful tool for identifying potential risks, it should be treated as an aid in decision-making, guiding the way but allowing for human judgment in the final course of action.