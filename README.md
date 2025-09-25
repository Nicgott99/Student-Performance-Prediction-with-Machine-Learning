# Student Performance Prediction with Machine Learning

## Overview
This project analyzes student performance data using various machine learning techniques to predict student grades. The analysis includes data exploration, correlation analysis, and implementation of multiple regression models.

## Dataset
- **Source**: Student Math Performance Dataset (`student-mat.csv`)
- **Features**: Various student attributes including demographic, social, and school-related features
- **Target Variable**: Final grade (G3)

## Analysis Performed

### 1. Dataset Description
- Data shape and structure analysis
- Missing value identification
- Statistical summary of numerical features

### 2. Correlation Analysis
- Correlation heatmap visualization
- Feature correlation with target variable (G3)

### 3. Machine Learning Models
The project implements and compares multiple regression models:
- **Linear Regression**
- **Decision Tree Regressor**
- **Multi-layer Perceptron (Neural Network)**

### 4. Model Evaluation
- R² Score comparison
- Mean Squared Error analysis
- Performance visualization

## Technologies Used
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** & **seaborn** - Data visualization
- **scikit-learn** - Machine learning algorithms and tools

## Files
- `FINAL_PROJECT_CSE422.ipynb` - Main Jupyter notebook containing all analysis
- `README.md` - This file

## How to Run
1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook FINAL_PROJECT_CSE422.ipynb
   ```
3. Run all cells to execute the complete analysis

## Results
The project provides insights into:
- Key factors affecting student performance
- Comparative performance of different ML algorithms
- Predictive accuracy for student grade prediction

## Author
CSE422 Final Project

## Course
CSE422 - Machine Learning/Data Science