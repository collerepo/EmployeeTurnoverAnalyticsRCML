# Employee Turnover Analytics

## Project Overview
This project aims to analyze employee turnover within Portobello Tech, an app innovator company. By utilizing machine learning algorithms, the project identifies key factors contributing to employee turnover, clusters employees based on their satisfaction and evaluation, handles class imbalance, and predicts employee turnover probabilities to suggest targeted retention strategies.

## Features
- **Data Quality Check**: Identifies and reports missing values.
- **Exploratory Data Analysis (EDA)**: Analyzes factors influencing employee turnover, visualizes data distributions, and correlates different features.
- **Clustering Analysis**: Groups employees who have left by their satisfaction and evaluation scores.
- **Class Imbalance Handling**: Applies Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset.
- **Model Training and Evaluation**: Trains and evaluates Logistic Regression, Random Forest, and Gradient Boosting models using k-fold cross-validation.
- **Retention Strategy Suggestions**: Categorizes employees into risk zones based on turnover probabilities to tailor retention strategies.

## Technologies Used
- Python 3.8+
- Pandas, Numpy
- Scikit-Learn
- Matplotlib, Seaborn
- Imbalanced-Learn

## Setup
To run this project, install the necessary dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

Usage
Data Preparation:
Load the data using Pandas and perform initial preprocessing and data quality checks.

Run EDA:
Use the provided Jupyter Notebook to explore and visualize data relationships.

Perform Clustering:
Apply KMeans clustering to understand different groups of employees based on key metrics.

Handle Class Imbalance:
Use SMOTE to balance the dataset effectively before modeling.

Model Training and Evaluation:
Train multiple models and evaluate their performance to select the best one.

Retention Strategies:
Based on model predictions, categorize employees into different risk zones and suggest appropriate retention strategies.

Files
data/: Directory containing the dataset in .xlsx format.
notebooks/: Jupyter notebooks for exploratory data analysis and model training.
scripts/: Python scripts for data preprocessing, model training, and evaluation.

Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your features or fixes.

License
This project is open-sourced under the MIT License.

This README file serves as a guide to help users understand the project's purpose, setup, and execution. You can modify this template as necessary to better fit your specific project needs or to elaborate on particular sections of your project.
