# Bank Term Deposit Subscription Prediction

## Overview

This project explores the use of supervised machine learning to predict whether a bank customer will subscribe to a term deposit following a marketing campaign.

Using the Bank Marketing dataset, the project investigates customer demographics, financial characteristics and campaign interactions, comparing Logistic Regression and Random Forest classification models.

## Objectives

- Perform exploratory data analysis (EDA) to identify patterns in customer subscription behaviour.
- Clean and preprocess numerical and categorical features.
- Train and evaluate classification models.
- Compare model performance using precision, recall, F1-score and ROC-AUC.
- Apply hyperparameter tuning and assess its impact on model performance.
- Discuss class imbalance, model limitations and ethical considerations.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Imbalanced-learn

## Methodology

1. **Exploratory Data Analysis:** Investigated subscription rates, demographic characteristics, financial indicators and campaign interactions.
2. **Data Preprocessing:** Applied categorical encoding and numerical feature scaling through a preprocessing pipeline.
3. **Model Development:** Built Logistic Regression and Random Forest classifiers.
4. **Model Evaluation:** Compared classification reports, confusion matrices and ROC curves.
5. **Hyperparameter Tuning:** Used GridSearchCV with five-fold cross-validation and macro F1-score to select model parameters.

## Key Findings

- The target variable was imbalanced: approximately 88.48% of customers did not subscribe, compared with 11.52% who did.
- Call duration was an important predictor of subscription behaviour.
- The initial Random Forest model achieved an ROC-AUC of approximately 0.903.
- Hyperparameter tuning produced only modest improvements, highlighting the difficulty of identifying the minority class.

## Limitations

Both models performed considerably better at identifying non-subscribers than subscribers. This demonstrates why accuracy alone is insufficient when evaluating imbalanced classification problems.

Further work could investigate class-weighted models, alternative boosting algorithms, feature engineering and model explainability techniques.

## Dataset

The project uses the Bank Marketing dataset associated with the UCI Machine Learning Repository.

Dataset source: https://archive.ics.uci.edu/dataset/222/bank+marketing

Please refer to the original dataset documentation and licence or usage terms before redistributing the data.

## Reproducibility

1. Clone or download this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open `notebooks/MachineLearningAnalysis.ipynb`.
4. Run the notebook cells in order.

## Skills Demonstrated

Exploratory data analysis, data preprocessing, classification, feature analysis, model evaluation, hyperparameter tuning and critical assessment of machine learning limitations.