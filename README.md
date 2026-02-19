# 📊 Loan Default Risk Analytics Dashboard (250K+ Records)

### Dashboard Link : 
https://app.powerbi.com/groups/me/reports/13204f37-ee7d-45ac-9ef4-05bfe9f7f245/cea30e78a258b8957e3a?experience=power-bi

---

## Problem Statement

This dashboard helps financial institutions understand borrower behavior and identify key factors contributing to loan defaults.

It helps lenders analyze borrower characteristics such as income level, employment status, and credit score to evaluate the likelihood of loan repayment.

Through various financial KPIs, organizations can identify high-risk borrower segments and take proactive measures to reduce potential loan default risks.

Since a significant number of borrowers fall into medium to high-risk categories, financial institutions must improve their loan approval and risk assessment strategies.

Additionally, the dashboard highlights loan performance trends over time using YOY and YTD analysis, allowing stakeholders to make data-driven lending decisions.

---

### Steps Followed

- Step 1 : Loaded borrower dataset containing 250,000+ loan records from Excel into SQL Server.
- Step 2 : Connected SQL Server database with Power BI using Dataflows.
- Step 3 : Opened Power Query Editor and enabled:
  - Column Distribution  
  - Column Quality  
  - Column Profile  
- Step 4 : Performed data cleaning and handled missing values using Power Query.
- Step 5 : Transformed borrower attributes such as income level, employment status, and credit score.
- Step 6 : Created calculated KPI measures using DAX functions such as:
  - CALCULATE  
  - AVERAGEX  
  - MEDIANX  
  - ALLEXCEPT  
  - SWITCH  
- Step 7 : Developed financial KPIs including:
  - Loan Default Rate  
  - Average Loan Amount  
  - Borrower Income Distribution  
  - Credit Score-Based Risk Segmentation  
- Step 8 : Implemented Year-over-Year (YOY) and Year-to-Date (YTD) trend analysis.
- Step 9 : Designed interactive dashboard visuals and slicers.
- Step 10 : Configured Scheduled Refresh and Incremental Refresh in Power BI Service.
- Step 11 : Published report to Power BI Service for automated reporting.

---

# Snapshot of Dashboard (Power BI Service)

### Loan Default & Overview
<img width="1289" height="727" alt="Risk Segmentation" src="https://github.com/user-attachments/assets/cc1db8d3-522c-4f28-9c54-ac322546967a" />

### Income & Employment Insights
<img width="1286" height="720" alt="Income Analysis" src="https://github.com/user-attachments/assets/faf8ed13-a54c-46b5-b837-f102a62a8310" />

### Loan Performance Trends
<img width="1284" height="721" alt="Loan Trends" src="https://github.com/user-attachments/assets/d3d4cf06-fbe0-42ac-905c-ea8f984538b6" />

---

# Insights

A multi-page analytical report was created on Power BI Desktop and published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Borrower Risk Segmentation
- Identified high-risk borrower segments based on credit score.
- Low credit score borrowers contributed significantly to loan defaults.

### [2] Income Analysis
- Borrowers with unstable or low income showed higher default probability.
- Loan default trends varied significantly across income groups.

### [3] Employment Insights
- Borrowers with irregular employment history were more likely to default.
- Employment stability influenced repayment behavior.

### [4] Loan Performance Trends
- YOY and YTD analysis highlighted seasonal loan repayment patterns.
- Loan performance varied across different borrower categories.

### [5] Credit Score Evaluation
- High credit score borrowers demonstrated better repayment behavior.
- Medium-risk borrowers required further evaluation before loan approval.
