ECG Classification using ResNet

Overview

This project presents a deep learning approach for ECG heartbeat classification using a Residual Neural Network (ResNet). The model is trained and evaluated on the MIT-BIH Arrhythmia Dataset to classify ECG signals into multiple heartbeat categories.

Dataset

- MIT-BIH Arrhythmia Dataset
- ECG signals preprocessed and normalized before training
- Multi-class heartbeat classification

Model Architecture

- Residual Neural Network (ResNet)
- TensorFlow / Keras implementation
- Batch Normalization and Residual Connections
- Softmax output layer for multi-class classification

Loss Functions Evaluated

- Categorical Cross-Entropy
- Focal Loss
- Dice Loss
- Hinge Loss
- KL Divergence Loss
- Label Smoothing Loss
- Cosine Similarity Loss
- Confidence Penalty Loss
- Mean Squared Error (MSE)
- Symmetric Cross-Entropy Loss
- Weighted Cross-Entropy Loss
- Class-Based Loss

Performance Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Matthews Correlation Coefficient (MCC)
- Training Loss
- Validation Loss

Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Project Structure

- notebooks/ : Model training notebooks
- results/ : Experimental results and plots
- models/ : Saved model weights
- README.md : Project documentation

