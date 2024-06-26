Cardiovascular Disease Prediction

This project aims to predict cardiovascular diseases using automated machine learning (AutoML) techniques with H2O and TPOT. The goal is to build accurate models that can assist in early detection and prevention of cardiovascular diseases.

Table of Contents

Overview
Features
Installation
Usage
Dataset
Modeling
Results
Contributing

Overview
Cardiovascular diseases are a leading cause of death worldwide. Early detection through predictive modeling can significantly improve treatment outcomes and save lives. This project leverages AutoML tools, specifically H2O and TPOT, to automate the machine learning workflow and build robust predictive models.

Features
Data Preprocessing: Cleaning and preparing the dataset for modeling.
Feature Engineering: Automatically generating relevant features.
Model Building: Using H2O and TPOT to create and optimize machine learning models.
Model Evaluation: Assessing model performance using various metrics.
Visualization: Plotting important results and feature importances.

Installation
Prerequisites
Python 3.6 or higher
pip
Clone the Repository
bash
Copy code
git clone https://github.com/Yuvraaj14/CardioVascular_Disease_AutoML_Project.git
cd CardioVascular_Disease_AutoML_Project

Usage
Data Preprocessing
python
Copy code
python preprocess.py
Model Training with H2O
python
Copy code
python train_h2o.py
Model Training with TPOT
python
Copy code
python train_tpot.py
Evaluate Models
python
Copy code
python evaluate.py
Jupyter Notebooks
To interactively explore the data and models, use the provided Jupyter notebooks:
bash
Copy code
jupyter notebook

Dataset
The dataset used for this project contains various features related to cardiovascular health, such as age, gender, cholesterol levels, and blood pressure. You can download the dataset from Kaggle, or use your own dataset with similar features.

Modeling
H2O AutoML
H2O AutoML automates the process of training and tuning a large selection of machine learning models, which includes:

TPOT
TPOT uses genetic programming to optimize machine learning pipelines. It explores various model types, preprocessing steps, and hyperparameters to find the best possible model.

Results
The project evaluates models based on metrics such as:

Accuracy
Precision
Recall
F1 Score
ROC AUC

Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.
