# Iris Flower Classification Web App

This application applies basic machine learning concepts to classify Iris flowers into one of three species based on Fisher's Iris dataset.

## Software and Libraries

- **Python:** 3.6.0
- **Anaconda:** 4.3.0 (32 bit)
- **Scikit-learn:** 0.18.1

## Introduction

The Iris flower data set, introduced by Ronald Fisher in 1936, is a multivariate data set used as an example of linear discriminant analysis. It contains data from three species of Iris:

- **Iris setosa**
- **Iris virginica**
- **Iris versicolor**

Each species has 50 samples with the following features measured in centimeters:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Application Components

### 1. Iris Decision Tree Classifier
- **Data Source:** Utilizes the `load_iris()` function from the `sklearn` module.
- **Functionality:** Builds a decision tree to classify the species of Iris.
- **User Interaction:** Users enter the four flower measurements, and the app predicts the Iris species.

### 2. Iris K-Nearest Neighbors (KNN) Classifier
- **Data Source:** Again uses `load_iris()` from the `sklearn` module.
- **Data Splitting:** Divides the dataset into an 80:20 ratio for training and testing using `train_test_split()` from `sklearn`.
- **Model Training:** Trains a KNN classifier using the training data.
- **Prediction and Accuracy:** Predictions are made on the test set and accuracy is evaluated by comparing the predictions with the actual labels.

## Getting Started

To run this project locally, clone the repository and install the required packages:

```bash
git clone <repository-url>
cd <project-directory>
pip install -r requirements.txt
