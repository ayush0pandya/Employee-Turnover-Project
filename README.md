# Employee Turnover Project

## Overview
A logistic regression project to predict employee turnover based on workplace and demographic features (job satisfaction, performance rating, tenure, income, work-life balance, and more). Three model variants were trained and compared:

1. Baseline Logistic Regression (no penalty)
2. Logistic Regression with explicit L1 regularization
3. Logistic Regression with explicit L2 regularization

## Results
| Model | Accuracy | Precision |
|---|---|---|
| Baseline (no penalty) | see notebook | see notebook |
| L1 Regularization | see notebook | see notebook |
| L2 Regularization | see notebook | see notebook |

The L1-regularized model performed best on accuracy and precision among the three. Evaluation was limited to these two metrics; recall and F1-score are noted as potential follow-up work.

## Files
- `Employee Turnover Project.ipynb` — full notebook (data loading, train/test split, model training, evaluation)
- `employee_turnover.csv` — dataset
- `requirements.txt` — Python dependencies
