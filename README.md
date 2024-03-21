# ASU_DABC_HW20
credit-risk-classification
# Overview of the Analysis
The purpose of the analysis was to create the model that is good at predicting high-risk and low risk loans.
The bank gathered some data on its borroweres with the information that believed to be most relavent to the ability of the borower to pay off the loan. The data per borrower inclueds 6 data points such as: 'loan_size', 'interest_rate', 'borrower_income', 'debt_to_income', 'num_of_accounts', 'derogatory_marks', 'total_debt'. The data also had a column with the 'loan_status' per each borrower. Based on this information I had to train the model to classify the borrower as high-risk or low-risk customer for future loans.
 The model was trying to classify the borrower as high-risk or low-risk customer for future loans. It will help the bank to quickly assess thier cusomers. The original data tables had about 77.5k rows
The data was devided on train and test sets. The train data was used to train the model and the test data was used to assess the model performance. There is a lot of good and a few bad loans. So the train and the test data sets had the same percentage of good and bad loans in each set to preserve for better assesment of model performance.
Machine Learning Model LogisticRegression:
The model is good at predicting the 0 (healthy loan) because
precision = 1.00 is high 
recall = 1.00 is high 
f1-score = 1.00 is high 
The model is resonably good at predicting at predicting 1 (high-risk loan) because 
the precision = 0.87 is medium 
the recall = 0.95 is high 
f-1 score = 0.91 is high 
the accuracy scores = 0.99 is high due to a lot of good loan that the model is good at predicting and some bad loans the model is worth at predicting.
Summary
I would recommend to use this model to the bank. It is good at predicting low-risk borrowers. It has a low rate of false positives for low-risk borowers. However, for high-risk borowers identified by the model I would recommend for a bank-worker to take a closer look at the customer because the model has a higher rate of false positives for this category.
