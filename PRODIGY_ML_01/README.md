# House Price Prediction using Different Regression Models

(This is the Task -01 of the PRODIGY InfoTech Internship.)

### In this project, we predict the house prices using many features available in the data.

Firstly, we deal with the missing data by dropping features and imputing values.

Then, we scale our input using Satndard Scaler()

Since the regression models need the features to be in numerical format, we convert the categorical data into numbers using LabelEncoder()

Then, we initialize many regression models and train to find the scores.

Finally, the model which gave the best score is used to find the predictions.

(Note: The prediction have to be inverse transformed to get the actual house prices.)