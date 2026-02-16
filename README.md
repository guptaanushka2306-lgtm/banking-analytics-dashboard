# banking-analytics-dashboard
## Repository Description
End-to-end Banking Analytics Dashboard built in Power BI analyzing loans, deposits, customer segmentation, and financial performance metrics.

## 📌 Project Objective

The objective of this project is to analyze banking financial data and create an interactive dashboard that provides insights into:

Loan distribution
Deposit performance
Customer segmentation
Business lending
Account balances
Income band classification
Nationality-based analysis
Engagement timeframes
This dashboard enables management to monitor financial health and make data-driven decisions.

## 📊 Dashboard Pages Overview

**1. Home Page – Financial Snapshot**
The Home Page provides a high-level summary of key financial indicators:
Total Clients: 3000
Total Loan: 4.38bn
Total Deposit: 3.77bn
Business Lending: 2.60bn
Savings Account Amount: 698.73M
Checking Account Amount: 963.28M
Foreign Currency Amount: 89.65M
**🔎 Purpose**: Gives executives a quick overview of overall banking performance.

**💰 2. Loan Analysis Page**
This page focuses on loan-related insights.

**Metrics Included**:
Total Loan
Bank Loan
Business Lending
CC Balance

**Visual Analysis**:
Loan by Income Band (High / Medium / Low)
Loan by Nationality
Loan by Occupation
Bank Loan by Banking Relationship

**🔎 Business Value**: Helps identify:
Which income group takes more loans
Which nationality contributes most to lending
Which occupation category has higher credit exposure.

**💳 3. Deposit Analysis Page**
This page analyzes deposit behavior.

**Key Metrics**:
Total Deposit
Bank Deposit
Savings Account Amount
Checking Account Amount
Foreign Currency Amount

**Visual Analysis**:
Deposit by Income Band
Deposit by Engagement Timeframe
Deposit by Nationality

**🔎 Business Value**:
Identifies long-term engaged customers
Understands deposit concentration
Tracks savings vs checking distribution.

**📈 4. Summary Page**
This page consolidates all major financial KPIs:
Total Clients
Total Loan
Total Deposit
Total CC Amount
Bank Deposit
Business Lending
Engagement Account
**🔎 Purpose**: Provides final summarized financial performance in one view.

## 🎛 Filters & Slicers Implemented
The dashboard includes dynamic filtering:
Joining Year (2013–2021)
Gender (Male / Female)
Banking Relationship:
Commercial
Institutional
Private Bank
Retail
Institution Advisor
These slicers allow real-time data filtering and interactive analysis.

## 🛠 Technical Implementation

**Data Modeling**
Created relationships between fact and dimension tables
Applied star schema structure

**DAX Measures Used**
Examples:
Total Loan = SUM(Loan Amount)
Total Deposit = SUM(Deposit Amount)
Business Lending Calculation
Income Band Classification
Percentage Contribution

**Visualization Techniques**
KPI Cards
Bar Charts
Donut Charts
Tree Map
Stacked Column Charts
Interactive Slicers

## 📊 Key Business Insights
- Business lending contributes significantly (2.60bn) to total loan portfolio.
- Medium income group shows highest loan exposure.
- Long-term engagement customers (5+ years) contribute higher deposits.
- European nationality shows higher financial contribution compared to others.

## ✅ Conclusion
This Banking Financial Dashboard project demonstrates how raw financial data can be transformed into meaningful business insights using Power BI.

Through interactive visualizations and dynamic filtering, the dashboard provides a clear understanding of:
Overall loan and deposit performance
Customer segmentation by income band and nationality

Business lending contribution
Savings and checking account distribution
Long-term customer engagement trends
The analysis highlights that business lending forms a significant portion of the loan portfolio, while long-term customers contribute more towards deposits. Income-based segmentation helps in identifying high-value customer groups and credit exposure levels.

This project reflects strong skills in:
-Data modeling
-DAX calculations
-Financial data interpretation
-Dashboard design and storytelling
-Business-focused analytics

Overall, this dashboard can support banking management in making strategic, data-driven financial decisions and improving customer engagement strategies.
