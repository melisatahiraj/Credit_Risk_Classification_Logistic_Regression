# Credit Risk Classification Logistic Regression

### Overview
This analysis involves leveraging diverse techniques to develop and assess a model centered on loan risk assessment. Utilizing a dataset containing historical lending data, the objective is to construct a robust model capable of detecting the creditworthiness of borrowers. Through a series of steps including data preprocessing, exploratory analysis, feature selection, model training, evaluation, and interpretation, the analysis aims to create an effective tool for identifying lending risks.

### Results
Based on the classification report, the logistic regression model demonstrates strong performance in predicting both 0 (healthy loans) and 1 (high-risk loans). It significantly excels in detecting healthy loans, with a precision of 1.00 and a recall of 0.99, implying its consistent ability to identify the vast majority of healthy loans with rare misclassifications. Conversely, while maintaining high accuracy, it also effectively anticipates high-risk loans, with a precision of 0.85 and a recall of 0.91. While it's not as accurate at identifying high-risk loans as it is at spotting healthy ones, this indicates that the model still has some capability in recognizing them.

### Summary
The machine learning model, particularly utilizing logistic regression, has yielded promising results for loan risk assessment. It demonstrates strong performance in identifying both healthy and high-risk loans, with high precision and recall scores.

## Requirements

### Split the Data into Training and Testing Sets

* Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
* Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
* Split the data into training and testing datasets by using train_test_split.

### Create a Logistic Regression Model

* Fit a logistic regression model by using the training data (X_train and y_train).
* Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
* Evaluate the model’s performance by doing the following:
    * Generate a confusion matrix.
    * Generate a classification report.
    * Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

### Write a Credit Risk Analysis Report

* Provide an overview that explains the purpose of this analysis.
* Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model.
* Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


## References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
