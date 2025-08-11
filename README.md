# Breast Cancer Tumor Staging with Machine Learning

## Project Description

This project develops and compares multiple machine learning models for the staging of breast cancer. By utilizing techniques like SVM, Random Forest, AdaBoost, XGBoost, and ensemble models, it aims to achieve high accuracy and reliability in predicting the stage of breast cancer tumors based on clinical data.

## Models Employed

- **Support Vector Machine (SVM)**
- **Random Forest**
- **AdaBoost**
- **XGBoost**
- **Voting Classifier** (Ensemble approach combining the above models)

## Features

- **Comprehensive Data Preprocessing**: Standardization and cleaning of the dataset to ensure quality inputs for models.
- **Detailed Model Evaluation**: Performance evaluation using accuracy, precision, recall, and F1-score.
- **Hyperparameter Tuning**: Optimization of each model to enhance performance.
- **Ensemble Methods**: Implementation of voting classifiers to leverage the strengths of individual models.

## Usage

Run the script to train the models and output the evaluation metrics:
```bash
python main.py
```

## Detailed Results

The final performance of the models after rigorous training and tuning are summarized as follows:

- **Random Forest**: Achieved an accuracy improvement from 90% to 91% after tuning.
- **SVM**: Improved from 81% to 86% accuracy with parameter tuning.
- **XGBoost**: Consistently performed well with a stable accuracy of 94%.
- **AdaBoost**: Significant improvement from 74% to 88% accuracy post-tuning.

Ensemble methods further enhanced the model's performance:
- **Ensemble with Hard Voting**: Reached up to 96% accuracy on upscaled data.
- **Ensemble with Soft Voting**: Achieved a maximum accuracy of 95% on upscaled data.

The precision, recall, and F1-score across different models indicated a balanced performance, especially in ensembles that effectively handled class imbalances.
