# disease-prediction-using-ml(parkinson)

🧠 Project Overview

This project builds a Parkinson’s Disease prediction system using biomedical voice measurements.
It uses an SVM (Support Vector Machine) classifier to predict whether a person may have Parkinson’s disease based on several vocal features.

The system includes:
Data preprocessing
Feature analysis
Model training
Evaluation

Final prediction interface inside the notebook

📂 Dataset
The dataset used is the UCI Parkinson’s Disease Dataset, which contains biomedical voice measurements from healthy and Parkinson’s patients.

🔗 Dataset Link:
https://archive.ics.uci.edu/ml/datasets/Parkinsons

Dataset Info:

Rows: ~195
Columns: ~24

Features include jitter, shimmer, HNR, NHR, PPE, etc.


⚙️ Workflow Summary

1. Load and Explore Data

Load data using Pandas
Check missing values
Explore feature distribution

2. Preprocessing
   
Normalize/scale the features
Separate input features and output label

4. Model Used — SVM

The project uses Support Vector Machine (SVM)
Kernel:(linear)
Best suited for smaller structured datasets
Handles classification boundaries well

4. Model Evaluation

The SVM achieved an accuracy of:
🎯 Model Accuracy: 87%

Additional metrics like confusion matrix and classification report can be generated, depending on your notebook.


▶️ How to Run the Notebook

Install required libraries:

pip install pandas numpy scikit-learn matplotlib

Open the notebook:

jupyter notebook parkinson-detection-testing-predictive-system.ipynb

Run all cells to:

Preprocess data

Train SVM model

Test model

View accuracy

📁 Project Structure
│── parkinson-detection-testing-predictive-system.ipynb
│── README.md
└── dataset (download from UCI)

📝 Author

Aster Noronha
