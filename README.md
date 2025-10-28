
# 🏦 Customer Loan Data Dashboard (Power BI)

##  Project Overview
This project is a **Power BI Dashboard** built to analyze **customer loan data** and provide actionable insights.  
It helps stakeholders track **loan performance, customer segmentation, risk analysis, and repayment trends**.


<img width="1310" height="747" alt="Screenshot 2025-10-15 152202" src="https://github.com/user-attachments/assets/77028425-ad68-4a7a-8a23-73423bffb336" />
<img width="1276" height="688" alt="Screenshot 2025-08-29 144616" src="https://github.com/user-attachments/assets/b13dbb1b-2caa-4b5a-91df-d76c9475b87d" />
<img width="1274" height="732" alt="Screenshot 2025-08-29 144633" src="https://github.com/user-attachments/assets/b577bdde-56ea-4dd6-986b-f9d46d49a047" />



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
  
<img width="1920" height="1080" alt="Screenshot 2025-08-29 144835" src="https://github.com/user-attachments/assets/8272402b-7fae-4842-b99b-ad0fa5c00cd8" />
<img width="1920" height="1080" alt="Screenshot 2025-08-29 145523" src="https://github.com/user-attachments/assets/b9821bce-581f-46bf-ba91-56eb8800abe5" />
<img width="1920" height="1080" alt="Screenshot 2025-08-29 145411" src="https://github.com/user-attachments/assets/b22f7cc4-0991-41e5-bc28-dfbbc51b12ed" />
<img width="1920" height="1080" alt="Screenshot 2025-08-29 145454" src="https://github.com/user-attachments/assets/f86f5159-4721-4767-a7ec-fbded09b9581" />


##  Power Automate Flow: Auto Refresh & Email Loan Dashboard

This Power Automate flow automates the daily refresh and report distribution process for the Customer Loan Data dashboard.

### Flow Actions:
1. Trigger: Scheduled every day at 7:00 AM.
2. Action 1: Refreshes the Power BI dataset (`Customer Loan Data`).
3. Action 2: Waits 5 minutes to allow incremental refresh to complete.
4. Action 3: Exports the updated Power BI report as a PDF.
5. Action 4: Emails the PDF report automatically to the management team

<img width="1385" height="745" alt="Screenshot 2025-10-28 105049" src="https://github.com/user-attachments/assets/7cb88708-78cd-4bcd-a524-c475933a2a38" />


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



