# Iris Dataset Classification Analysis
## Overview 
This project demonstrates the analysis and classification of the Iris dataset, a classic dataset widely used in machine learning and statistics. The dataset consists of three species of Iris plants: Iris Setosa, Iris Versicolour, and Iris Virginica. Each species is represented by 50 samples, with four distinct features measured for each: sepal length, sepal width, petal length, and petal width.

The goal of this project is to classify the species of an Iris plant based on the given features using various classification algorithms.

## Dataset Information
Number of Classes: 3
Number of Instances: 150 (50 samples per class)
- Features:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- Target Variable: species (Iris Setosa, Iris Versicolour, Iris Virginica)

## Project Objective
The main objective of this project is to:

- Perform Exploratory Data Analysis (EDA) to understand the dataset.
- Visualize feature distributions and relationships.
- Build and evaluate machine learning classification models.
- Achieve optimal classification performance.

## Libraries Used
The following Python libraries are used for analysis and modeling:

- pandas: Data manipulation and analysis.
- matplotlib: Data visualization.
- seaborn: Enhanced data visualization.
- scikit-learn: Machine learning algorithms and tools.

## Algorithms Used
The following machine learning algorithms are applied to classify the Iris dataset:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree

## Steps Involved
### 1. Data Loading:

- Load the Iris dataset using pandas.
- Perform an initial inspection of the dataset.

### 2. Data Exploration:

- Generate descriptive statistics for the dataset.
- Visualize pairwise relationships between features using scatter plots and seaborn's pairplot.

### 3. Data Preprocessing:

- Encode the target variable species into numeric values.
- Split the dataset into training and testing subsets.

### 4. Model Training:

- Train Logistic Regression, K-Nearest Neighbors, and Decision Tree models on the training dataset.

### 5. Model Evaluation:

- Evaluate each model on the test dataset.
- Compare the performance based on accuracy.

### 6. Visualization:

- Create decision boundaries and feature importance plots to interpret model performance.

**Best method:** KNeighborsClassifier

**Accuracy:** 96%

#### Dataset
https://www.kaggle.com/datasets/uciml/iris

