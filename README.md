# Financial Health Prediction

This project explores financial well-being and builds a predictive model to classify small-business financial health across several countries. The dataset combines business ownership, access to finance, risk perception, and insurance-related indicators to study how operational and demographic factors relate to financial health outcomes.

## Project objective

The goal is to analyze patterns in the data and develop a model that predicts a business's financial health category, such as healthy, moderate, or at-risk, using available features.

## Repository structure

- `Notebook/Financial_health.ipynb` - Jupyter notebook with data loading, cleaning, exploratory analysis, and model development.
- `Rawdata/financial_health.csv` - business dataset used for analysis and modeling.
- `Rawdata/VariableDefinitions 1.csv` - variable dictionary explaining the fields in the dataset.
- `Docs/` - supporting documentation and project notes.

## Dataset overview

The data contains business-level records from multiple countries, including:

- owner demographics and business age
- income, turnover, and expenses
- mobile money, insurance, and loan usage
- access to credit and financial record keeping
- business risk perception and operational challenges
- target label indicating financial health outcome

## Typical workflow

1. Load and inspect the raw dataset.
2. Clean missing values and normalize inconsistent categorical entries.
3. Encode categorical variables for modeling.
4. Train and evaluate a classification model.
5. Review feature importance and interpret findings.

## Requirements

Use a Python environment with the following packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Getting started

```bash
cd "C:\Users\USER\Documents\Financail_health"
python -m venv .venv
.\.venv\Scripts\activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Notebook/Financial_health.ipynb
```

## Notes

This repository is designed for exploratory data analysis and machine learning experiments in a notebook workflow. The model and findings can be extended by adding more features, comparing algorithms, or validating performance on a holdout set.
