

🔐 Proactive Software Defect Prediction Using Ensemble Machine Learning Models

This project implements an intelligent intrusion detection system using machine learning classifiers, including Random Forest, Support Vector Machine (SVM), Naïve Bayes, and a Stacking Ensemble. It incorporates SMOTE for class imbalance handling and performs detailed evaluation using multiple performance metrics. The objective is to proactively detect intrusions with high accuracy and low false detection rates.

📌 Key Features

* ✅ High-accuracy intrusion detection (up to **99.77%** with Random Forest)
* ⚙️ **Ensemble Model** using Stacking Classifier with Logistic Regression as meta-classifier
* ⚖️ **SMOTE** (Synthetic Minority Over-sampling Technique) to balance class distribution
* 📊 Detailed performance evaluation (Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC-AUC)
* 📈 Visualizations for EDA and model comparison
* 💡 Scalable and generalizable for various datasets

🧠 Algorithms Used

* Random Forest Classifier
* Support Vector Machine (SVM)
* Naïve Bayes
* Stacking Ensemble (with Logistic Regression as meta-classifier)
* SMOTE for data balancing

🧰 Technologies & Libraries

* Python
* NumPy, Pandas
* Scikit-learn
* Imbalanced-learn (for SMOTE)
* Matplotlib, Seaborn
* Plotly (optional for interactive visuals)

📂 Project Structure


📁 intrusion-detection-ensemble
│
├── data/
│   └── dataset.csv  # Preprocessed dataset
├── models/
│   └── trained_models.pkl  # Saved models (optional)
├── notebooks/
│   └── exploratory_analysis.ipynb
│   └── model_training.ipynb
├── results/
│   └── confusion_matrix.png
│   └── performance_report.pdf
├── README.md
└── main.py


🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/intrusion-detection-ensemble.git
   cd intrusion-detection-ensemble
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the main file:

   ```bash
   python main.py
   ```

4. Or open the notebooks for step-by-step execution.

📈 Results

| Model             | Accuracy | Precision | Recall | F1-Score |
| ----------------- | -------- | --------- | ------ | -------- |
| Random Forest     | 99.77%   | 1.00      | 1.00   | 1.00     |
| Stacking Ensemble | 99.54%   | 1.00      | 0.99   | 0.99     |
| Naïve Bayes       | 98.57%   | 0.97      | 0.97   | 0.97     |
| SVM               | 96.87%   | 0.74      | 0.94   | 0.83     |

🔬 Future Enhancements

* Integration of deep learning (e.g., LSTM, CNN)
* Real-time intrusion detection via streaming data
* Explainable AI for model interpretability
* AutoML for hyperparameter tuning


