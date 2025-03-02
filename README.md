# Banking - Investment Analysis and Solutions
YOU CAN CHECK OUT MY [PROJECT NOTEBOOKS](https://github.com/khoapham1002/Banking-Investment-Optimization-Framework/blob/main/notebooks/framework.ipynb) FIRST!

## Table of Contents   
- [Overview](#overview)
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
4. **Stock Portfolio Analysis:** Optimized FAANG stock portfolios using mean-variance optimization, achieving a Sharpe ratio of 3.5, balancing risk and returns.



## Setup
```bash
git clone <repository-url>
cd <repository-directory>
pip3 install -r requirements.txt
jupyter notebook bank-marketing-campaign.ipynb
```



## Credit Card Approvals
### Tools & Technologies: 
Python, Pandas, Scikit-Learn, Logistic Regression, GridSearchCV, StandardScaler

### Project Overview: 
Developed a machine learning model to automate credit card approvals, reducing manual effort and improving accuracy.

### Key Contributions:
* Data Preprocessing: Handled missing values, standardized numerical features, and one-hot encoded categorical data.
* Model Training & Optimization:
    * Trained a Logistic Regression model, achieving 81.8% accuracy.
    * Used GridSearchCV to optimize hyperparameters (tol, max_iter) for better performance.

### Impact & Insights:
* Reduced manual workload for banks by automating approval decisions.
* Improved risk assessment through data-driven predictions.



## Bank Marketing Campaign
### Tools & Technologies: 
Python, Pandas, Data Cleaning, SQL Preparation

### Project Overview: 
Cleaned and restructured bank marketing campaign data to prepare for database storage and future analytics.

### Key Contributions:
* Data Cleaning & Structuring:
    * Created three structured tables (client, campaign, economics) for database ingestion.
    * Converted categorical variables (e.g., credit default, mortgage) into boolean format.
    * Created timestamp features from raw date columns.

### Impact & Insights:
* Enabled structured data storage for easy querying and future campaign analytics.
* Prepared data for predictive modeling in future marketing strategies.



## Hedge Fund Financial Report
### Tools & Technologies: 
Python, Pandas, Seaborn, Financial Ratio Analysis

### Project Overview:
Analyzed financial reports to compute profitability and leverage ratios, helping investment firms assess financial risk.

### Key Contributions:
* Computed Key Ratios:
	* Debt-to-Equity Ratio to evaluate company leverage.
	* Gross Margin Ratio to measure profitability.
* Industry Insights:
	* Found that FMCG companies had the lowest profitability ratio.
	* Real Estate companies had the highest leverage ratio.
	* Identified a positive correlation between leverage and profitability in real estate firms.

### Impact & Insights:
* Provided data-driven financial insights for investment decision-making.
* Identified industry-specific financial trends for risk assessment.



## Stock Portfolio Analysis
### Tools & Technologies:
Python, Pandas, PyPortfolioOpt, Mean-Variance Optimization

### Project Overview: 
Applied Modern Portfolio Theory (MPT) to optimize a FAANG stock portfolio, maximizing return while managing risk.

### Key Contributions:
* Benchmark Portfolio:
    * Calculated expected returns and Sharpe ratio for an equally weighted portfolio.
* Mean-Variance Optimization:
	* Found a minimum volatility portfolio, optimizing risk reduction.
	* Identified a Sharpe ratio-maximizing portfolio, optimizing returns.

### Impact & Insights:
* Provided a data-driven strategy for portfolio allocation.
* Demonstrated risk-return tradeoffs using financial optimization techniques.
