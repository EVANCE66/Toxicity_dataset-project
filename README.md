Toxicity Prediction Using Machine Learning
Overview

This project builds a machine learning model to classify chemical compounds as Toxic or Non-Toxic using molecular descriptor features. The workflow includes EDA, preprocessing, feature selection, handling class imbalance with SMOTE, and training an ensemble model (Random Forest).

Dataset

Target column: Class

Classes: Toxic / NonToxic

Features: Numerical molecular descriptors (e.g., MDEO-22, MATS3v, AATSC1c)

Workflow

Exploratory Data Analysis (EDA) – dataset inspection, missing values, class distribution, correlation heatmap

Preprocessing – feature/target separation and label encoding

Feature Selection – Random Forest feature importance

Handling Imbalance – SMOTE applied within a pipeline

Model Training – Random Forest classifier

Evaluation – 5-fold cross-validation and classification metrics

Example Results
precision    recall  f1-score   support

0       0.69      0.92      0.79        24
1       0.33      0.09      0.14        11

accuracy                           0.66        35
Tools

Python, Pandas, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn

How to Run
pip install -r requirements.txt
jupyter notebook
Author

Evance Omondi
