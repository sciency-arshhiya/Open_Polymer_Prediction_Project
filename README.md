# Open_Polymer_Prediction_Project
Exploratory Data Analysis (EDA) and Machine Learning (ML) project for polymer property prediction. Includes data preprocessing, model development, evaluation, and prediction workflows.

# Open Polymer Prediction

This project explores the Open Polymer Prediction dataset from the NeurIPS Open Polymer Prediction Challenge. The objective is to analyze polymer property data, perform exploratory data analysis (EDA), preprocess the dataset, and build a machine learning model to predict polymer properties.

## Project Overview

The project includes:

- Data loading and inspection
- Exploratory Data Analysis (EDA)
- Missing value analysis
- Data visualization using Matplotlib and Seaborn
- Label Encoding of categorical features
- Data preprocessing
- Train-test split
- Linear Regression model training
- Model evaluation using MAE, MSE, and R² Score
- Prediction generation for unseen data

## Dataset Features

The dataset contains the following columns:

- `id` – Unique identifier
- `SMILES` – Polymer structure representation
- `Tg` – Glass Transition Temperature
- `FFV` – Fractional Free Volume
- `Tc` – Thermal Conductivity
- `Density` – Polymer Density
- `Rg` – Radius of Gyration

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Workflow

1. Data Loading
2. Data Exploration
3. Data Visualization
4. Missing Value Analysis
5. Label Encoding
6. Feature Selection
7. Train-Test Split
8. Linear Regression Model Training
9. Model Evaluation
10. Prediction

## Results

The Linear Regression model was trained using the processed dataset and evaluated using standard regression metrics including Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.

## Repository Structure

```text
Open_Polymer_Prediction/
│
├── train.csv
├── test.csv
├── Open_Polymer_Prediction.ipynb
├── requirements.txt
└── README.md
