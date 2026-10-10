# Intel Image Classification using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN), a deep learning technique, to classify natural scene images into six categories.

## Objective
To build and evaluate a CNN model that automatically identifies the category of an image based on its visual features.

## Dataset
The Intel Image Classification dataset contains images belonging to six classes:
- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Model Architecture
The CNN model uses convolutional layers to extract image features, max-pooling layers to reduce dimensionality, dropout to help reduce overfitting, and dense layers for classification.

## Experiments and Evaluation
The project explores different model configurations and evaluates performance using:
- Training accuracy
- Validation accuracy
- Training loss
- Validation loss
- Test accuracy and test loss
- Confusion matrix
- Classification report

## Results
The baseline model achieved:
- **Validation Accuracy:** 84.25%
- **Test Accuracy:** 82.20%
- **Test Loss:** 0.4811

These results are from the baseline model; other configurations may produce different results.

## Project Files
- `CNN_Intel_Image_Classification.ipynb` — Google Colab containing the code, training outputs, visualizations, and evaluation.

## How to Run
1. Download or clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Download the Intel Image Classification dataset and configure the dataset path as required in the notebook.
4. Run the notebook cells in order.

## Note
This repository contains the model implementation and evaluation. It does not include a deployed website or application.
