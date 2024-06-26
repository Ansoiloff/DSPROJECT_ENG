# Tariff Recommendation

## Project Status: Completed

## Project Description

The mobile operator "Megaline" has found that many customers are using outdated tariff plans. They want to build a system capable of analyzing customer behavior and suggesting a new tariff: "Smart" or "Ultra".

You have at your disposal data on the behavior of customers who have already switched to these tariffs (from the "Statistical Data Analysis" course project). You need to build a classification model that will select the appropriate tariff. Data preprocessing is not required — you've already done it.

Build a model with the maximum accuracy. To pass the project successfully, you need to achieve an accuracy rate of at least 0.75. Check the accuracy on the test dataset yourself.

## Skills and Tools  
pandas
numpy
matplotlib  
seaborn  
DecisionTreeClassifier  
DecisionTreeRegressor  
RandomForestRegressor  
RandomForestClassifier  
LogisticRegression  
LinearRegression  
train_test_split  
mean_squared_error  
accuracy_score  
DummyClassifier  

## Data Description

Each object in the dataset represents information about the behavior of one user for a month. It is known: calls — number of calls,
minutes — total call duration in minutes,
messages — number of SMS messages,
mb_used — internet traffic used in MB,
is_ultra — which tariff was used during the month ("Ultra" — 1, "Smart" — 0).

## Conclusion of the Research
On the test data, the model performs better, confirming the adequacy of our model.  
We examined 3 models (listed them in descending order of model accuracy) \
1. RandomForest  
2. DecisionTree  
3. LogisticRegression    
We evaluated the model on test data (the accuracy was slightly lower than on the validation data, which is normal)
