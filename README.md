# Employee Attrition Classification using SVM and Random Forest

![Machine Learning](https://img.shields.io/badge/Machine-Learning-blue)
![Python](https://img.shields.io/badge/Python-3.x-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3.0-orange)

This project implements and compares two machine learning algorithms - Support Vector Machines (SVM) and Random Forest - for predicting employee attrition using a dataset containing employee information.


### File Descriptions:
- **.github/workflows/blank.yml**: GitHub Actions configuration file (currently blank)
- **Dataset.csv**: Contains employee data with features like age, job role, salary, and attrition status
- **LICENSE**: MIT License file for open-source usage
- **README.md**: Project documentation with setup instructions and results
- **ml-23070831-tut.pdf**: Supplementary tutorial or project documentation
- **model.ipynb**: Jupyter notebook containing:
  - Data preprocessing
  - EDA visualizations
  - SVM and Random Forest implementations
  - Model evaluation metrics
 

## Introduction
Employee attrition is a critical challenge for organizations. This project demonstrates how machine learning can help predict whether an employee is likely to leave the company. We compare two classification algorithms:
- **Support Vector Machine (SVM):** Finds the optimal hyperplane to separate classes
- **Random Forest:** Ensemble method combining multiple decision trees

## Dataset
The dataset contains 59,598 employee records with 24 features including:
- Age
- Gender
- Job role
- Monthly income
- Years at company
- Attrition status (target variable)


## Methodology
### Data Preprocessing
- Handling missing values
- Label encoding for categorical variables
- Feature scaling using StandardScaler

### Exploratory Data Analysis (EDA)
- Feature distribution analysis
- Correlation matrix visualization

### Feature Selection
- Correlation analysis
- Random Forest feature importance

### Model Training
- 80-20 train-test split
- Hyperparameter tuning for both models

## Results
Both models achieved comparable performance:

| Metric        | Random Forest | SVM     |
|---------------|--------------|---------|
| Accuracy      | 0.7415       | 0.7456  |
| Precision (0) | 0.73         | 0.73    |
| Recall (0)    | 0.73         | 0.74    |
| F1-score (0)  | 0.73         | 0.74    |
| Precision (1) | 0.76         | 0.75    |
| Recall (1)    | 0.75         | 0.75    |
| F1-score (1)  | 0.75         | 0.75    |


## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/employee-attrition-prediction.git
cd employee-attrition-prediction
