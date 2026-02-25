# Global AI Jobs (2020–2026)
Subject: SDS (Statistics and Data Science) / Hypothesis Testing + Regression Analysis  
Name: Abdanur

## 📌 Project Description
This project analyzes a large dataset about the **global AI & data science job market (2020–2026)**.  
The work includes data cleaning and exploratory data analysis (EDA), multiple hypothesis tests (t-tests, correlation tests, ANOVA), and regression models (simple and multiple linear regression).  
The goal is to understand which factors are related to the main outcome variable and how strong those relationships are.

Dataset in this repository: `ai_jobs.csv`  
Original dataset source (Kaggle): https://www.kaggle.com/datasets/mann14/global-ai-and-data-science-jobmarket-20202026

## 💡 Features
- Data preparation and EDA:
  - dataset overview (shape, data types, missing values)
  - cleaning and basic preprocessing
  - visualizations (at least 3 different plots)
- Hypothesis testing (α = 0.05):
  - one-sample t-test
  - two-sample t-test (with variance check)
  - paired t-test (with explanation of pairing)
  - Pearson and Spearman correlation (and comparison)
  - one-way ANOVA (3+ groups)
- Regression analysis:
  - simple linear regression (interpret slope/intercept, report R²)
  - multiple linear regression (3+ predictors, report R² and adjusted R²)
- Clear interpretation in context:
  - hypotheses, p-values, decisions, and conclusions

## 📦 Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- SciPy (statistical tests)
- Statsmodels and/or scikit-learn (regression)
- Matplotlib / Seaborn (visualizations)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MnstrsParago/SDS4.Regression_Tests.AI_Jobs.git
   cd SDS4.Regression_Tests.AI_Jobs
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy scipy matplotlib seaborn scikit-learn statsmodels
   ```

3. Open and run the notebook:
   - `Abdanur_Ayazbek_Task4_Analysis.ipynb`

## 📘 Reflection
This project helped me combine the full statistical workflow on a large real dataset: cleaning data, exploring patterns with plots, testing hypotheses with proper statistical methods, and building regression models to quantify relationships.  
I also learned that statistical results must be explained carefully, including limitations like missing data, assumptions of tests, and the fact that correlation does not always mean causation.
