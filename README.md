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
3. **Hedge Fund Financial Report:** Analyzed leverage and profitability ratios across industries to provide data-driven insights for hedge fund investment strategies.
4. **Stock Portfolio Optimization:** Applied Modern Portfolio Theory (MPT) to optimize FAANG stock allocation, minimizing risk and maximizing return using mean-variance optimization.



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
Python, Pandas, Seaborn, Financial Ratio Analysis, Excel

### Project Overview:
Analyzed financial reports to compute profitability and leverage ratios, helping investment firms assess financial risk.

### Key Contributions:
* Computed Key Ratios:
	* Debt-to-Equity Ratio to evaluate company leverage.
	* Gross Margin Ratio to measure profitability.
* Industry Insights:
	* Found that FMCG companies had the lowest profitability ratio.
	* Real Estate companies had the highest leverage ratio.
	* Found that higher leverage correlated with higher profitability in real estate companies.

### Impact & Insights:
* Provided data-driven financial insights for investment decision-making.
* Identified industry-specific financial trends for risk assessment.
* Insights can help investors assess financial stability and optimize risk management.



## Stock Portfolio Optimization
### Tools & Technologies:
Python, Pandas, NumPy, Matplotlib, Seaborn, PyPortfolioOpt, Mean-Variance Optimization, Sharpe Ratio

### Project Overview:
Optimized a FAANG stock portfolio using **Modern Portfolio Theory (MPT)** to balance risk and return, leveraging **mean-variance optimization** to construct the most efficient asset allocation.

### Key Contributions:
* **Benchmark Portfolio Analysis:**
  * Calculated **expected returns** and **Sharpe ratio** for an **equally weighted** FAANG portfolio.
* **Minimum Volatility Portfolio:**
  * Used **Mean-Variance Optimization (MVO)** to construct the portfolio with **lowest risk**.
  * Identified **optimal stock weights** to minimize portfolio volatility.
* **Maximum Sharpe Ratio Portfolio:**
  * Optimized stock allocation to **maximize return per unit of risk**.
  * Determined **ideal stock weight distribution** for the highest **risk-adjusted return**.

### Impact & Insights:
* Demonstrated **efficient frontier optimization**, showing how **diversification** can reduce investment risk.
* **Risk-return tradeoff analysis** revealed that an optimized allocation significantly outperforms an equal-weighted approach.
* **Data-driven portfolio recommendations** can help investors make better-informed decisions.
