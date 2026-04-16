# Data Exploration and Preparation

This project presents a complete data exploration and preprocessing workflow for a customer loan dataset. The aim is to understand the structure of the data, identify important patterns, and prepare the dataset for future analytical and predictive tasks.

The analysis focuses on customer demographics, income, credit quality, loan details, account behaviour, delinquency history, and repayment outcome. The dataset contains **3,000 records** and **21 original attributes**, with **loan_paid_back** used as the target variable. :contentReference[oaicite:0]{index=0}

---

## Project Objectives

- Explore the dataset using summary statistics and visualisations
- Identify distributions, outliers, and relationships between variables
- Analyse both numerical and categorical attributes
- Apply preprocessing techniques such as:
  - Binning
  - Normalisation
  - Discretisation
  - Binarisation
- Prepare the data for future machine learning and risk analysis tasks

---

## Dataset Overview

The dataset includes information related to:

- Customer demographics
- Annual and monthly income
- Debt-to-income ratio
- Credit score
- Loan amount and interest rate
- Credit limit and current balance
- Delinquency history
- Loan repayment outcome

According to the report, the dataset is complete and contains no missing values in the original 21 attributes. :contentReference[oaicite:1]{index=1}

---

## Files in this Repository

- `README.md` — project overview
- `Report.docx` — detailed written report of the analysis
- `data table.xlsx` — Excel workbook containing processed tables and outputs
- `main.ipynb` — Jupyter Notebook with the Python code for exploration and preprocessing

---

## Methods Used

### 1. Initial Data Exploration
The project includes:

- Attribute classification
- Summary statistics for numerical variables
- Frequency analysis for categorical variables
- Histograms, boxplots, bar charts, and scatter plots
- Correlation analysis
- Identification of outliers and interesting patterns

### 2. Data Preprocessing
The following preprocessing methods were applied:

- **Equi-width binning**
- **Equi-depth binning**
- **Min-max normalisation**
- **Z-score normalisation**
- **Age discretisation**
- **Gender binarisation**

These preprocessing steps were used to make the data easier to interpret and more suitable for future modelling. :contentReference[oaicite:2]{index=2}

---

## Key Findings

Some important findings from the analysis include:

- Several financial variables such as `annual_income`, `loan_amount`, `total_credit_limit`, and `current_balance` are right-skewed
- `credit_score`, `debt_to_income_ratio`, `interest_rate`, and `num_of_delinquencies` appear to be important indicators of repayment risk
- Borrowers with higher credit scores and lower debt-to-income ratios are more likely to repay loans
- Employment status shows a meaningful relationship with repayment behaviour
- The target variable `loan_paid_back` is imbalanced, with most customers repaying their loans :contentReference[oaicite:3]{index=3}

---

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Excel

---

## Future Work

This project can be extended in several ways:

- Build machine learning models to predict loan repayment
- Perform feature engineering for better model performance
- Handle class imbalance using resampling techniques
- Compare classification algorithms such as Logistic Regression, Decision Tree, Random Forest, and XGBoost
- Create an interactive dashboard using Streamlit or Power BI
- Perform customer segmentation for business insights
- Evaluate fairness and inclusiveness in preprocessing decisions, especially for gender binarisation

The report also notes that future work could include predictive modelling to support loan approval and risk assessment. :contentReference[oaicite:4]{index=4}

---

## Conclusion

This project demonstrates how data exploration and preprocessing can be used to better understand customer loan behaviour and prepare data for future analytics. The findings can help support more informed lending decisions, reduce risk, and improve customer profiling.

---

## Author

**Drashti Kakadiya**  
Master of Data Science and Innovation  
University of Technology Sydney

GitHub: [kakadiyadrashti](https://github.com/kakadiyadrashti)

---

## License

This project is for academic and learning purposes.
