# Housing-Saleprice-Prediction-Regression

Author : Prasad Patharvat

Algoritm used :

Linear regression

Decision Tree

Random forest

Adaboost Regressor

Artificial Neural Network

Goal
It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

IDE: Jupyter Notebook

Language: Python 3

Libraries used : Pandas , Numpy , Sk-learn , Tensorflow , Keras

Problem Statement:
Goal
It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

Data:

Overview of the data

The next step is to look at the data we’re working with. Realistically, most of the data we will get, even from the government, can have errors, and it’s important to identify these errors before spending time analyzing the data. Normally, we must answer the following questions:

• Do we find something wrong in the data?

• Are there ambiguous variables in the dataset?

• Are there variables that should be fixed or removed? Project Summary :

• Predicted loan Eligibility by starting with Logistic Regression to Artificial Neural Network as loan status column is categorical (YES/NO).

• Made some plots for showing the relation between them all the columns which we will take as a predictors.

• Applied StandardScaler on the dataset for conversion the higher magnitude value to standard magnitude values with the One hot encoding in the categorical data of independent feature & Label Encoding on dependent feature.

• Statistical test like ANOVA, Chi-square test are performed for feature selection, After performed all the operations used grid search cv technique to get the best parameters by using most classification and regression algorithms.

• On regression analysis have all the preprocessed columns again apply best columns for loan amount predictions.

• Got the lesser mean absolute error for the regression analysis. We are taking all the predicted (yes) columns will take in the regression analysis also used the same data from testing set

• Performed processes before training the model that is data profiling, data preprocessing and exploratory data analysis

• Applied Linear Regression, Decision tree, AdaBoost and Random forest to compare between models and to obtain better accuracy.

• Predicted Sale Price.
