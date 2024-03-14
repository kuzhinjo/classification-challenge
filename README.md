# Classification Example

## Goal: Predict Model Performance
Create and Compare two models on below Dataset Source.
Logistic Regression Vs Random Forests Classifier

Dataset Source: [UCI Machine Learning Library](https://archive.ics.uci.edu/dataset/94/spambase)

## Scale the Features
By using `StandardScaler`, scale the `X_train` and `X_test` DataFrames.

## Create and Fit a Logistic Regression Model
Created a Logistic Regression model, fit it to the training data, made predictions with the testing data, and printed the model's accuracy score.

* Training Data Score: 0.9310144927536231
* Testing Data Score: 0.9278887923544744

## Create and Fit a Random Forest Classifier Model

Created a Random Forest Classifier model, fit it to the training data, made predictions with the testing data, and printed the model's accuracy score.

* Training Data Score: 0.9997101449275362
* Testing Data Score: 0.9278887923544744

## Evaluate the Models

Which model performed better? How does that compare to your prediction? Write down your results and thoughts in the following markdown cell.

### Observations:
In terms of accuracy Random Forest Classifier model is the better one.
However the training Vs testing data score looks good for Logistic Regression Model.

### Next Step:
By considering this, i would like to fine tune the data further for both the models and reassess the solution again.



