🔐 Proactive Network Intrusion Detection using Hybrid Machine Learning Models
This project implements a Network Intrusion Detection System (NIDS) using advanced machine learning techniques, aiming to detect and classify malicious network traffic efficiently. The system is designed to proactively identify intrusions based on patterns learned from historical network data.

🚀 Key Features
✅ Data Preprocessing: Null value handling, label encoding, and feature normalization.

✅ Feature Selection: Correlation-based filtering to reduce dimensionality.

✅ Custom Feature Creation: Introduced a Complexity Evaluation metric to classify traffic segments.

✅ Base Models:

Random Forest

Support Vector Machine (SVM)

Naïve Bayes

✅ Stacking Ensemble Classifier: Combines base models with Logistic Regression as the meta-classifier.

✅ Class Imbalance Handling: Applied SMOTE (Synthetic Minority Oversampling Technique) to improve detection of rare attack types.

✅ Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report.

📊 Model Performance
Random Forest Accuracy: 99.77%

SVM Accuracy: 96.87%

Naïve Bayes Accuracy: 98.57%

Stacked Ensemble with SMOTE Accuracy: 99.54%

🧠 Technologies Used

Python 🐍

Scikit-learn

Pandas / NumPy

Imbalanced-learn

Matplotlib / Seaborn

📁 Dataset
Trained and tested on publicly available network intrusion datasets (e.g., NSL-KDD, NSS-KDL, SDN).

📌 Project Goals
Improve detection accuracy for various network intrusions.

Handle imbalanced datasets effectively.

Provide a scalable and extendable intrusion detection architecture.


