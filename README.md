# Machine Learning for Vector-Borne Disease Prediction

## Overview

This repository contains code and research materials from a collaborative university project exploring machine learning for predicting vector-borne diseases from patient symptom data. The work compares classification models, examines how symptoms influence predictions, and evaluates model behaviour under adversarial attacks.

This is an academic research project, not a clinical diagnostic tool.

## Objectives

- Prepare and explore symptom-based data for disease classification.
- Train and compare machine learning models.
- Interpret model predictions using LIME and SHAP.
- Examine model robustness using adversarial techniques, including FGSM and PGD.

## Dataset

The project uses the publicly available **Vector-Borne Disease Prediction** dataset shared by Richard Bernat on Kaggle. Each record contains binary symptom indicators and a disease label.

[View the dataset on Kaggle](https://www.kaggle.com/datasets/richardbernat/vector-borne-disease-prediction)

Please follow the dataset’s terms of use and cite the original source when reusing it.

## Methodology

1. Checked and prepared the dataset for analysis.
2. Conducted exploratory and statistical analysis of symptoms and disease labels.
3. Trained and evaluated Random Forest, Artificial Neural Network, Decision Tree, XGBoost, and K-Nearest Neighbors models.
4. Compared performance using metrics such as accuracy, precision, recall, F1-score, and confusion matrices.
5. Used LIME and SHAP to examine model predictions and influential symptoms.
6. Applied FGSM and PGD attacks to study the effect of adversarial input changes on model predictions.

## Findings

In the report’s model comparison, XGBoost and Random Forest performed strongly on the test data. The Decision Tree offered a more interpretable set of decision rules, while the adversarial experiments showed that model predictions could be affected by crafted input perturbations.

See the research report and notebooks for detailed results and visualizations.

## Tools and Libraries

- Python
- Pandas and NumPy
- Scikit-learn
- TensorFlow and Keras
- XGBoost
- LIME and SHAP
- Adversarial Robustness Toolbox (ART)

## Installation

Clone your repository and install its dependencies:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
pip install -r requirements.txt
