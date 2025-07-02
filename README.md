# Users Churn & Fraud Insights Dashboard \- README

# **Overview**

This dashboard is designed to help identify user churn patterns and flag potentially fraudulent activities across our fintech transaction data for the year 2024\. By analyzing behavioral trends and transaction anomalies, the dashboard provides critical insights to support user retention, risk mitigation, and product optimization strategies.

# **Objectives**

* Detect and profile churned users based on inactivity (90+ days).  
*  Monitor and analyze suspicious high-value transactions.  
*  Understand user behaviors by location, account tier, and verification status.  
*  Provide actionable insights for product, marketing, and risk teams.

# **Navigation Structure**

Overview: High-level KPIs: total users, total transactions, total volume, etc.

Churn Insights: Churn rate trends, active vs churned user breakdown, churn by segment

User Profile: Churned users by verification status, account tier, and card linkage

Fraud Insights: Flagged transaction volume, fraud rate trends, suspicious amount over time

Risky Users: Table of user IDs with flagged transactions for deep-dive or escalation

Recommendations: Data-driven suggestions for reducing churn and improving fraud detection

# **Key KPIs & Metrics**

## **Churn Analysis**

*  Churn Rate (% of users inactive for 90+ days)  
*  Avg Days Since Last Transaction  
*  Churn Rate by Month  
*  Churn by Location, Account Tier, and Card Linkage  
*  % of Churned Users who were Verified

## **Fraud/Anomaly Analysis**

*  Flagged Transaction Rate  
*  Total Flagged Volume  
*   % of Total Volume Flagged  
*   Suspicious Volume Trend (Monthly)  
*   Flagged Transactions by Channel, Status, and Country  
*   Cross-Analysis: % of Churned Users Involved in Fraud (33–34%)

# **Notable Findings**

* 30% of users have churned — the spike is especially visible in May and September.  
* 68% of churned users had successful transactions — suggesting churn isn't due to failed payments.  
* 80% of churned users are verified — they are real, invested users who disengaged.  
* Flagged transactions represent 67.45% of total volume, despite being a smaller portion of count.  
* Highest flagged volume originates from South Africa, followed by Uganda and Kenya.  
* 76% of flagged transactions were successful — indicating lack of constraints or fraud checks.  
*  USSD is the most used channel for suspicious transfers.  
* 33–34% of churned users are also listed in the suspicious transaction table — indicating a potential link between fraud risk and churn.

# **Recommendations**

## **For Churn Mitigation**

*  Launch targeted retention campaigns focused on Tier 1 users and those without linked cards.  
* Consider localized marketing and multi-language support, especially for South African users.  
* Send re-engagement emails, SMS nudges, and card activation incentives.  
* Promote tier upgrades and usage through referral or loyalty programs.

## **For Fraud Risk Reduction**

*  Implement stricter checks and transaction flags for large-value transfers.  
*  Trigger pending status and multi-factor verification for flagged transactions.  
*  Conduct a deeper audit on users flagged in both churn and fraud dimensions.  
* Focus on channel-based risk patterns — especially on USSD transactions.

# **Tech Stack**

* • Data Tool: Power BI  
* • Data Source: Simulated fintech transaction data (CSV)  
*  Languages (underlying logic): DAX, Python (Pandas)  
* Metrics Engine: Calculated DAX measures and filters

# **Files Included**

*  ChurnRiskDashboard.pbix – Power BI dashboard file  
*   ChurnRisk python script \- Full Script on cleaning and analysis with python  
*   README.docx – This file  
*   churn\_fraud\_report.docx – Full written analysis for presentation

# **Contact**

For questions or walkthroughs, reach out to:

Sylvia Imisi

sylviaimisi01@gmail.com