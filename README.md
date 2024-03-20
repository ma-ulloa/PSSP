# Protein Secondary Structure Prediction

This repository contains the code for a project focused on predicting protein secondary structures using multilayer fully connected neural networks. The project is a part of a Bioinformatics course held at Stockholm University, Sweden.

In this project, a fully connected neural network model was developed to predict secondary structures from amino acid sequences with a 76% overall accuracy. The model is particularly effective at predicting 2D conformations such as 𝛼-helices, 𝛽-sheets, and coils.

The code in this repository includes:

- Data preprocessing and feature extraction using Position-Specific Scoring Matrices (PSSM)
- Implementation of the multilayer feedforward neural network architecture
- Use of Bayesian Optimization and Hyperband algorithms from Keras tuner for model optimization
- Evaluation and optimization of various hyperparameters like window size, number of epochs, activation functions, and regularization techniques

This work demonstrates the effectiveness of regularization techniques and careful selection of activation functions in improving model performance. However, it also suggests that exploring alternative architectures and incorporating specific features to provide the network with additional structural and geometrical information may yield further improvements in accuracy.

Please refer to the accompanying report for a detailed explanation of the methods used and the results obtained.
