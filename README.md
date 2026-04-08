# Loan-Approval-Machine-Learning-Programme

# Tool and packages used:

- Python: Pandas, Numpy, Scikit-Learn, Plotly.
- Google Colab

# Description:

This project explores the usage of machine learning models to predict a bank's ability to classify a person's loan eligibility. A person can either be accepted or denied. Three classifiers; Logistic Regression, Naive Bayes, and Random Forest were implemented on a cleaned bank customer dataset with over 55,000 instances. The training testing split was 80:20. The aim was to identify which model's metrics best matched our success criteria. 

Random Forest was the best performing classifier with metrics that aligned the closest to our criteria. GridSearchCV was applied to the Random Forest model to estimate what parameters were optimal. The optimised model was similar in performance metrics to the first Random Forest, so I ultimately decided against using it. 

Once the accepted borrowes were classified, their maximum loaned amount was next to predict. I built two decision trees with different input variables. The tree with the stronger metrics was pruned. I input values into the pruned tree to obtain a maximum loan amount prediction.
