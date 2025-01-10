# Banking - Investment Analysis and Solutions
YOU CAN CHECK OUT MY [PROJECT NOTEBOOKS](https://github.com/khoapham1002/Banking-Investment-Optimization-Framework/tree/main/notebooks) FIRST!

## Table of Contents

- [Overview](#overview)
- [Tools and Techniques](#tools-and-techniques)
- [Setup](#setup)
- [Credit Card Approvals](#credit-card-approvals)
- [Bank Marketing Campaign](#bank-marketing-campaign)
- [Hedge Fund Financial Report](#hedge-fund-financial-report)
- [Stock Portfolio Analysis](#stock-portfolio-analysis)

## Overview

Delivered connected insights across financial systems by applying structured data workflows, predictive modeling, and optimization techniques to improve decision-making in banking, marketing, and investments.

1. **Credit Card Approvals:** Built a logistic regression model that classified credit card applications with accuracy of 0.798, streamlining the decision-making process.
2. **Bank Marketing Campaign:** Structured marketing data into PostgreSQL-compatible datasets, enabling scalable analysis of campaign performance.
3. **Hedge Fund Financial Report:** Analyzed leverage and profitability ratios across sectors, providing insights for hedge fund strategies.
4. **Stock Portfolio Analysis:** Optimized FAANG stock portfolios using mean-variance optimization, achieving a Sharpe ratio of 3.5.

## Tools and Techniques: 

- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, PyPortfolioOpt, PostgreSQL.  
- Data preprocessing, Data pipeline cleaning, Data wrangling, Feature engineering, Data visualization, Supervised learning, Logistic regression, Hyperparameter tuning, Financial modeling, Ratio analysis, Portfolio optimization.

## Setup
```bash
git clone <repository-url>
cd <repository-directory>
pip3 install -r requirements.txt
jupyter notebook bank-marketing-campaign.ipynb
```

### Credit Card Approvals

Objective: Automate the credit card approval process using supervised learning.

Key Tasks:
- Preprocessed raw data by replacing missing values and encoding categorical features.
- Trained a logistic regression model to classify applications as approved or rejected.
- Tuned hyperparameters using GridSearchCV to optimize model performance.

Key Insights:
- Achieved an accuracy of 79.8%, improving the efficiency of the credit card approval process.
- Provided a scalable pipeline for automating application decisions.

### Bank Marketing Campaign

Objective: Enhanced marketing strategies for a bank’s personal loan campaigns by analyzing customer demographics and campaign outcomes.

Key Tasks:
- Processed raw data into three structured DataFrames: client, campaign, and economics, each designed for specific analytical purposes.
- Reformatted data to meet PostgreSQL database standards, enabling seamless integration and scalability.

Key Insights:
- Created clean, consistent datasets for future analysis of campaign success rates.
- Enabled better tracking of customer behavior and campaign performance.

### Hedge Fund Financial Report

Objective: Assess financial health and risk metrics across industries.

Key Tasks:
- Calculated leverage ratios (debt-to-equity) and profitability ratios (gross margin) for companies in tech, FMCG, and real estate sectors.
- Analyzed sector trends, identifying real estate as having the highest leverage ratio (5.69) and FMCG as the least profitable sector (profitability ratio: 0.51).
- Visualized the positive correlation between leverage and profitability in real estate companies.

Key Insights:
- Provided industry-specific financial insights to guide investment decisions.
- Enhanced understanding of risk and return dynamics in diverse sectors.

### Stock Portfolio Analysis
Objective: Analyze FAANG stocks to determine optimal portfolio allocations.

Key Tasks:

- Calculate expected returns and annualized Sharpe ratio for an equally-weighted portfolio.
- Find a portfolio that minimizes volatility using mean-variance optimization.
- Find a portfolio that maximizes the Sharpe ratio using mean-variance optimization.

Key Insights:
- Achieved a Sharpe ratio of 3.5 in the optimized portfolio, showcasing how diversification reduces risk.
- Highlighted efficient investment strategies based on historical stock performance.
