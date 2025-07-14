# Health Insurance cost prediction with GUI interface 

In this notebook, I model the Health Insurance Costs of 1338 Americans with health insurance and used this data to predict the cost for a new client.

The data is from the pycaret library. This library is a fantastic source of datasets and classification and regression models. In this notebook, I compared 7 models, Linear Regression, Lasso, Ridge, XGBoost, Decision Tree, RandomForest and ExtraTree.
With Pycaret, you can compare 10 or more models at the same time, I choose not to do this for this notebook because it takes away the fun when the program does it all for you.

I have also included a GUI interface for the user to imput thier own data and calculate the expected insurance cost.


![Screenshot from 2023-02-08 15-33-33](https://user-images.githubusercontent.com/105222741/217563355-865c6180-233c-4288-b010-6ef32a2fb753.png)

Run the notebook and then run the last cell. The GUI will open and then input the information and the model will return the your health insurance predicted cost.

The Data used to train the model is from the USA and the price is in USD. Let us be thankful we dont have to pay such costs here in Germany.

