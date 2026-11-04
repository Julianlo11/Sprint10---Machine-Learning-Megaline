Megaline | Mobile Plan Recommendation

Project Overview

This project was developed for Megaline, a telecommunications company that wants to recommend one of its two new mobile plans, Smart or Ultra, to customers who are still using legacy plans.

The objective was to develop a machine learning classification model capable of predicting the most suitable plan based on customer behavior and monthly usage patterns.

Business Objective

Build a classification model that analyzes customer usage data and recommends the appropriate mobile plan.

The model must achieve an accuracy greater than or equal to 75% to meet the project's performance requirement.

Dataset

The project uses users_behavior.csv, which contains customer usage information.

Feature

Description

calls

Number of calls

minutes

Total call duration

messages

Number of messages sent

mb_used

Internet data consumption

is_ultra

Target variable: 1 = Ultra, 0 = Smart

Methodology

The project followed these steps:

Data Exploration: Examined the dataset, data types, missing values, duplicates, and target distribution.

Data Splitting: Divided the data into training (60%), validation (20%), and testing (20%) sets.

Model Training: Developed and evaluated three classification algorithms:

Decision Tree Classifier

Random Forest Classifier

Logistic Regression

Hyperparameter Tuning: Compared model performance using validation accuracy.

Final Evaluation: Retrained the best-performing model using training and validation data, then evaluated it on the test set.

Sanity Check: Compared the final model against a Dummy Classifier baseline.

Model Performance

Validation Results

Model

Accuracy

Random Forest

82.12%

Decision Tree

80.25%

Logistic Regression

73.87%

Random Forest achieved the highest validation accuracy and was selected as the final model.

Final Test Results

Model

Test Accuracy

Random Forest

82.89%

Dummy Classifier

69.36%

The final model exceeded the required accuracy threshold of 75% and improved performance by 13.53 percentage points compared with the baseline.

Business Conclusion

The project successfully developed a machine learning model capable of recommending Megaline's Smart or Ultra plans based on customer usage patterns.

The Random Forest classifier achieved 82.89% accuracy on unseen test data, demonstrating its ability to identify patterns in customer behavior and outperform a simple baseline prediction.

From a business perspective, this model can support Megaline's commercial strategy through more personalized plan recommendations, customer segmentation, and data-driven decision-making.

Before implementation in a real business environment, the model should be validated with new customer data and monitored to ensure its performance remains consistent.

Technologies

Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook

Git & GitHub

Author

Julian Lopez
Economics Graduate | Data Science & Business Analytics

GitHub Profile
