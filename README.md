# telecom-customer-churn-analysis
A customer churn analysis for an American wireless telecommunications company, covering predictive modelling, profit-based decision optimisation for a retention discount program, and Monte Carlo risk assessment, as part of the COMM3501 Quantitative Business Analytics course.

## Data
- **Training set:** 30,000 customers with 44 variables
- **Evaluation set:** 10,000 customers with 43 variables
- **Contents:** Customer demographics, tenure, equipment, usage, billing, service issue and retention variables

## Methods
- **Predictive modelling:** Logistic regression, random forest and XGBoost, compared on AUC (ROC and PR), recall, F1 and Kappa
- **Threshold tuning:** Youden's J and F1 optimisation to prioritise recall
- **Model interpretation:** Decile-wise lift, variable importance and break-down plots for customer profiles
- **Decision optimisation:** Break-even churn probability (0.3571) for a 5% bill discount, with offers capped at the 3,000-customer operational capacity (expected profit uplift of about $18,000)
- **Stochastic modelling:** Monte Carlo simulation (10,000 runs) of Bernoulli churn outcomes, with bootstrapped standard errors for tail-risk estimates

## Code
The analysis is in `Customer Churn Modelling.Rmd`, run in R Studio.

## Paper
The full report is available in `Final Report.pdf`.
