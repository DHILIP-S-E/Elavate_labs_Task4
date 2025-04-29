Task 4
 Social Network Ads Dataset
Project Title:
User Purchase Prediction from Social Ads using Logistic Regression

Objective:
To classify whether a user will purchase a product based on Age and Estimated Salary.

Dataset Overview:
📁 File: Social_Network_Ads.csv

🔢 Target Variable: Purchased (0 = Not Purchased, 1 = Purchased)

⚙️ Features Used: Age, EstimatedSalary
(Ignore: User ID, Gender for simplicity)

Workflow:
Load dataset and extract relevant columns

Split into training/testing sets

Apply feature scaling

Train Logistic Regression model

Evaluate:

Confusion Matrix

Accuracy, Precision, Recall

ROC Curve and AUC Score

Tune threshold manually (0.3, 0.5, 0.7)

Visualize sigmoid function for concept clarity

Key Results:

Metric	Score (Example)
Accuracy	0.85
Precision	0.79
Recall	0.71
ROC-AUC	0.90
Sigmoid Explanation:
The sigmoid function maps the output of the model to a probability between 0 and 1, allowing you to assign class labels based on a chosen threshold.

