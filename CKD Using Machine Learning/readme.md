# Chronic Kidney Disease Detection Using ML
Chronic kidney disease (CKD) is a common health problem that affects millions of people worldwide. Early detection and timely treatment are crucial for managing CKD and preventing its complications. This project uses machine & deep learning algorithms to detect chronic kidney disease. The model achieves a classification accuracy of 98% by applying cross-validation on Random Forest, SVM, and Decision Trees, and applying feed-forward neural networks (FFNNs).

## Requirements
- Python 3.6 or above
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Keras

## Code and Resources Used
- **Programming Language:** Python 3.9
- **Packages:** NumPy, Pandas, Matplotlib, Seaborn, TensorFlow & Keras
- **Optimization Approaches:** Adam (Adaptive Moment Estimation)
- **Loss Functions:** Categorical Crossentropy (CCE)

## Methodology
We used a dataset of 400 patients with CKD and 150 patients without CKD to train and evaluate our model. We performed extensive data preprocessing, including handling missing values, scaling the features, and encoding categorical variables. We then applied three machine learning algorithms to build our CKD detection model: Random Forest, Support Vector Machines (SVM), and Decision Trees. We evaluated the performance of each model using cross-validation and measured its accuracy, precision, recall, and F1-score. We also created a Receiver Operating Characteristic (ROC) curve to assess the tradeoff between sensitivity and specificity.

## Results
Our results showed that all three machine learning algorithms performed well in predicting the presence of CKD, with an accuracy of 98% for the Random Forest model, 95% for the random forest model, and 97% for the FFNN model. The Random Forest model had the highest precision and F1-score, while the SVM model had the highest recall.
