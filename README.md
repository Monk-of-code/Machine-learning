# Machine-learning
Logistic Regression
This code challenge involves implementing logistic regression for a classification problem using Python. 
Data Cleaning Function:
The function data_cleaning replaces missing values denoted by '?' with NaN, imputes missing values with mean for numeric columns, and with the most frequent value for non-numeric columns. It then returns a list of unique values in the specified column
.
Data Preprocessing Function:
The data_preprocess function converts non-numeric data to numeric using LabelEncoder, drops specific features, converts the DataFrame to a NumPy array, standardizes the features using MinMaxScaler, and splits the data into training and testing sets using train_test_split
.
Training the Model:
The train_model function fits a logistic regression model to the training data using the solver 'lbfgs'
.
Testing the Model:
The AUC - ROC curve function is intended to calculate the Area Under the Receiver Operating Characteristic Curve (AUC-ROC), which is a performance metric for classification models. It evaluates the model's ability to distinguish between classes at different threshold settings
.
These functions aim to preprocess the data, train a logistic regression model, and evaluate its performance using the AUC-ROC curve.
