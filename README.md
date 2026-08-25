# Financial-Analytics-Of_Indian_IT_companies


**Financial Performance Analysis of Indian IT Companies**

📊 Project Overview

Financial Performance Analysis of Indian IT Companies is an
end-to-end data analytics project that evaluates the financial
performance of five leading Indian IT companies over a 10-year period
from FY2017 to FY2026.

The project combines Python, Pandas, Jupyter Notebook, and Power BI
to transform raw financial statement data into an interactive financial
analytics dashboard.

Companies Analyzed

* TCS

* Infosys

* HCLTech

* Wipro

* Tech Mahindra

The analysis focuses on growth, profitability, financial position,
cash flow, and comparative company performance.

🎯 Project Objectives

Analyze long-term financial performance across five Indian IT
companies.

Compare revenue and profit growth over ten financial years.

Evaluate profitability using ROE, ROA, Operating Margin, and Net
Profit Margin.

Analyze borrowings, working capital, and financial leverage.

Evaluate Operating Cash Flow and Free Cash Flow.

Identify company-specific strengths and weaknesses.

Build an interactive Power BI dashboard for business-oriented
financial analysis.

🗂️ Project Structure

Financial-Analytics/
│
├── data/
│   ├── raw/
│   │   ├── TCS.xlsx
│   │   ├── Infosys.xlsx
│   │   ├── HCLTech.xlsx
│   │   ├── Wipro.xlsx
│   │   └── Tech Mahindra.xlsx
│   │
│   └── processed/
│       ├── profit_loss.csv
│       ├── financial_data.csv
│       └── financial_kpis.csv
│
├── notebooks/
│   └── Financial_Analytics.ipynb
│
├── powerbi/
│   └── Financial_Performance_Analysis.pbix
│
└── README.md

🔄 Project Workflow

Raw Financial Data
        ↓
Excel Financial Statements
        ↓
Python + Pandas
        ↓
Data Cleaning & Transformation
        ↓
Data Integration
        ↓
Financial KPI Engineering
        ↓
Processed CSV Files
        ↓
Power BI
        ↓
Interactive Financial Dashboard
        ↓
Business Insights

🐍 Data Processing with Python

Python was used for the data preparation and analytical layer.

Key tasks

Imported Excel financial statements using Pandas.

Extracted Profit & Loss, Balance Sheet, and Cash Flow information.

Standardized company and financial-year structures.

Converted financial statements into analysis-ready tables.

Combined data from all five companies.

Created a unified company-year dataset.

Calculated financial growth and profitability KPIs.

Exported processed datasets as CSV files for Power BI.

Core Libraries

pandas
numpy
openpyxl

📊 Power BI Dashboard

The final Power BI report contains five analytical pages.

1. Executive Summary

Provides a high-level overview of financial performance.

Key areas: - Total Revenue - Total Net Profit - Operating Cash
Flow - Average Net Profit Margin - Average ROE - Revenue Growth Trend -
Net Profit Trend - Revenue Comparison - Company-level KPI comparison

Business question:
> What is the overall financial performance of the five companies?

2. Growth Analysis

Evaluates long-term growth patterns.

Key areas: - Revenue Growth - Profit Growth - Asset Growth - EPS
Growth - Growth trends by company - Average Revenue Growth comparison

Key finding:
HCLTech recorded the highest average revenue growth in the comparison,
followed closely by Infosys.

Business question:
> Which companies are growing faster, and how consistent is their
growth?

3. Profitability Analysis

Evaluates how efficiently companies generate returns and profits.

Key areas: - ROE - ROA - Operating Margin - Net Profit Margin -
Profitability trends - ROE vs ROA comparison

Key finding:
TCS demonstrated the strongest overall profitability performance in
terms of absolute profit and major profitability indicators.

Business question:
> Which companies generate stronger returns and operate with better
margins?

4. Financial Position & Cash Flow Analysis

Evaluates financial structure and cash-generation capability.

Key areas: - Borrowings - Working Capital - Operating Cash Flow -
Free Cash Flow - Debt-to-Equity - Financial position trends - Borrowings
comparison

Key finding:
Wipro had the highest borrowings and Debt-to-Equity ratio, while TCS
demonstrated strong operating and free cash flow generation with
relatively lower leverage.

Business question:
> How financially leveraged are the companies, and how effectively do
they generate cash?

5. Company Comparison & Key Insights

Brings the major findings together.

Key areas: - Revenue Growth - Net Profit - ROE - Operating Margin -
Operating Cash Flow - Revenue vs Net Profit - Company-level comparison -
Executive business insights

Key findings:

TCS led in cumulative sales, net profit, and operating cash
flow.

Infosys demonstrated strong profitability with relatively low
leverage.

HCLTech recorded the strongest average revenue growth.

Wipro had the highest borrowings and Debt-to-Equity ratio.

Tech Mahindra had the lowest cumulative sales and net profit but
remained competitive in selected growth metrics.

💡 Key Financial Insights

TCS --- Strongest Overall Scale

TCS maintained the highest cumulative sales, net profit, and operating
cash flow among the five companies.

HCLTech --- Strong Growth

HCLTech recorded the highest average revenue growth in the analysis.

Infosys --- Strong Profitability with Lower Leverage

Infosys combined strong profitability with relatively low Debt-to-Equity
compared with the other companies.

Wipro --- Highest Financial Leverage

Wipro had the highest cumulative borrowings and the highest
Debt-to-Equity ratio.

Tech Mahindra --- Smaller Scale, Selected Growth Strength

Tech Mahindra had the lowest cumulative sales and net profit, while
showing competitive performance in selected EPS and profit-growth
metrics.

📈 Financial KPIs

Growth Metrics

Revenue Growth %

Profit Growth %

EPS Growth %

Asset Growth %

Operating Profit Growth %

Profitability Metrics

ROE --- Return on Equity

ROA --- Return on Assets

Operating Margin %

Net Profit Margin %

Financial Position Metrics

Borrowings

Working Capital

Total Assets

Total Equity

Debt-to-Equity

Cash Flow Metrics

Operating Cash Flow

Investing Cash Flow

Financing Cash Flow

Net Cash Flow

Free Cash Flow

🛠️ Tools & Technologies

Tool                   Purpose

Python             Data processing and KPI engineering
Pandas             Data cleaning, transformation, and integration
NumPy              Numerical calculations
Jupyter Notebook   Data analysis and development
Excel              Source financial data
Power BI           Interactive dashboard and visualization
GitHub             Version control and documentation

📁 Processed Datasets

profit_loss.csv

Contains standardized Profit & Loss information.

financial_data.csv

Contains the integrated company-year financial dataset.

financial_kpis.csv

Contains the final analytical dataset with derived financial KPIs used
for the Power BI dashboard.

Dataset Size

5 companies × 10 financial years = 50 company-year records

📌 Analytical Structure

The final analytical dataset follows a company-year structure:

Company | Year | Financial Metrics | KPIs

Each company contributes ten financial-year observations from FY2017
through FY2026.

This structure supports:

Company filtering

Year filtering

Trend analysis

Cross-company comparison

KPI analysis

Interactive Power BI reporting

🔍 Important Analytical Considerations

Financial ratios such as ROE, ROA, Operating Margin, Net Profit
Margin, and Debt-to-Equity should generally be interpreted for
individual years or through appropriate averages and trends.

They should not be interpreted as meaningful cumulative sums across
multiple years.

Therefore, the dashboard uses trend and average-based views where
appropriate, while cumulative values are primarily used for absolute
financial metrics such as Sales, Net Profit, Borrowings, and Cash Flow.

🚀 Future Scope

Possible extensions include:

Adding quarterly financial data.

Incorporating historical stock-price performance.

Adding dividend analysis.

Adding valuation metrics such as P/E and P/B.

Developing revenue and profit forecasting models.

Adding machine-learning-based financial prediction.

Incorporating macroeconomic indicators.

Adding industry benchmarks.

Building automated data-refresh pipelines.

Developing interactive investment-oriented analysis.

🎓 Learning Outcomes

This project developed practical skills in:

Data cleaning

Data transformation

Exploratory data analysis

Financial analytics

KPI engineering

Python-based ETL

Pandas

Power BI dashboard development

Data visualization

Business storytelling

Comparative analysis

Financial ratio interpretation

📷 Dashboard Preview

Add screenshots of the five Power BI pages to the repository, for
example:

![Executive Summary](screenshots/executive_summary.png)
![Growth Analysis](screenshots/growth_analysis.png)
![Profitability Analysis](screenshots/profitability_analysis.png)
![Financial Position & Cash Flow](screenshots/financial_position_cash_flow.png)
![Company Comparison](screenshots/company_comparison.png)

⚠️ Disclaimer

This project is created for educational and portfolio purposes.

The analysis is based on historical financial data and should not be
interpreted as financial or investment advice. Historical performance
does not guarantee future performance.

👤 Author

Tanmay
Data Analyst | Python | Pandas | Power BI | Financial Analytics

⭐ Project Highlights

End-to-end financial analytics project using Python and Power BI to
analyze 10 years of financial performance across five leading Indian
IT companies.

Python → Data Processing → KPI Engineering → Power BI → Business
Insights
