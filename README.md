# Student Performance Prediction with Flask Deployment

## Overview

This repository houses an end-to-end machine learning application designed to predict student performance. It explores various machine learning algorithms, selects the best-performing model, and deploys it using Flask for user interaction.

## Key Features

***Diverse Algorithm Comparison***: Evaluates the performance of seven robust regression algorithms:
- Random Forest
- Decision Tree
- Gradient Boosting
- Linear Regression
- XGBoost
- CatBoost
- AdaBoost

***Rigorous Model Selection***: Utilizes cross-validation and performance metrics (e.g., RMSE, R-squared) to select the best-performing model.

***Interpretability and Explainability***: Incorporates feature importance analysis to provide insights into factors influencing predictions.

***Scalable Flask Deployment***: Facilitates integration with existing workflows and enables easy prediction access.

## Setup and Usage

***Clone the repository:***

1. **Clone the Repository**
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to install the project.
   - Run the following command to clone the GitHub repository:
     ```
     git clone https://github.com/<your-username>/student-performance-prediction
     ```

2. **Install Dependencies**
   - Navigate to the project directory:
     ```
     cd [project_directory]
     ```
   - Run the following command to install project dependencies:
     ```
     pip install -r requirements.txt
     ```

3. **Configure settings:(e.g., data paths, port number).**
  - Run the Flask app:
  - python app.py
