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

- Developed a credit card approval model with 81.8% accuracy, automating risk assessment for banks.
- Optimized data pipeline for bank marketing analysis, enabling more precise customer targeting.
- Analyzed financial ratios, identifying industry-specific risk trends for investment decision-making.
- Optimized a FAANG stock portfolio using mean-variance optimization, balancing risk and returns.



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
	* Achieved a final accuracy of 79.8% on the test set.
    * Used GridSearchCV to optimize hyperparameters (tol, max_iter) for better performance.

### Impact & Insights:
* Automated decision-making reduces manual processing time.
* Model can assist banks in filtering out high-risk applicants efficiently.
* A scalable solution that can be integrated into banking systems for real-time predictions.




## Bank Marketing Campaign
### Tools & Technologies: 
Python, Pandas, NumPy, PostgreSQL, Data Cleaning

### Project Overview: 
Structured marketing data into PostgreSQL-compatible datasets, enabling scalable analysis of campaign performance.

### Key Contributions:
* Data Cleaning & Structuring:
    * Created three structured tables (client, campaign, economics) for database ingestion.
    * Converted categorical variables (e.g., credit default, mortgage) into boolean format.
    * Created timestamp features from raw date columns.


### Impact & Insights:
* Split raw data into three structured datasets: client.csv, campaign.csv, and economics.csv.
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
