# attrition-classification
A comparison of three different binary classification models for prediction of employee attrition. 


# Summary
This notebook exhibits a comparison between the following models implemented through <b>scikit-learn</b> on a dataset that provides the information of employee attrition for an anonymous company.
*   Logistic regression
*   Random Forest Classifier
*   Neural Network

# About the data

The dataset consists of 32 usable features and the records of 1472 employees.

Upon performing exploratory analysis on the data, it was observed that there were two main types of features: 1) Normal scaling integer features 2) Categorical features

The following steps were carried out in order to bring the data into usable format:

1. Performing one-hot-encoding on the categorical and string features to convert them into multiple features with binary values(intuitively was better upon looking at what exactly the features entail rather than having a single feature with multiple classes).

2. Ran the models on the datasets before and after normalizing the dataset (using z-score normalization) and compared performance.

3. Split the data in 65:35 ratio for training and testing.
