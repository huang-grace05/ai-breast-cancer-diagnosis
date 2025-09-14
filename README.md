# Breast Cancer Diagnostic Using Machine Learning

## Overview

This project uses machine learning to predict whether a breast tumor is malignant (cancerous) or benign (non-cancerous) based on various measurements of the tumor. The goal is to provide an accurate and efficient tool to assist in breast cancer diagnosis.

## Project Details

- Data is preprocessed by cleaning unnecessary columns and converting diagnosis labels to binary numeric values.
- Key features related to tumor size, shape, and texture are selected for prediction.
- The dataset is split into training and testing sets.
- A machine learning model is trained on the training data.
- Model performance is evaluated using confusion matrix, precision, recall, and accuracy metrics.

## Files

- `breast_cancer_diagnostic.ipynb` - The Jupyter notebook with all the code and explanations.
- `data.csv` - The UCI Breast Cancer Wisconsin (Diagnostic) Data Set used for training and testing (note: due to privacy and licensing, the dataset needs to be downloaded separately).

## How to Use

1. Clone or download this repository.
2. Ensure you have Python installed with necessary libraries: pandas, numpy, matplotlib, scikit-learn.
3. Run the Jupyter notebook to see the full workflow of data preprocessing, training, and evaluation.
4. Modify or extend the notebook as desired for experimentation.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
