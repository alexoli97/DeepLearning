# Lab 3 - Visualizing CNNs with t-SNE and PCA

## Overview
Lab 3 delves into visualizing and understanding the internal workings of Convolutional Neural Networks (CNNs) using techniques like t-SNE and PCA. The lab combines theoretical insights with practical exercises, as detailed in the accompanying Colab Notebook.

## Prerequisites
- Basic understanding of CNNs.
- Familiarity with Python, TensorFlow, PCA, and t-SNE.

## Theory Part

### 1. Understanding t-SNE
- **Objective**: Explore the advantages of t-SNE over PCA.
- **Key Points**:
  - Preservation of local structures.
  - Non-linear dimensionality reduction capabilities.
  - Clustering and robustness to the crowding problem.

### 2. Loss Behavior Analysis
- **Objective**: Analyze how loss behaves in different scenarios based on the relationships between points in high-dimensional and low-dimensional spaces.
- **Discussion**: Understanding the implications of various spatial arrangements on loss calculation in dimensionality reduction.

## Practical Part
The Colab Notebook attached contains code for training a CNN on the MNIST dataset and visualizing the extracted features using PCA and t-SNE.

### Key Steps:
1. Train a CNN on the MNIST dataset.
2. Extract features using the trained model.
3. Apply PCA and t-SNE for dimensionality reduction.
4. Visualize the results to understand the CNN's feature extraction.

## Instructions
1. Review the theoretical concepts to understand the motivation behind using t-SNE and PCA for visualization.
2. Follow the steps in the Colab Notebook to train the CNN and perform feature extraction.
3. Apply PCA and t-SNE to the extracted features and analyze the visualizations.
4. Compare the insights gained from PCA and t-SNE visualizations.

## Additional Resources
- [t-SNE Video Explanation](https://www.youtube.com/watch?v=RJVL80Gg3lA)
- [Wikipedia: PCA](https://en.wikipedia.org/wiki/Principal_component_analysis)
- [Wikipedia: t-SNE](https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding)

## Contribution
Feel free to contribute to this guide by suggesting improvements, additional exercises, or resources.
