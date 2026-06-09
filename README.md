# SVHN Digit Classification: SVM Baseline vs Deep CNNs

This is a portfolio-ready computer vision project that classifies real-world digit images from the Street View House Numbers (SVHN) dataset.

The project compares a traditional machine learning baseline against deep learning models:

1. Support Vector Machine (SVM) using flattened image features
2. Deep Convolutional Neural Network (DCNN)
3. DCNN with Keras image data augmentation

## Live notebook

View the full runnable notebook on Kaggle:

[Open Kaggle Notebook](https://www.kaggle.com/code/deeppatel68/svhn-digit-classification-svm-vs-deep-cnns)


## Project Motivation

Digit recognition is a common real-world computer vision task used in address parsing, document processing, logistics, and automated data entry. SVHN is more challenging than clean handwritten digit datasets because the images are collected from real street-view scenes and can include noise, lighting variation, imperfect cropping, and background clutter.

## Skills Demonstrated

- Computer vision classification
- TensorFlow/Keras model development
- CNN architecture design
- Data augmentation
- Baseline modelling with scikit-learn
- Model comparison and evaluation
- Confusion matrix analysis
- Failure case analysis
- Kaggle notebook publishing

## Files

- `svhn_digit_classification_project.ipynb` — main Kaggle notebook
- `svhn_train.mat` — training dataset
- `svhn_validation.mat` — validation dataset
- `svhn_test.mat` — test dataset
- `cnn_model_architecture.png` — model architecture image, optional

## How to Run on Kaggle

1. Create a new Kaggle Dataset.
2. Upload `svhn_train.mat`, `svhn_validation.mat`, and `svhn_test.mat`.
3. Create a new Kaggle Notebook.
4. Import or copy the notebook `svhn_digit_classification_project.ipynb`.
5. Click **Add Data** and attach your uploaded SVHN dataset.
6. Enable GPU acceleration if available.
7. Run all notebook cells.
8. Save and publish the notebook.

This project is designed to show practical machine learning workflow ability rather than just final model accuracy. It includes the full workflow from dataset loading and preprocessing through to baseline comparison, deep learning model training, evaluation, visualisation, and model export.
