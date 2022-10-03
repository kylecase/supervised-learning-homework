# supervised-learning-homework

## Overview of analysis
Purpose: We want to evaluate data for credit risk
Data used: We are using an imbalanced sample of labeled data of 0 (low-risk), 1 (high-risk) loans
Preprocessing: Pulling in the CSV and splitting the dataset into Training and Testing datasets
Processes used: Logistic regression to evaluable the unbalanced data set. Used RandomOverSampler to resample the data and perform an additional Logistic Regression to compare results

Results: The resampled data performed with higher recall and similar precision to the original unbalanced data set

Summary: Using the RandomOverSampler was an effective technique for increasing the recall of our model.