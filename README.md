# Numaligarh-Refinery-Ltd-Project

Objective: Build a CNN classifier for the Fashion MNIST dataset and analyze how changing the training-test split affects classification accuracy.

Steps:

1. Import Libraries: Used `numpy`, `pandas`, `tensorflow`, and `matplotlib` for data manipulation, model building, and visualization.

2. Load Data: Loaded Fashion MNIST dataset and visualized sample images.

3. Preprocess Data: Normalized pixel values. • Split data into different ratios (60:40, 70:30, 80:20, 90:10) for training and testing.

4. Build Model: Defined a CNN with convolutional, pooling, flattening, and dense layers. Compiled with Adam optimizer and sparse categorical crossentropy.

5. Train Model: Trained the model on each split and plotted accuracy over epochs.

6. Evaluate Model: Tested on the test data, plotted confusion matrices, and generated classification reports.

7. Save Model: Saved the trained model for future use.

Comparative Analysis: Compared model performance metrics (accuracy, confusion matrix) across different training-test splits to assess how data distribution impacts classification results.
