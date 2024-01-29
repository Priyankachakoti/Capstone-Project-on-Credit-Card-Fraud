Credit Card Fraud Prediction

problem statament

The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
The dataset presents transactions, where we have 492 frauds out of 284,807 transactions. 

Solution Approch

We start with Exploring the Basic information about the dataset using shape(),info() and head() etc.. Then we are checking for any null values and duplicates in the dataset.
Exploratory Data Analysis to get in-depth data understanding,  We then move to Data preparation where we try to split the data in test, train splits,and apply the standardization required.


we build various models like LogisticRegression, DecisionTree, RandomForest using the imbalanced dataset, where we caluculated the precision_score,f1_score,
recall_score metrics from which we could select the best fit model by comparing and also visualized the three models with a bar plot.

Since the dataset is imbalanced , here we balanced the data by oversampling technique, on which we agin built the models LogisticRegression, DecisionTree, RandomForest. Again we
found metrics recall_score,precision_score,f1_score for all three models and then select the best fir model after comparing all models.We also visualized the Plot the Comparision 
of the Accuracy of Three models.

Libraries used for the Project are:
sklearn, 
NumPy,
pandas,
matplotlib,
seaborn
