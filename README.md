# PRODIGY_DS_03
Task_3:
Question: Build a decision tree classifier to predict whether a customer will purchase a product or service 
based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository

This Python script demonstrates building a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Here's a brief overview:

Data Loading: We imported the necessary libraries and loaded the dataset (Social_Network_Ads.csv) using pandas.

Data Preprocessing: We used Label Encoding from scikit-learn to encode the 'Gender' column into numerical values to make it compatible with the model.

Data Splitting: The dataset was split into features (X) and the target variable (y), and further divided into training and testing sets using train_test_split().

Model Building: We instantiated a DecisionTreeClassifier from scikit-learn and fitted it to the training data using fit().

Model Evaluation: We made predictions on the testing set and evaluated the model's performance using metrics like accuracy, classification report, and confusion matrix.

Visualization: Finally, we visualized the trained decision tree using plot_tree() from scikit-learn and matplotlib.

This script provides a comprehensive workflow for building and evaluating a Decision Tree Classifier for predicting customer purchases.





