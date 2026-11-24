# Loan Default Risk Analysis

## Project Overview

This project analyzes loan application data for Horizon Financial Group to identify patterns and factors associated with loan defaults.

The objective is to understand borrower risk, evaluate lending indicators, and provide data-driven recommendations to improve credit risk assessment.

## Business Problem

The company has an overall loan default rate of 24.29%, compared with its target of 12%.

This project investigates borrower profiles and loan characteristics to identify potential risk indicators.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- SQLite
- Statistical Analysis
- Jupyter Notebook

## Dataset

The analysis uses two datasets:

- `borrower_profiles.csv`
- `loan_applications.csv`

The datasets were joined using `borrower_id`.

Final merged dataset:
- 500 borrowers
- 601 loan applications
- 22 columns

## Key Analysis

1. Overall loan default rate
2. Credit score risk segmentation
3. Debt-to-income (DTI) analysis
4. Loan purpose comparison
5. Loan amount statistical testing
6. Employment status and tenure analysis
7. Correlation analysis
8. Credit score and DTI threshold evaluation

## Key Findings

- Overall default rate: 24.29%
- Credit score group 520–599 had a 49.14% default rate.
- Credit score group 750+ had an 11.69% default rate.
- DTI group 65+ had a 35.94% default rate.
- Employment tenure below two years was associated with a 34.52% default rate.
- Loan amount difference was not statistically significant (p-value: 0.657).
- Employment tenure showed a statistically significant association with default status (p-value: 0.0264).

## Screening Scenario

A historical screening combination was evaluated:

- Credit Score ≥ 700
- DTI ≤ 55

Results:
- Eligible loans: 218
- Historical coverage: 36.27%
- Observed default rate: 10.55%

This is an exploratory historical scenario, not a validated lending policy.

## Repository Contents

- `notebooks/` – Jupyter Notebook analysis
- `data/` – Project datasets
- `sql/` – SQL queries

## Business Recommendations

- Strengthen screening for low credit score applicants.
- Conduct additional affordability checks for high DTI applicants.
- Consider employment stability in risk assessment.
- Monitor default patterns across loan purposes.
- Validate screening rules on new data before implementation.

## Limitations

- Historical analysis does not establish causation.
- Multiple loans may belong to the same borrower.
- DTI values require validation against their original definition.
- Screening results require out-of-time validation.

## Author

Aspiring Data Analyst | Data Science & AI Engineering Learner
