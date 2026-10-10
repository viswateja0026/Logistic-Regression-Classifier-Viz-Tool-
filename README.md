# Interactive Logistic Regression Classifier with Decision Boundary Visualization

## Overview

This project is an interactive machine learning application developed using Python, Streamlit, NumPy, Matplotlib, and Scikit-learn.

It allows users to explore logistic regression classification by generating synthetic datasets, configuring model parameters, visualizing decision boundaries, and evaluating classification accuracy.

## Features

* **Dataset Selection:** Generate binary and multiclass datasets.
* **Interactive Configuration:** Customize regularization, solver, maximum iterations, and other model parameters.
* **Model Training:** Train a logistic regression classifier using Scikit-learn.
* **Decision Boundary Visualization:** Visualize the classification regions learned by the model.
* **Model Evaluation:** Calculate and display test-set accuracy.
* **Interactive Interface:** Configure and execute experiments through a Streamlit web application.

## Technologies Used

* Python
* Streamlit
* NumPy
* Matplotlib
* Scikit-learn

## Project Structure

```text
logistic-regression-visualizer/
│
├── streamlit-viz-tool.py
├── requirements.txt
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd logistic-regression-visualizer
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## Usage

Run the application using:

```bash
streamlit run streamlit-viz-tool.py
```

Open the local URL provided by Streamlit in your browser.

### How to Use

1. Select a binary or multiclass dataset.
2. Configure the logistic regression parameters.
3. Click **Run Algorithm**.
4. Examine the classification regions.
5. Review the model's test-set accuracy.

## How It Works

The application follows these steps:

1. Generates a synthetic dataset.
2. Splits the dataset into training and testing subsets.
3. Initializes the logistic regression classifier.
4. Trains the model using the training data.
5. Predicts labels for the test data.
6. Generates a mesh grid across the feature space.
7. Visualizes the predicted classification regions.
8. Calculates test-set accuracy.

## Evaluation Metric

The application uses accuracy to evaluate classification performance.

Accuracy is calculated as:

Accuracy = Correct Predictions / Total Predictions

## Future Enhancements

* Add precision, recall, and F1-score.
* Display a confusion matrix.
* Support additional datasets.
* Compare logistic regression with other classification algorithms.
* Allow users to upload their own datasets.
* Add automatic validation for incompatible model parameters.

## Learning Objectives

This project demonstrates practical applications of:

* Machine learning classification
* Logistic regression
* Model evaluation
* Data visualization
* Interactive application development


