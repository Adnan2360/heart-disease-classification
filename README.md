# Heart Disease Classification

A group machine learning project completed for AASD 4001:
Mathematical Concepts for Machine Learning at George Brown Polytechnic.

## Project Overview

Compared five classification models to predict heart disease status.
The project includes data preprocessing, exploratory data analysis,
hyperparameter tuning, feature-removal analysis, and SMOTE experiments.

## Dataset

- 10,000 records
- 20 input features and one target: Heart Disease Status
- Class distribution: 80% No, 20% Yes

## Models

- Logistic Regression
- Decision Tree
- Random Forest
- SGD Classifier
- Support Vector Machine (SVM)

## Team Members

Adnan, Isabel, Kris, Ming-Chi, and Lance.

## My Contribution — Adnan Ahmed

- Data preprocessing, including missing-value handling, encoding, and scaling.
- Logistic Regression baseline modeling.
- Hyperparameter tuning using GridSearchCV.
- Feature-removal analysis and interpretation.

## Logistic Regression Results

| Experiment | Accuracy | Heart Disease Recall |
|---|---:|---:|
| Baseline | 52.25% | 46% |
| Tuned | 52.20% | 46% |
| Smoking and Diabetes removed | 51.40% | 43% |

Tuning had little effect. Removing Smoking and Diabetes slightly reduced recall.

## Tools

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn,
imbalanced-learn, and Jupyter Notebook.

## Project Files

- Project Notebook.ipynb — code and saved results
- heart_disease.csv — dataset
- Project Report.pdf — technical report
- Group Project Precentation.pptx — presentation

## How to Run

1. Download the repository files.
2. Keep heart_disease.csv in the same folder as the notebook.
3. Install the required packages:

   pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn jupyter

4. Open Project Notebook.ipynb in Jupyter and run the cells in order.

## Limitations

This repository preserves a group academic submission.
Some results in the report and presentation differ from the notebook.
Preprocessing and evaluation also have limitations, including imputation
before the train/test split and differences between experiment settings.
The results are educational and do not establish clinical reliability.
