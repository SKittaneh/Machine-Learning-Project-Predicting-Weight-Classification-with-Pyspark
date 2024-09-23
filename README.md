# Predicting Obesity Classification from Lifestyle and Demographic Data

## Project Overview

This project explores the factors contributing to obesity by analyzing survey data on individual demographics and lifestyle habits. Our goal was to predict an individual's **obesity classification** without relying on height and weight, typically the most influential features in such predictions. By focusing on alternative factors (e.g., family history, eating habits, physical activity), we aim to develop an accurate, interpretable model for health and wellness applications. This project is implemented through PySpark.

**Key Features**:
- Predicts obesity classification based on **demographic and lifestyle factors**.
- Investigates the impact of non-obvious features on weight classification.
- Evaluates the performance of various machine learning models.
  
## Data

The dataset contains survey responses related to demographics and lifestyle habits, including:
- **Demographic Features**: Age, Gender, etc.
- **Lifestyle Habits**: Family history of obesity, calorie consumption, water intake, alcohol consumption, etc.
- **Target**: Weight classification (e.g., obesity, overweight, underweight, etc.)

We excluded height and weight to assess the predictive power of other features.

## Methodology

The following steps were performed in this project:

1. **Data Cleaning and Preprocessing**: 
    - Handled missing values and transformed categorical data into numerical formats.
    - Scaled and normalized features to improve model performance.
  
2. **Exploratory Data Analysis (EDA)**:
    - Visualized distributions of key lifestyle factors.
    - Identified correlations between features and obesity classification.

3. **Feature Selection**: 
    - Selected a subset of important features using techniques like feature importance from Random Forest.

4. **Modeling**:
    - Implemented multiple classification algorithms:
        - Logistic Regression
        - Random Forest Classifier


5. **Evaluation**:
    - Assessed models using accuracy and confusion matrix.
    - Identified and addressed class imbalance with resampling techniques.
