# credit-risk-classification



## **Background**
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## **Instructions**
The instructions for this Challenge are divided into the following subsections:
  * Split the Data into Training and Testing Sets
  * Create a Logistic Regression Model with the Original Data
  * Write a Credit Risk Analysis Report

## **Split the Data into Training and Testing Sets**
Open the starter code notebook and use it to complete the following steps:
  1. Read the <code>lending_data.csv</code> data from the Resources folder into a Pandas DataFrame.
  2. Create the labels set (<code>y</code>) from the “loan_status” column, and then create the features (<code>X</code>) DataFrame from the remaining columns.

> [!NOTE]
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

  3. Split the data into training and testing datasets by using `train_test_split`.

## **Create a Logistic Regression Model with the Original Data**
Use your knowledge of logistic regression to complete the following steps:
  1. Fit a logistic regression model by using the training data (`X_train` and `y_train`).
  2. Save the predictions for the testing data labels by using the testing feature data (`X_test`) and the fitted model.
  3. Evaluate the model’s performance by doing the following:
       * Generate a confusion matrix.
       * Print the classification report.
  4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
























