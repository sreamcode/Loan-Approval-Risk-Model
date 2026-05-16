Predictive Loan Approval & Credit Risk Model
ML model to predict loan approval outcomes using applicant 
financial data — achieving 85.37% accuracy and 0.817 AUC score.

Tools Used
Python | Pandas | Scikit-learn | Matplotlib | Seaborn

What I Did
- Cleaned and prepared 614 loan records (fixed 6 missing columns)
- Engineered key features: EMI, DTI Ratio, Log Income, Log Loan
- Trained Logistic Regression and Random Forest models
- Evaluated using Confusion Matrix, ROC Curve and AUC Score

Results
| Model | Accuracy | AUC |
|-------|----------|-----|
| Logistic Regression | 85.37% | 0.817 |
| Random Forest | 82.11% | — |

Key Finding
Credit History is the #1 factor in loan approval (importance: 0.234)

Dataset
Loan Prediction Dataset — 614 rows | Source: Kaggle

How to Run
pip install pandas numpy matplotlib seaborn scikit-learn
