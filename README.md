# Breast Cancer Prediction

This repository contains a machine learning project aimed at predicting breast cancer. The project utilizes a dataset containing features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass to predict whether a tumor is benign or malignant.

## Overview

The goal of this project is to build and evaluate different machine learning models for breast cancer prediction. The process involves:

1.  **Data Loading and Initial Exploration**: Loading the `BreastCancer.csv` dataset and performing initial data inspection to understand its structure and contents.
2.  **Exploratory Data Analysis (EDA)**: Visualizing the data to identify patterns, relationships, and distributions of features, and to understand the characteristics of benign and malignant tumors.
3.  **Data Preprocessing**: Handling missing values, feature scaling, and preparing the data for model training.
4.  **Model Training and Evaluation**: Implementing and evaluating various classification algorithms to predict breast cancer.

## Dataset

The project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**. This dataset includes various features such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension, computed for each cell nucleus. The `diagnosis` column indicates whether the tumor is malignant (M) or benign (B).

## Technologies Used

* **Python**: The primary programming language.
* **pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Matplotlib**: For data visualization.
* **Seaborn**: For enhanced data visualizations.
* **Scikit-learn**: For machine learning model implementation and evaluation.

## Usage

To run this notebook:

1.  Clone the repository to your local machine.
2.  Ensure you have all the necessary libraries installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `scikit-learn`). You can install them using pip:
    ```bash
    pip install pandas numpy matplotlib seaborn scipy scikit-learn
    ```
3.  Place the `BreastCancer.csv` dataset in the same directory as the notebook.
4.  Open the `breast_cancer_prediction (1).ipynb` file using Jupyter Notebook or JupyterLab.
5.  Run all cells to see the data loading, analysis, and model predictions.
6.  
