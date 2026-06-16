# Employee Turnover Project
A supervised machine learning project that predicts employee turnover using Logistic Regression, built on an HR analytics dataset.

---
## Dataset
The dataset contains 1,350 records with 15 features describing various attributes of employees, including job satisfaction, performance rating, tenure, work-life balance, income, and the target variable — `Employee_Turnover`.

---
## Project Workflow
1. **Exploratory Data Analysis (EDA)** — inspected shape, data types, and null values
2. **Train / Test Split** — 80/20 split using `train_test_split`
3. **Model Training** — trained three Logistic Regression variants: a baseline model with no penalty, a model with explicit L1 regularization, and a model with explicit L2 regularization
4. **Evaluation** — assessed and compared model performance using Accuracy and Precision

---
## Results
| Model | Accuracy | Precision |
|---|---|---|
| Baseline (no penalty) | 0.8593 | 0.8595 |
| L1 Regularization | 0.8667 | 0.8739 |
| L2 Regularization | 0.8593 | 0.8718 |

The L1-regularized model performed best on accuracy and precision among the three.

---
## Tech Stack
- Python 3.13
- pandas
- seaborn
- scikit-learn

---
## Files
| File | Description |
|---|---|
| `Employee Turnover Project.ipynb` | Main notebook with full pipeline |
| `employee_turnover.csv` | Dataset |

---
## What I Learned
- How to set up a baseline Logistic Regression model before tuning
- The difference between L1 and L2 regularization and how each affects model coefficients
- How to compare regularized models against a baseline using Accuracy and Precision
- That Accuracy and Precision alone are not sufficient for evaluating turnover prediction, where Recall and F1-score matter for catching employees likely to leave
