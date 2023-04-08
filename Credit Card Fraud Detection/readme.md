# Credit Card Fraud Detection Using Machine Learning
This project is a machine learning-based approach to detect credit card fraud. Credit card fraud is a serious issue that can cause financial losses to both individuals and financial institutions. This project aims to provide an automated solution for detecting fraudulent transactions and preventing financial losses.

## Dataset Used
For this project, we used a publicly available dataset that contains credit card transactions made by European cardholders over a two-day period. The dataset contains 492 fraudulent transactions out of a total of 284,807 transactions. The dataset is highly imbalanced, with only 0.172% of transactions being fraudulent.

## Methodology
We used a machine learning approach for credit card fraud detection, with a combination of Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and Logistic Regression classifiers. We trained our models on a subset of the dataset and validated them on a separate subset. We used the F1 score as the evaluation metric for our models, as it is a better metric for imbalanced datasets. We also applied data preprocessing techniques such as scaling and feature selection to improve the performance of our models. 

## Results
Our models achieved an average F1 score of 98% on the test set, which demonstrates the effectiveness of our approach. The KNN and Logistic Regression models performed slightly better than the SVM model. We also calculated the precision, recall, and accuracy metrics for our models, which showed that they can detect fraudulent transactions with high precision and recall.

## Conclusion
This project demonstrates the effectiveness of machine learning-based approaches for credit card fraud detection. Our approach can assist financial institutions in detecting fraudulent transactions accurately and efficiently, which can prevent financial losses. The code and trained models can be found in this repository, along with detailed documentation on how to use them for credit card fraud detection.
