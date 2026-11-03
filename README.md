# Breast Cancer Detection using Logistic Regression from Scratch

## Overview

This project implements Logistic Regression from scratch using Python and NumPy to classify breast cancer tumors as Malignant or Benign.

The main objective of this project is to understand the mathematical concepts behind Logistic Regression and implement the algorithm without using Scikit-learn's built-in Logistic Regression model.

## Dataset

This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset** from the UCI Machine Learning Repository.

- Total samples: 569
- Total features: 30
- Target variable: Diagnosis
- Malignant (M): 1
- Benign (B): 0

Dataset source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Implementation

The following components were implemented from scratch:

- Sigmoid Function
- Binary Cross-Entropy Cost Function
- Gradient Computation
- Gradient Descent Optimization
- Prediction Functions
- Accuracy Calculation

Additional preprocessing and evaluation techniques:

- Train-Test Split
- Feature Standardization using StandardScaler
- Cost Function Visualization

## Model Performance

The model achieved **97.37% test accuracy** on the 20% held-out test set.

This result is based on a single train-test split with `random_state=11`.

## Project Structure

```text
Breast-Cancer-Detection-Logistic-Regression-Scratch/
│
└── Breast-Cancer-Detection-Logistic-Regression-Scratch/
    │
    ├── breast_cancer_logistic_regression_scratch.ipynb
    ├── wdbc.data
    └── wdbc.names
```

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Dulsaraabeybandara/Breast-Cancer-Detection-Logistic-Regression-Scratch.git
   ```

2. Navigate to the project folder:

   ```bash
   cd Breast-Cancer-Detection-Logistic-Regression-Scratch/Breast-Cancer-Detection-Logistic-Regression-Scratch
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `breast_cancer_logistic_regression_scratch.ipynb` and run the notebook cells sequentially.

## Future Improvements

- Implement Precision, Recall, and F1-score from scratch.
- Implement a Confusion Matrix.
- Experiment with different learning rates and iterations.
- Evaluate model performance using additional validation techniques.

## Author

**Dulsara Abeybandara**
