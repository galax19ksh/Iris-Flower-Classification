# Iris Flower Classification
Iris classification is a classic problem in machine learning that involves classifying different species of iris flowers based on their measured characteristics. It is a popular introductory example due to its simplicity and availability of a well-known dataset.

## Dataset
Source: https://archive.ics.uci.edu/dataset/53/iris

The dataset consists of 150 samples of iris flowers, each belonging to one of three species: Iris setosa, Iris versicolor, and Iris virginica.

Each sample is described by four features: sepal length (cm), sepal width (cm), petal length (cm), and petal width (cm).

## Objective
The goal is to build machine learning model that can accurately predict the species of a new iris flower based solely on its measured features.

## Data Preprocessing 
* There is no missing or null values in the dataset.
* There is no class imbalance. Each target variable (iris species) are perfectly balanced.
* No distinct outliers

## Data Splitting & Feature Engineering
* Training and test data are split in 8:2.
* Feature scaling is performed.

## Models and Performance
* **Logistic Regression Classifier** - 100% accuracy
* **Random Forest CLassifier** - 100% accuracy
* **Decision Tree Classifier** - 100% accuracy
