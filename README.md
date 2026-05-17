# AI_ML_Practical_Application-3
Comparing Classifiers for Bank Churn Prediction
This repository is providing solution for "Comparing Classifiers" practical application. The purpose of this is to compare the performance of several different machine learning classifiers when given a set of banking marketing data.

The main deliverables of this are a Jupyter notebook containing a statement of the business problem, inferential and descriptive statistics, findings, next steps, and recommendations.
Find solution in jupiter notebook attached in main branch - [practical_appllication_3.ipynb.](https://github.com/sindhujasekar-dev/AI_ML_Practical_Application-3/blob/main/practical_appllication_3.ipynb)

OBSERVATION:

| Model    | Test Accuracy | Train Accuracy | Time  |
| -------- | ------------- | -------------- | ----- |
| Logistic | 0.870         | 0.871          | 0.21s |
| KNN      | 0.853         | 0.860          | 5.77s |
| SVM      | 0.870         | 0.871          | 33s   |
| DTC      | 0.866         | 0.875          | 0.05s |

All models perform similarly, but Logistic Regression gives best trade-off.

The performance of all models is relatively similar, with test accuracies ranging between 0.85 and 0.87. Logistic Regression and SVM achieved the highest test accuracy (0.8704), while Decision Tree Classifier performed slightly lower but with significantly faster training time. KNN showed the lowest performance and the highest computational cost during training.

Although SVM matches Logistic Regression in accuracy, it requires much longer training time, making it less efficient for this dataset. Decision Tree Classifier is extremely fast but may lack robustness compared to other models. KNN is the least efficient in terms of both accuracy and speed.

Based on these results, Logistic Regression is the most balanced model, offering strong accuracy with fast training time and good generalization. Therefore, it is the recommended model for this dataset due to its efficiency and stability.
