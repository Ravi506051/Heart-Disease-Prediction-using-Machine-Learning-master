# Heart Disease Prediction Using Machine Learning

A binary-classification project exploring machine-learning methods for analysing structured heart-disease data.

## Models Explored
The project documentation describes experiments with Logistic Regression, Naive Bayes, Support Vector Machines, K-Nearest Neighbours, Decision Trees, Random Forest, XGBoost, and a small neural network.

## Workflow
1. Load and inspect the dataset.
2. Clean the data and prepare model features.
3. Split data into training and test sets.
4. Train and compare classification algorithms.
5. Evaluate with precision, recall, F1-score, ROC-AUC, and a confusion matrix.
6. Review errors and document model limitations.

## Technology
Python · Pandas · NumPy · Scikit-learn · Keras · Jupyter Notebook

## Getting Started
```bash
git clone https://github.com/Ravi506051/Heart-Disease-Prediction-using-Machine-Learning-master.git
cd Heart-Disease-Prediction-using-Machine-Learning-master
```
Open the notebook in Jupyter or Google Colab and install the libraries imported by the notebook.

## Evaluation and Responsible Use
Use a clearly separated test set and check for data leakage before reporting metrics. For imbalanced data, inspect class-wise precision and recall rather than relying on accuracy alone. This is an educational project, not a medical diagnostic system; its predictions must not guide clinical decisions. Reproduce any performance figure on a documented test split before quoting it.

## Future Improvements
Add cross-validation, calibration analysis, explainability, and a model card describing dataset provenance and intended use.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)

## Reproduce the notebook

The repository contains `Heart_disease_prediction.ipynb` and `heart.csv`. Open the notebook in Jupyter or Google Colab from this folder so its relative `pd.read_csv("heart.csv")` path resolves. It compares Logistic Regression, Naive Bayes, linear SVM, KNN, Decision Tree, Random Forest, XGBoost, and a small Keras neural network.

Install the libraries imported by the notebook if they are not already available. Compare models on the same documented split, and do not treat accuracy from this small dataset as evidence of clinical performance. This project is educational and is not a diagnostic tool.
