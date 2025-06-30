# Loan Default Prediction Using Neural Networks

This project demonstrates how to predict loan default using an Artificial Neural Network (ANN) implemented in Python with TensorFlow and Keras.

[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)](https://keras.io/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org)

## 📁 Project Structure

- `loan_default_prediction.ipynb` – Jupyter Notebook with model training, evaluation, and visualization.
- `train.csv` – Training dataset.
- `test.csv` – Test dataset.
- `loan_predictions.csv` – Example of model prediction outputs.

## 🔧 Techniques Used

- Data preprocessing with Pandas and Scikit-learn
- Standardization of numerical features
- One-hot encoding of categorical features
- Dropout and L2 Regularization to reduce overfitting
- Early stopping to optimize training duration
- Model evaluation using accuracy, loss, and confusion matrix

## 📊 Visualization

Training and validation loss over epochs were plotted to monitor learning progress.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mekusgood/loan-default-prediction.git
