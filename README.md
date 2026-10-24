# NeuroVision-AI 2.0

### Confidence-Aware Artificial Neural Network for Binary Classification

## Project Overview

NeuroVision-AI is a machine learning project that uses an Artificial Neural Network (ANN) to classify data from the `make_moons` dataset provided by Scikit-learn.

The project compares a basic ANN with an improved ANN and visualizes classification confidence, model accuracy, and robustness to different noise levels.

## Objectives

- Understand binary classification using an ANN.
- Compare basic and improved neural network models.
- Visualize the model's prediction confidence.
- Study the effect of noise on classification performance.
- Predict the class and confidence of a custom input point.

## Technologies Used

- Python
- Google Colab
- Scikit-learn
- NumPy
- Matplotlib
- IPyWidgets

## Dataset

The project uses the synthetic `make_moons` dataset from Scikit-learn. It contains two classes arranged in two interleaving moon-shaped patterns.

The dataset is generated with adjustable noise to experiment with classification difficulty.

## Methodology

1. Generate the dataset using `make_moons`.
2. Split the data into training and testing sets.
3. Standardize the features using `StandardScaler`.
4. Train a basic ANN and an improved ANN using `MLPClassifier`.
5. Compare the models using accuracy and F1-score.
6. Visualize prediction confidence, model comparison, and noise robustness.
7. Predict the class and confidence for a custom input point.

## Key Features

- **Interactive training:** Adjust dataset noise, hidden neurons, hidden layers, and training iterations.
- **ANN comparison:** Compare a basic model with an improved model.
- **Confidence map:** Visualize predicted probabilities and the decision boundary.
- **Noise challenge:** Observe how different noise levels affect model performance.
- **Custom prediction:** Test a point and display its predicted class and confidence.

## Sample Results

In one recorded run with the default settings:

| Model or Metric | Result |
|---|---:|
| Basic ANN Accuracy | 94.00% |
| Basic ANN F1-score | 0.939 |
| Improved ANN Accuracy | 98.00% |
| Improved ANN F1-score | 0.980 |
| Uncertain area of plotted grid | 2.21% |

*Results may vary when the interactive settings are changed.*

## How to Run

1. Open the project notebook in this repository.
2. Open it in Google Colab.
3. Run the notebook cells in order.
4. Adjust the interactive settings if needed.
5. Click **Train NeuroVision AI**.
6. Observe the model metrics and visualizations.
7. Run the custom prediction cell to test a point.

## Learning Outcomes

This project demonstrates ANN-based binary classification, feature scaling, model evaluation, prediction probabilities, and the effect of noisy data on machine learning performance.

## Author

**Sowbakyavathi R**

Artificial Intelligence and Data Science

GitHub: [Sowbakyavathi](https://github.com/Sowbakyavathi)
