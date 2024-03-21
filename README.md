# ASU_DABC_HW20
credit-risk-classification
# Overview of the Analysis
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of the analysis was to create the model that is good at predicting 1 (high-risk loan).
Explain what financial information the data was on, and what you needed to predict. The bank gathered some data on its borroweres with the information that believed to be most relavent to the ability of the borower to pay off the loan. The data per borrower inclueds 6 data points such as: 'loan_size', 'interest_rate', 'borrower_income', 'debt_to_income', 'num_of_accounts', 'derogatory_marks', 'total_debt'. The data also had a column with the 'loan_status' per each borrower. Based on this information I had to train the model to classify the borrower as high-risk or low-risk customer for future loans.
Provide basic information about the variables you were trying to predict (e.g., value_counts). My model was trying to classify the borrower as high-risk or low-risk customer for future loans. It will help the bank to quickly assess thier cusomers. The original data tables had about 77.5k rows
Describe the stages of the machine learning process you went through as part of this analysis. The data was devided on train and test sets. The train data was used to train the model and the test data was used to assess the model performance. There is a lot good and a few bad loans. So the train and the test data sets had the same percentage of good and bad loans in each set to preserve for better assesment of model performance.
Briefly touch on any methods you used (e.g., LogisticRegression, or any other algorithms). To predict the 0 (healthy loan) and 1 (high-risk loan) labels the model was based on LogisticRegression algorithms. Which are good for classification ML models.
Results
Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model LogisticRegression:
Description of Model 1 Accuracy, Precision, and Recall scores. The model is good at predicting the 0 (healthy loan) because both precision = 1.00 is high recall = 1.00 is high f1-score = 1.00 is high The model is resonably good at predicting at predicting 1 (high-risk loan) because the precision = 0.87 is medium the recall = 0.95 is high f-1 score = 0.91 is high the accuracy scores = 0.99 is high due to a lot of good loan that the model is good at predicting and some bad loans the model is worth at predicting.
Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Which one seems to perform best? How do you know it performs best?
Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's? )
If you do not recommend any of the models, please justify your reasoning. I would recommend to use this model to the bank. It is good at predicting low-risk borrowers. It has a low rate of false positives for low-risk borowers. However, for high-risk borowers identified by the model I would recommend for a bank-worker to take a closer look at the customer because the model has a higher rate of false positives for this category.
