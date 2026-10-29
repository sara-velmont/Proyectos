# Proyectos
A collection of projects in data analysis, machine learning, mathematical modeling, and scientific computing. This repository showcases my work with Python, statistical methods, computational simulations, and complex systems, combining mathematical reasoning with programming to explore data, build models, and solve quantitative problems.

# Data Science, Machine Learning & Statistical Modeling Portfolio

Welcome to my portfolio of academic and computational projects in **data analysis, machine learning, statistical modeling, and scientific computing**.

I am a physicist pursuing a background in applied mathematics, with an interest in using programming and statistical methods to investigate data, identify patterns, and build mathematical and computational models.

This repository brings together projects developed during my academic training, covering supervised and unsupervised learning, Bayesian statistics, time series analysis, and neural networks.

## Projects

### 1. Statistical Learning Models

**File:** [`Modelos_de_aprendizaje_estadístico.ipynb`](https://github.com/sara-velmont/Proyectos/blob/main/Modelos_de_aprendizaje_estad%C3%ADstico.ipynb)

A collection of statistical learning exercises and applications focused on regression and classification problems.

**Topics covered:**
- Data preprocessing and feature scaling.
- Linear regression with Ridge and Lasso regularization.
- Logistic regression and classification models.
- Decision trees, random forests, and gradient boosting.
- Hyperparameter tuning and model comparison.
- Model evaluation using metrics such as accuracy, mean squared error, and ROC-AUC.

The notebook includes applications involving prediction and classification tasks, providing practice in model development, evaluation, and selection.

**Skills:** Python, pandas, scikit-learn, statistical learning, regression, classification, model evaluation.

### 2. Unsupervised Learning with Real-World Data

**File:** [`Proyecto_aprendizaje_no_supervisado.ipynb`](https://github.com/sara-velmont/Proyectos/blob/main/Proyecto_aprendizaje_no_supervisado.ipynb)

This project investigates whether unsupervised learning methods can identify recurring daily patterns in real-world air quality measurements.

Using the UCI Air Quality dataset, the analysis represents daily observations as 24-hour temporal profiles and compares different clustering approaches.

**Methods and tasks:**
- K-means clustering.
- K-medoids using PAM.
- Gaussian Mixture Models (GMM).
- Dirichlet Process clustering.
- Selection and comparison of clustering solutions using silhouette scores.
- Principal Component Analysis (PCA) for visualization.
- Interpretation of cluster profiles and temporal patterns.

The analysis highlights the importance of evaluating clustering results rather than assuming that multiple groups necessarily exist in the data. The final comparison found limited evidence of distinct daily profiles under the methods and representation used.

**Skills:** Unsupervised learning, clustering, time-dependent data, PCA, statistical evaluation, data visualization, R.

### 3. Bayesian Hierarchical Modeling: Voice and Social Attitude

**File:** [`Proyecto_Bayes_Voces.ipynb`](https://github.com/sara-velmont/Proyectos/blob/main/Proyecto_Bayes_Voces.ipynb)

This project explores whether a speaker's vocal pitch varies with social attitude, comparing polite and informal dialogue.

A Bayesian hierarchical regression model is used to account for differences in baseline pitch between individuals while estimating the association between attitude and vocal pitch.

**Topics covered:**
- Bayesian hierarchical regression.
- Subject-level random effects.
- Weakly informative prior distributions.
- Interpretation of model parameters.
- Bayesian estimation using Stan-based tools.

The project illustrates how hierarchical models can represent individual variability while studying relationships between variables.

**Skills:** Bayesian statistics, hierarchical modeling, regression, probabilistic modeling, R.

### 4. Machine Learning for Wine Quality Classification

**File:** [`Proyecto_taller.ipynb`](https://github.com/sara-velmont/Proyectos/blob/main/Proyecto_taller.ipynb)

This project applies a machine learning workflow to wine quality data. The quality score is converted into a binary target, creating a classification problem.

**Main tasks:**
- Data preparation and target construction.
- Feature scaling and preprocessing.
- Stratified train-test splitting.
- Preparation of a machine learning pipeline using scikit-learn-compatible tools.
- Analysis of predictors associated with the target classification.

The project provides practical experience preparing structured data for predictive modeling.

**Skills:** Python, pandas, scikit-learn, feature engineering, data preprocessing, classification.

### 5. Neural Network Implementation from Scratch

**File:** [`Red_neuronal_con_la_arquitectura_propuesta.ipynb`](https://github.com/sara-velmont/Proyectos/blob/main/Red_neuronal_con_la_arquitectura_propuesta.ipynb)

This project implements a feedforward neural network using NumPy to classify three groups of synthetic points in a three-dimensional feature space.

Rather than relying on a high-level deep learning framework, the implementation explicitly calculates the main steps involved in training a neural network.

**Topics covered:**
- Synthetic data generation.
- Neural network architecture with a hidden layer.
- Sigmoid and softmax activation functions.
- Cross-entropy loss.
- Forward propagation and backpropagation.
- Gradient descent and iterative weight updates.

This project focuses on understanding the mathematical foundations of neural network training and multiclass classification.

**Skills:** Python, NumPy, neural networks, deep learning fundamentals, numerical computation, optimization.

### 6. Time Series Analysis

**File:** [`Series_de_tiempo_Proyecto_P1.ipynb`](https://github.com/sara-velmont/Proyectos/blob/main/Series_de_tiempo_Proyecto_P1.ipynb)

This project explores time series data, including energy consumption and other temporal datasets, to investigate trends, seasonality, and stationarity.

**Main tasks:**
- Loading and preparing time-indexed data.
- Time series visualization.
- Seasonal decomposition.
- Stationarity assessment using the Augmented Dickey-Fuller (ADF) test.
- Autocorrelation analysis.
- Logarithmic transformations and differencing.

The project develops a foundation for understanding temporal structure and preparing time series for further statistical analysis and forecasting.

**Skills:** Python, pandas, Matplotlib, statsmodels, time series analysis, statistical testing, data visualization.

## Technical Skills

- **Programming:** Python, R.
- **Data analysis:** pandas, NumPy.
- **Statistical modeling:** Regression, regularization, Bayesian statistics, hierarchical models.
- **Machine learning:** Supervised learning, unsupervised learning, clustering, classification, neural networks.
- **Data visualization:** Matplotlib, PCA-based visualizations, clustering plots.
- **Time series:** Seasonal decomposition, stationarity testing, autocorrelation.
- **Model evaluation:** Train-test validation, silhouette scores, accuracy, MSE, ROC-AUC.

## Repository Structure

The repository contains Jupyter notebooks organized by project topic. Each notebook includes code and analysis related to its respective problem.

## How to Explore the Projects

You can open the notebooks directly on GitHub or run them using Google Colab. Some projects may require installing additional libraries or providing the datasets used in the analysis.

For reproducibility, check each notebook for its data sources, dependencies, and execution instructions.

---

*This portfolio reflects my ongoing development in data analysis, machine learning, statistical modeling, and computational methods.*
