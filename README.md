# credit-risk-classification
UT Austin Data Visualization Bootcamp Module 20 Challenge - Credit Risk Classification

** ** Overview of the Analysis
The goal of this analysis is to assess the risk associated with lending money to specific borrowers. The dataset includes variables such as Loan Size, Interest Rate, Borrower Income, Debt-To-Income Ratio, Number of Accounts, Derogatory Marks, and Total Debt. By analyzing factors like income and debt, we aim to predict whether lending to a borrower is a risky decision.
The process involved in this model includes data exploration, separating the loan status from the other features for prediction purposes, splitting the dataset into training and testing subsets, fitting a logistic regression model, and 
evaluating its performance using a confusion matrix and classification report.

** ** Results
Question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
Answer: The model makes perfect predictions for the healthy loans label as all of the precision, recall, and f1-score classification reports are 1. It has very high precision, recall, and f1-score for high-risk loan labels. One thing to note is that the data is not perfectly balanced so the model could vary depending on the dataset.

** ** Summary
The logistic regression is a good model to use to predict loan status as it has perfect predictions for healthy loans. It also has high predictions for high-risk labels. Performance does vary quite a bit for problems like this. The precision is lower than the recall for the high-risk loan label. This means that there is more likely to be a Type I error where healthy loans will be labeled as high-risk loans. The recall means that there is more likely to be a Type II error where no high-risk loan gets mislabeled. Both are not good when they happen, but the latter is worse as there will be high-risk loans given out as they were labeled as no high risk.
