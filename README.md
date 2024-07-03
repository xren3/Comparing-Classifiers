# Comparing Classifiers
The purpose of this study was to compare the performance of the following 4 classifier:
- Logistic Regression
- K Nearest Neighbors
- Decision Trees
- Support Vector Machines

The dataset contains marketing data collected by a Portuguese banking institution. The purpose of the campaign is to attract customers who will susbribe to the bank deposits offered. This study aims to identify features of potential customers to make future marketing campaigns more targetted and efficient. The business goal is to maintain the same number of new subscribers while cutting down on number of marketing outreach.

You can find the notebook here: https://github.com/xren3/Comparing-Classifiers/blob/main/practical_application_3.ipynb

## Findings
- The dataset target was very imbalanced. With 88.7% of outreach attempts being 'no' (i.e. failed to attract customer).
- The 4 classifier used to predict the target variable all had a accuracy of around 90%
- The top 5 most important factor for customer conversion were idenfied.
- The highest scoring classifier with the shortest training/fit time was Logistic Regression.
- Support Vector Machine was computationally intensive and not feasible for a dataset of this size

## Future Work
- Simplify data to only include top 5 most important feature
- Use Logistic Regression with weighted classes
