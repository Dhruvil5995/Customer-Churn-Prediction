# Customer-Churn-Prediction

# Machine Learning Model Development with PyCaret and MLflow

## Introduction

This GitHub repository contains code and resources related to the development of machine learning models using the PyCaret library and integration with MLflow. The repository consists of two main scripts, each focusing on different datasets and machine learning objectives.

## MLflow and DAGsHub Integration
We utilized MLflow for experiment tracking, model versioning, and visualization, while DAGsHub served as an online repository with Git integration. This combination enhanced team collaboration and ensured reproducibility

## Code Snippet 1: Churn_model_development.ipynb

### Overview
- This script focuses on building a machine learning model for churn prediction.
- It leverages the PyCaret library to automate the machine learning workflow.
- Model training, evaluation, and deployment are key components of this script.

### Key Steps
1. **Data Loading:** The script loads data from the 'raw_data.csv' file.
2. **PyCaret Setup:** It initializes a machine learning setup for classification, setting the target variable, session ID, and other parameters.
3. **Model Training:** Multiple machine learning models are compared, and the best-performing model is selected.
4. **Model Evaluation:** Various evaluation plots are generated, including AUC, confusion matrix, and feature importance.
5. **Model Saving:** The best model is saved in the 'outputs\model' folder.

## Code Snippet 2: MLflow_Churn_model_registration.ipynb

### Overview
- This script works with a different dataset or potentially a distinct machine learning task.
- It integrates with MLflow for experiment tracking and storage on the DAGsHub platform.
- Similar to the first script, it uses the PyCaret library for machine learning tasks.

### Key Steps
1. **MLflow Integration:** MLflow version 2 is installed and configured for experiment tracking on DAGsHub.
2. **Data Loading:** Data is loaded from the 'final_data.csv' file.
3. **PyCaret Setup:** A machine learning setup is initialized for classification, following a similar process as in the first script.
4. **Model Training:** Multiple machine learning models are compared, and the best-performing model is selected.
5. **Model Evaluation:** Various evaluation plots are generated, and the best model is saved in the 'outputs\model' folder.
6. **MLflow UI:** The script starts the MLflow user interface (UI) for experiment visualization.

![2023-09-09](https://github.com/Dhruvil5995/Customer-Churn-Prediction/assets/64741151/cc8587dd-001a-4429-b39c-3e10103dea77)

![2023-09-09 (1)](https://github.com/Dhruvil5995/Customer-Churn-Prediction/assets/64741151/422ae2f5-cf24-4aaf-bc96-3309c202577a)

## Usage
- Each script can be run independently based on the specific machine learning task or dataset.
- Make sure to follow the setup and library installation instructions in the scripts.
- Additional information and documentation can be found within each script.

## Contributing
- Contributions to this repository are welcome. Please follow GitHub's standard pull request process.

## Acknowledgments
- The code and project structure in this repository are inspired by real-world machine learning projects.
