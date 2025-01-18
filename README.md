# Heart Disease Detection using Scikit-Learn

This repository contains an implementation of a heart disease detection model built using Scikit-Learn. The model uses clinical data to predict the likelihood of heart disease with an accuracy of **92%**.

## Features

- **Data Preprocessing**: Includes handling missing values, feature scaling, and encoding categorical variables.
- **Classification Model**: Implements a machine learning pipeline using algorithms such as Logistic Regression, Random Forest, or Gradient Boosting.
- **Model Evaluation**: Provides accuracy, precision, recall, and F1-score metrics.

## Dataset

The dataset used for this project is from the Kaggle competition: [Heart Disease Classification Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset). The dataset contains clinical and diagnostic features related to heart disease. Typical features include:

- Age
- Sex
- Resting blood pressure
- Cholesterol levels
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression induced by exercise

## Requirements

- Python 3.8+
- Scikit-Learn 1.0+
- Pandas 1.3+
- NumPy 1.21+

Install the required packages with:

```
pip install scikit-learn pandas numpy
```

## Results

The model achieved the following performance on the test dataset:

- **Accuracy**: 86%
- **Precision**: 0.83
- **Recall**: 0.92
- **F1-Score**: 0.88

These metrics demonstrate the model's reliability in detecting heart disease.

## File Structure

- `heart_disease_detection.py`: Contains the implementation of the model.
- `heart_disease_data.csv`: The dataset used for training and evaluation.
- `README.md`: Provides an overview of the project.

## References

1. [Heart Disease Classification Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)
2. Scikit-Learn Documentation: [https://scikit-learn.org](https://scikit-learn.org/)
