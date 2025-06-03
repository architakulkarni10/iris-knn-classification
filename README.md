# K-Nearest Neighbors (KNN) - Iris Classification

## Overview

This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm on the Iris dataset. KNN is an instance-based, non-parametric learning algorithm that classifies data points based on the majority class among their nearest neighbors.

---

## Dataset

- **Name**: Iris Dataset (from `sklearn.datasets`)
- **Classes**: Setosa, Versicolor, Virginica
- **Features**: Sepal length, sepal width, petal length, petal width
- **Target**: Iris flower species (3-class classification)

---

## Objectives

- Normalize feature values
- Train a KNN classifier using `scikit-learn`
- Evaluate model accuracy, confusion matrix, and classification report
- Experiment with different values of `k`
- Visualize accuracy trends and decision boundaries

---

## Files Included

- `Day6_KNN.ipynb`: Main notebook with code, visualizations, and results
- `README.md`: This documentation file

---

## Key Results

- Achieved over 96% accuracy on the test set with `k=3`
- Confusion matrix confirmed very few misclassifications
- Visualized decision boundaries using 2D feature reduction
- Observed how increasing `k` smooths decision boundaries but may reduce sensitivity

---

## Conclusion

KNN worked well on the Iris dataset due to its simplicity and clear class separation. Proper feature scaling and `k` selection are critical to its success. Though effective for small datasets, KNN’s performance can degrade on large-scale or noisy datasets due to its memory and computation cost.
