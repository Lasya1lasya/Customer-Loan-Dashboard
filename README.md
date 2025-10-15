
# 🏦 Customer Loan Data Dashboard (Power BI)

##  Project Overview
This project is a **Power BI Dashboard** built to analyze **customer loan data** and provide actionable insights.  
It helps stakeholders track **loan performance, customer segmentation, risk analysis, and repayment trends**.

---

##  Features
- **Automated Data Cleaning & Transformation** → Implemented using **Power BI Dataflows**
- **Scheduled & Incremental Refresh** → Ensures updated reports in real-time
- **Interactive Dashboards** → KPIs, charts, slicers, and drill-through insights
- **Loan Segmentation Analysis** → Based on age, income, loan type, and repayment history
- **Key Metrics** → Loan disbursement, overdue amounts, defaults, and customer retention

###  Features Implemented in Power BI Service:
- **Dataflows** → Built automated ETL pipelines to clean and transform customer loan data.
- **Scheduled Refresh** → Configured to refresh **daily** for up-to-date reporting.
- **Incremental Refresh** → Set up to handle **large datasets efficiently** by processing only new records.
- **Dataset Management** → Centralized data storage and optimized performance using cloud-based service.
- **Live Dashboard Sharing** → Published the dashboard to Power BI Service for stakeholder access.


##  Power Automate Flow: Auto Refresh & Email Loan Dashboard

This Power Automate flow automates the daily refresh and report distribution process for the Customer Loan Data dashboard.

### Flow Actions:
1. Trigger: Scheduled every day at 7:00 AM.
2. Action 1: Refreshes the Power BI dataset (`Customer Loan Data`).
3. Action 2: Waits 5 minutes to allow incremental refresh to complete.
4. Action 3: Exports the updated Power BI report as a PDF.
5. Action 4: Emails the PDF report automatically to the management team



##  Dashboard Preview
| KPI | Description |
|------|------------|
| Total Loans | Shows total loans issued |
| Active Customers | Count of active loan holders |
| Default Rate | Percentage of unpaid loans |
| Loan Type Distribution | Breakdown of loan types |
|year over year | loan amount and defult changes |
|Age Distribution | Over Loan Amount |
|credit card scores | credit scores over age group |

## Tech Stack
- **Power BI** → Dashboard & Visualizations  
- **Power BI Service** → Dataflows, Scheduled Refresh,Incremental Refresh. 
- **SQL Server** → Source Dataset  
- **DAX** → For KPIs & Measures
- **Power Automate** → Automation for daily  Auto refresh and exporting report to pdf through Email.



