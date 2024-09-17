# Wine Quality Prediction

This repository contains the implementation of a machine learning model to predict wine quality based on various chemical properties. The project explores different classification algorithms such as Support Vector Machine (SVM), Logistic Regression, and Random Forest Classifier to achieve optimal prediction performance.

## Table of Contents
- [Project Overview](#Project-Overview)
- [Models Used](#Models-Used)
- [Dataset](#Dataset)
- [Installation](#Installation)
- [Usage](#Usage)
- [Results](#Results)
- [Conclusion](#Conclusion)

## Project Overview

Wine quality is an essential aspect of the wine industry, influencing consumer choices and market value. This project aims to predict the quality of wine (on a scale of 0 to 10) based on its chemical composition. The dataset used contains features like alcohol content, pH, sulfur dioxide levels, and more.

## Models Used

- **Support Vector Machine (SVM)**: Helps in finding a hyperplane to classify wine quality into predefined categories.
- **Logistic Regression**: A baseline model for predicting categorical outcomes, suitable for binary and multiclass classification.
- **Random Forest Classifier**: A robust ensemble learning method that improves prediction accuracy using multiple decision trees.

## Dataset

The dataset contains information about the physicochemical properties of red and white wine samples. Features include:
- Alcohol
- pH
- Sulphates
- Citric Acid
- Residual Sugar

These features are used to predict the target variable: wine quality.

## Installation

1. Clone this repository to your local machine:
```bash
git clone https://github.com/prateek0809/Wine_Quality_Prediciton_Using_ML.git
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open the Wine_Quality_Prediction.ipynb notebook in your browser

## Usage

- Run the cells in the notebook sequentially to execute the entire project workflow.
- The notebook includes data preprocessing, model training, evaluation, and comparison of results across different models.

## Results

The performance of the models was evaluated using accuracy, precision, recall, and F1-score. Random Forest Classifier provided the highest accuracy among the tested models.

## Conclusion

This project demonstrates how various machine learning models can be used for classification tasks in the food and beverage industry. Further tuning of hyperparameters and adding more sophisticated models may enhance prediction accuracy.
