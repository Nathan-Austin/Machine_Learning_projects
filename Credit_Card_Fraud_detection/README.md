# Credit Card Fraud Detection

In this notebook, I developed a simple credit card fraud detection model that predicts if a transaction is fraudulent.

Because the data set is highly unbalanced, I decided to test both under sampling and over sampling methods.
Under sampling with Linear Regression provided an accuracy of 93.68, which is quite good. 
But over sampling with Random Forest provided a much better result.

Accuracy of 99.99
Precision of 99.98
Recall of 1.0
f1 score of 99.99

I A-B tested using different classification models which were LinearRegression, DecisionTree and RandomForest.


The data is from [this kaggle dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

I have also included a GUI interface for the user to imput thier own data and check if transactions on their card are fraudulent.

Run the notebook and then run the last cell and input information about your last transactions and the model will return if a selected transaction is fraudulent.


