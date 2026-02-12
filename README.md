# Purchase Amount Signal Audit

A rigorous exploratory and statistical audit of a retail purchase dataset to evaluate whether machine learning can reliably predict customer purchase amount.

## Objective
To assess predictive feasibility using principled data science methodology rather than forcing model performance from weak or noisy data.

## Methodology
- Exploratory Data Analysis (EDA)
- Feature engineering and categorical encoding
- Principal Component Analysis (PCA) to study variance structure
- Baseline RMSE comparison using mean prediction
- Tree-based regression modeling with hyperparameter tuning
- Cross-validated performance evaluation

## Key Findings
- First principal component explains only ~9% of total variance, indicating weak underlying structure.
- Best model RMSE is approximately equal to baseline RMSE, showing no meaningful learning.
- Cross-validated R² remains near zero across folds, confirming lack of predictive signal.

## Conclusion
The dataset does not contain sufficient information to support a reliable regression model.  
This project highlights the importance of **scientifically validating model infeasibility**, a critical real-world data science skill.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
