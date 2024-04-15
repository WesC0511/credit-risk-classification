# credit-risk-classification
hw 20 credit-risk-classification

Module 12 Report
Overview of the Analysis
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

purpose of the analysis.
-predict loan status based on financial information
Explain what financial information the data was on, and what you needed to predict.
-Data has loan amount, income, debt of income, interest rate, total debt. To Predice and assess the risk associated with loans and improving decision-making in lending processes.
Provide basic information about the variables you were trying to predict (e.g., value_counts).
-Variable was 'loan_status', indicating whether a loan was classified as healthy (0) or high-risk (1).
Describe the stages of the machine learning process you went through as part of this analysis.
1.Data Preprocessing: Handled missing values, encoded categorical variables, and scaled numerical features.
2.Model Selection: Explored multiple classification algorithms including Logistic Regression, Random Forest, and Gradient Boosting.
3.Model Training: Trained the selected models on the training dataset.
4.Model Evaluation: Evaluated models using metrics such as accuracy, precision, and recall on the test dataset.
5.Hyperparameter Tuning: Fine-tuned hyperparameters of the best performing model(s) using techniques like grid search.
6.Model Comparison: Compared the performance of different models to select the best one for deployment.
Briefly touch on any methods you used (e.g., LogisticRegression, or any resampling method).
-Logistic Regression: Used for its simplicity and interpretability.
Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1:
Description of Model 1 Accuracy, Precision, and Recall scores. Logistic Regression
Balanced Accuracy: 0.94 Precision (0): 1.00 Recall (0): 1.00 Precision (1): 0.87 Recall (1): 0.89

Machine Learning Model 2:
Description of Model 2 Accuracy, Precision, and Recall scores. Balanced Accuracy: 0.95 Precision (0): 0.99 Recall (0): 1.00 Precision (1): 0.92 Recall (1): 0.80
Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Which one seems to perform best? How do you know it performs best?
Model 2 has performed better than model 1. Based on the datasets Balanced Accuracy | Precision and Recall for Each Class
Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's? )
Yes, performance depends on the problem at hand. The importance of predicting healthy loans (class 0) versus high-risk loans (class 1) can varied based on the business context.
If you do not recommend any of the models, please justify your reasoning. Recommend both models, no reasoning needed. It is again based on business context.
