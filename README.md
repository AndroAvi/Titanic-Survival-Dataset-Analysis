# Titanic-Survival-Dataset-Analysis

A project depicting the analysis of the Titanic Dataset available at :
https://www.kaggle.com/c/titanic

The "Titanic-Machine Learning from Disaster" competition is an introductory kaggle competition for getting started with machine learning.

This relatively small dataset expemplifies many of the practical problems that one deals with while doing machine learning projects, namely:
1. Correlated Data
2. Missing Values
3. Different kinds of features-categorical, ordinal, numeric, alphanumeric, as well as textual.
4. Outliers

My goal here is to present and implement various methods of understanding the information contained inside the dataset that I've learnt through numerous books and courses.

In many ways, this is the first project that I'm doing to showcase the practices.

The notebook contains the following files:
1. training_data.csv : The training data which I've analyzed.
2. test_data.csv: The test data to train the classifier model on.
3. ground_truth.csv: The actual class labels for test_data.csv for confidence and accuracy score calculation.
4. titanic_survival.csv: The ipython shell or jupyter notebook which consists of explanation and code in python.


As of now, I've managed to:
1. Clean the dataset by removing useless and missing values.
2. Visualized individual features' correlation with the label.
3. Plotted some clear biases to survival.
4. Converted non numerical categorical features into numerical ones.
5. Started attempt on conversion of some features into categorical based on it's correlation with survival.

What remains to be done:
1. Finishing the data wrangling part.
2. Training various models and comparing their accuracy.
