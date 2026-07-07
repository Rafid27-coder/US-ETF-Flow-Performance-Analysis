# US ETF Flow, Performance and Market Beta Analysis
Overview
Analysis of 25 years of monthly US ETF data covering 3,023 funds from 2000 to 2024. This project was completed as part of a Master of Business Analytics at the University of Adelaide for a financial services client (IRESS).

# Business Questions

- Do investors respond to past ETF returns when deciding where to invest?
- Can future ETF flows be predicted, and does seasonality help?
- Can ETFs be grouped into meaningful behavioural categories?
- How has ETF market beta changed as the ETF universe expanded?

 # Key Findings

- Past returns are a weak predictor of ETF flows. Flow persistence and fund size matter more.
- Seasonality improves prediction only for bond and treasury ETFs with calendar-driven patterns.
- K-means clustering identified distinct ETF behavioural groups based on flow-performance beta and AUM.
- Average ETF market beta declined from approximately 1.4 in 2006 to 0.7 to 0.9 today, driven by product diversification rather than behavioural change.

# Tools and Methods

- Python: pandas, NumPy, scikit-learn, matplotlib, statsmodels
- OLS and logistic regression
- Train/test split with 80/20 time-ordered split
- K-means clustering with elbow method
- Winsorisation and robustness checks

# Data
- Data sourced from CRSP (licensed). Raw data files are not included in this repository due to licensing restrictions. The notebook documents all variable construction and cleaning steps.
# How to Run
- Open the notebook in Jupyter or Google Colab. Update the file paths to point to your local copies of the CSV files. Run all cells in order.
