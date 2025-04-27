# Sonar-Based-Object-Classification (Rock-vs-Mine)

This project implements an Artificial Neural Network (ANN) model to perform a binary classification task.  
It is built using **TensorFlow** and **Keras**, demonstrating the use of deep learning for predictive analytics.

## Project Overview

- **Problem Type:** Binary Classification
- **Goal:** Train an ANN model that can accurately classify instances into one of two categories based on input features.

## Key Steps

1. **Data Preparation**
   - Dataset loaded and preprocessed.
   - Features (X) and Target (y) variables separated.
   - Train-test split (70% training, 30% testing).

2. **Model Architecture**
   - **Input Layer:** matching the number of features
   - **Hidden Layers:** 
     - First hidden layer with ReLU activation
     - Second hidden layer with ReLU activation
   - **Output Layer:** Single neuron with Sigmoid activation for binary classification.

3. **Compilation**
   - Optimizer: Adam
   - Loss Function: Binary Crossentropy
   - Evaluation Metric: Accuracy

4. **Training**
   - Model trained for 100 epochs.
   - Validation done on the test set.

5. **Evaluation**
   - Final test accuracy achieved: **~88%**

## Technologies Used

- Python
- TensorFlow
- Keras
- Scikit-learn
- Pandas
- Numpy
- Matplotlib (for visualization)
