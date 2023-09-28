# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The Purpose of this Analysis is to use various techniques to train and evaluate a model based on loan risk. Using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
* I will be using a machiene learning process to determine which loans are high risk and which are low risk.
* Some variables I used in this code were value_counts whichcounts the unique values from the dataframe and then returns the code in descending order, since it has a categorical variable.
My X_train and y_train are used to make predictions and to train the machine learning model.
The confusion Matrix is a table in classification tasks to evaluate the performance from the machine learning model, it gives a summary of model's predictions.
random_state controls the randomness in my algorithm.
* I had to split the data into training and testing sets and first read the CSV file and put it into a Pandas DataFrame. Then Check the balence of the target values and then created a Logistic Regression Model. Finally I evaluated the model's performance.
* LogisticRegression is used for classification tasks in the field of machiene learning and statistics. Usually also used to predict one of two possible outcomes.

## Results


* Machine Learning Model 1:
  * The Logistic Regression Model predicted a 95% accuracy score which is a good preformed model from the accuracy score being so high. It also shows a 100% accuracy for the healthy loans and 85% for high-risk loans.


* Machine Learning Model 2:
  * The logistic model also fit well with the model with having a 99% accuracy score. With 100% healthy loans and 84% high-risk loans.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
The Machine LEarning Model 1 performed better as it produced a higher accuracy score of 99% compared to 95% accuracy from Machine Learning Model 1.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
It is more imporatant to predict the 1's with the healthy loans as if it has a higher accuracy score it makes it more safe and reliable to go with.
