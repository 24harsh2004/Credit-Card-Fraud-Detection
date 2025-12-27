**Project Overview**

Credit card fraud is a major issue in financial systems, causing huge monetary losses every year. This project focuses on detecting fraudulent credit card transactions using unsupervised and semi-supervised machine learning algorithms, which are effective when labeled fraud data is limited or highly imbalanced.

The goal is to accurately identify anomalous transactions that deviate from normal user behavior.

**Objectives**

Detect fraudulent transactions from credit card data

Handle highly imbalanced datasets

Compare performance of different anomaly detection algorithms

Improve fraud detection accuracy while minimizing false positives

**Machine Learning Models Used**

The following classifiers were implemented and evaluated:

Isolation Forest

One-Class Support Vector Machine (SVM)

Local Outlier Factor (LOF)

**Dataset**

link- (https://drive.google.com/file/d/1lSELd5KIuwSD8jZgj94chlMyJpksewAL/view?usp=drive_link)

Publicly available Credit Card Transactions Dataset

Contains numerical features obtained after PCA transformation

Highly imbalanced with very few fraudulent cases compared to normal transactions

Technologies & Tools

Programming Language: Python

**Libraries:**

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

 **Methodology**

Data loading and preprocessing

Exploratory Data Analysis (EDA)

Handling class imbalance

Training anomaly detection models

**Model evaluation using:**

Accuracy

Precision

Recall

F1-score

Performance comparison between models

 **Results**

Isolation Forest showed strong performance in detecting anomalies efficiently.

One-Class SVM performed well but required careful tuning.

Local Outlier Factor effectively identified local anomalies in transaction patterns.

The results demonstrate that unsupervised learning techniques are effective for real-world fraud detection problems.


 **Future Improvements**

Apply deep learning–based anomaly detection techniques

Hyperparameter optimization for better performance

Real-time fraud detection using streaming data

Deployment using Flask or FastAPI

 **Author**

Harsh Agarwal
B.Tech – Artificial Intelligence & Machine Learning
