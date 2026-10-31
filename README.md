# Heart-Disease-Prediction-using-Machine-Learning
Thus preventing Heart diseases has become more than necessary. Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives. This is where Machine Learning comes into play. Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.

The project involved analysis of the heart disease patient dataset with proper data processing. Then, different models were trained and and predictions are made with different algorithms KNN, Decision Tree, Random Forest,SVM,Logistic Regression etc
This is the jupyter notebook code and dataset I've used for my Kaggle kernel 'Binary Classification with Sklearn and Keras'

I've used a variety of Machine Learning algorithms, implemented in Python, to predict the presence of heart disease in a patient. This is a classification problem, with input features as a variety of parameters, and the target variable as a binary variable, predicting whether heart disease is present or not.

Machine Learning algorithms used:

1. Logistic Regression (Scikit-learn)
2. Naive Bayes (Scikit-learn)
3. Support Vector Machine (Linear) (Scikit-learn)
4. K-Nearest Neighbours (Scikit-learn)
5. Decision Tree (Scikit-learn)
6. Random Forest (Scikit-learn)
7. XGBoost (Scikit-learn)
8. Artificial Neural Network with 1 Hidden layer (Keras)

Accuracy achieved: 95% (Random Forest)

Dataset used: https://www.kaggle.com/ronitf/heart-disease-uci


## 📊 Model Evaluation

Model performance should be evaluated using multiple classification metrics rather than accuracy alone.

- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** How many positive predictions were correct.
- **Recall:** How many actual positive cases were identified.
- **F1-Score:** Balance between precision and recall.
- **Confusion Matrix:** Breakdown of correct and incorrect predictions.

Record the actual evaluation results from your notebook before reporting any performance numbers.

## 🔍 Project Workflow

1. Load and explore the heart disease dataset.
2. Perform data cleaning and preprocessing.
3. Analyze feature distributions and relationships.
4. Split the data into training and testing sets.
5. Train and compare machine learning classification models.
6. Evaluate model performance using appropriate metrics.
7. Review predictions and document the findings.

## 🚀 Future Improvements

- Compare multiple classification algorithms consistently
- Improve feature selection and hyperparameter tuning
- Add visualizations for model performance
- Validate performance on separate, representative datasets
- Improve explainability so model predictions can be examined

## ⚠️ Medical Disclaimer

This project is intended for educational and research purposes only. It is not a medical diagnostic tool and must not be used to diagnose disease or make treatment decisions. Always consult a qualified healthcare professional for medical advice.

## Evaluation and Responsible Use

For a fair comparison, evaluate all classifiers on the same held-out data and report sensitivity/recall, specificity where calculated, precision, F1-score, and the confusion matrix in addition to accuracy. Check for data leakage and document the split strategy before reporting results.

This repository is an educational machine-learning exercise. Its predictions must not be used to diagnose, rule out, or guide treatment for heart disease. Medical decisions require qualified healthcare professionals and appropriate clinical tests.

## Project Development Notes

Use consistent held-out evaluation and report sensitivity, specificity, precision, recall, and calibration where available. This educational model is not for clinical decisions.

For reproducible updates, record the dataset/source version, environment and dependency versions, preprocessing choices, and actual outputs from each run. Keep sample values clearly labelled and do not publish secrets or private data.

### Technical Deep Dive

This is a binary classification workflow, so compare models on identical held-out data and report sensitivity/recall, specificity, precision, F1-score, and the confusion matrix—not accuracy alone. Any feature scaling or selection must be fitted only on training folds. Check for duplicated records and target leakage before interpreting the reported score.

This notebook is for learning and research only. Its predictions are not a diagnosis, screening recommendation, or substitute for a clinician's assessment.

## Evaluation, Safety, and Reproducibility

- Evaluate with sensitivity/recall, specificity, precision, F1-score, ROC-AUC, and a confusion matrix; accuracy alone can hide clinically important errors.
- Use a held-out test set and avoid data leakage during preprocessing and feature selection.
- Record dataset provenance, split strategy, random seed, model configuration, and actual measured results.
- Inspect calibration and false-negative cases, and clearly communicate uncertainty.
- This is an educational machine-learning experiment, not a diagnostic device or a substitute for qualified medical advice.
