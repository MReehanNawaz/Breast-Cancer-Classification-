# Single Layer Perceptron is used for Breast Cancer Classification

# About

This project uses a Single Layer Perceptron with TensorFlow to classify breast cancer samples into two classes:

 `0` → Malignant
* `1` → Benign

## Dataset

* Total samples: 569
* Features: 30
* Classes: 2
* Test samples: 114

## Workflow

```text
Breast Cancer Dataset
        ↓
Preprocessing
        ↓
Train / Test Split
        ↓
Weights + Bias
        ↓
Forward Propagation
        ↓
Softmax
        ↓
Loss
        ↓
GradientTape
        ↓
SGD
        ↓
Epochs
        ↓
Test Prediction
        ↓
Accuracy
        ↓
Confusion Matrix
        ↓
Classification Report
```

## Technologies

* Python
* NumPy
* Pandas
* Scikit-learn
* TensorFlow

## Model

```text
30 Features
     ↓
Single Layer
     ↓
2 Output Classes
     ↓
Softmax


## Training

The model was trained for **100 epochs** with a learning rate of **0.01**.

Final training loss:

text
0.1926


# Results

Test Accuracy:

```text
97.37%
```

Confusion Matrix:

text
[[38  1]
 [ 2 73]]


# Evaluation

The model was evaluated using:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score
