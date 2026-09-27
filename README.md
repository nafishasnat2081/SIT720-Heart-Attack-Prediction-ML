# An Explainable Optimised Stacking Ensemble Framework for Heart Attack Prediction

## SIT720 Machine Learning - Task 11.1HD

## Project Overview

This project reproduces and enhances a published machine learning framework for early heart attack prediction.

The original research applied a stacking ensemble approach using multiple machine learning classifiers. This project critically evaluates the reliability of the original approach and develops an optimised explainable stacking framework.

The proposed framework integrates:

- Duplicate record removal for reliable evaluation
- Feature importance analysis
- Feature selection
- Hyperparameter optimisation
- Optimised stacking ensemble modelling
- SHAP-based explainability


## Folder Structure

```
SIT720_11_1HD_Heart_Attack_Prediction_Project

├── Presentation Slide
│   └── Final presentation slides
│
├── Dataset
│   └── Heart disease dataset used for experiments
│
├── Colab Notebook
│   └── SIT720_11_1HD_Heart_Attack_Reproduction.ipynb
│
├── Report
│   └── Final technical report
│
└── README.md
```


## Software Requirements

The project was developed using Python and Google Colab.

Required Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- shap


## How to Run the Notebook

1. Open the notebook:

```
Colab Notebook/
SIT720_11_1HD_Heart_Attack_Reproduction.ipynb
```

2. Upload the dataset from the Dataset folder.

3. Install required libraries if necessary.

4. Run all cells sequentially from beginning to end.


## Notebook Workflow

The notebook includes:

1. Dataset loading and exploration
2. Data quality analysis
3. Duplicate record identification
4. Reproduction of the original stacking ensemble framework
5. Evaluation using the duplicate-free dataset
6. Feature importance analysis
7. Feature selection
8. Hyperparameter optimisation
9. Development of the proposed optimised stacking framework
10. Performance evaluation
11. ROC curve analysis
12. Confusion matrix analysis
13. SHAP explainability analysis


## Expected Outputs

The notebook generates:

- Dataset quality analysis results
- Duplicate record statistics
- Machine learning model performance comparison
- Accuracy, Precision, Recall, F1-score and AUC metrics
- ROC curve visualisation
- Confusion matrix
- Feature importance ranking
- SHAP feature contribution analysis


## Author Information

Name: Nafis Hasnat

Student ID: 226455731

Unit: SIT720 Machine Learning

Assessment: Task 11.1HD
