# Handwritten Digit Recognition (MNIST)

This project implements a complete machine learning pipeline for handwritten digit recognition using the MNIST dataset in CSV format. The goal is to classify grayscale handwritten digit images (0–9) using classical machine learning techniques.

## Project Overview
- Dataset: MNIST (CSV format, 28×28 grayscale images)
- Task: Multi-class image classification (digits 0–9)

## Methodology
1. Data loading and exploration using Pandas
2. Visualization of sample digit images
3. Data preprocessing and normalization (0–255 → 0–1)
4. Train–test split (80% / 20%)
5. K-Nearest Neighbors (KNN) implemented from scratch
6. Classical ML models using scikit-learn:
   - KNN
   - Support Vector Machine (SVM)
   - Decision Tree
7. Model evaluation using accuracy and confusion matrices
8. Misclassification analysis
9. Results and conclusion

## Files in this Repository
- `mnist_digit_recognition.ipynb` – Complete implementation
- `flow_diagram.png` – Execution flow diagram
- `mnist_digit_recognition.pdf` – Detailed report

## Note
The MNIST dataset is publicly available and is not included in this repository.
