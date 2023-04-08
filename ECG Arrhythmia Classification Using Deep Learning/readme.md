# ECG Arrhythmia Classification using Deep Learning
This project is a deep learning-based approach to classify Electrocardiogram (ECG) beats into 5 different classes. ECG is a vital test to diagnose and monitor heart conditions, and the classification of ECG beats can assist medical professionals in diagnosing cardiac arrhythmias.

## Dataset
For this project, we used the internationally recognized "MIT-BIH Database" for ECG Arrhythmia Classification. This dataset contains 48 half-hour ECG recordings and annotations for over 100,000 individual beats. The dataset is widely used for benchmarking ECG classification algorithms.

## Tools Used
- Python 3.9
- Machine Learning libraries like sckit-learn
- Deep Learning frameworks like TensorFlow & Keras
- Visualization libraries like seaborn matplotlib
- Mathematical & data manipulation libraries like NumPy & Pandas

## Methodology
We used a deep learning approach for ECG classification, with a combination of Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. The CNNs were used to extract features from the ECG signals, and the LSTM network was used to capture temporal dependencies in the signals. We trained our model on a subset of the MIT-BIH dataset and validated it on a separate subset. We used the categorical cross-entropy loss function and Adam optimizer for training the model. We also applied data augmentation techniques such as flipping and rotating the ECG signals to improve the model's robustness.

## Results
Our model achieved an accuracy of 98% on the test set, which demonstrates the effectiveness of our approach. The classification accuracy of different classes is also impressive, with the highest accuracy achieved for the Normal class and the lowest for the Other class.

## Conclusion
This project demonstrates the effectiveness of deep learning-based approaches for ECG arrhythmia classification. Our approach can assist medical professionals in diagnosing cardiac arrhythmias accurately and efficiently. The code and trained model can be found in this repository, along with detailed documentation on how to use the model for ECG classification.
