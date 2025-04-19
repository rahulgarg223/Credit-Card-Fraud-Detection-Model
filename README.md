# Credit Card Fraud Detection

A machine learning-based project to detect fraudulent credit card transactions using real-world datasets and classification models.

## Table of Contents
### Overview

### Dataset

### Installation

### Usage

### Modeling Approach

### Results

### Technologies Used

### Contributing

##3 License

## Overview
Credit card fraud detection is crucial for financial institutions and customers alike. In this project, we build and evaluate machine learning models to classify transactions as fraudulent or legitimate. The key challenge tackled here is the extreme class imbalance in the dataset.

## Dataset
Source: Kaggle - Credit Card Fraud Detection

### Details:

Transactions made by European cardholders in September 2013.

Contains 284,807 transactions with 492 frauds (0.172%).

Features are PCA-transformed (V1 to V28), plus Time, Amount, and Class.

##  Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
### Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
##  Usage
Run the main script:

bash
Copy
Edit
python main.py
Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Fraud_Detection.ipynb
You can modify the notebook to explore data, train models, and visualize results.

## Modeling Approach
Data Preprocessing:

Normalized the Amount feature.

Dropped Time as it was not informative.

Handled class imbalance using:

Under-sampling

SMOTE (Synthetic Minority Oversampling Technique)

## Models Implemented:

### Logistic Regression

### Decision Tree

### Random Forest

## Evaluation Metrics:

Confusion Matrix

Precision, Recall, F1-Score

AUC-ROC Curve

## Results

#### Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
#### LogisticRegression	99.3%	82.1%	91.4%	86.5%	0.973
#### RandomForest	99.9%	92.7%	95.6%	94.1%	0.988

Best performance achieved with RandomForest.

## Technologies Used
Python

Scikit-learn

Pandas

NumPy

Matplotlib / Seaborn

XGBoost

Jupyter Notebook

## Contributing
Contributions are welcome! Please fork the repo and submit a pull request with improvements or bug fixes.

## License
This project is licensed under the MIT License.
