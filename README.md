# PesaSmart_Financing
End-to-end Power BI reporting for a microfinance lender — disbursements, collections, and portfolio health. 

## Viz Overview & Business Context 
The Dashboards shows business metrics from inception to date of PesaSmart Financing a fictitious business that offers short term (30 day) working capital to its clients. The operations team needs a way to:
- Track monthly disbursements across clients
- Compare current-month performance with previous month and same month last year
- Monitor collection rates and identify at-risk clients
- Understand portfolio ageing and repayment behaviour


## Key Questions and Insights
1. How much has been disbursed from inception to date?
2. What is the average loan size?
3. How much has been disbursed per client?
4. Who are the highest served clients by cumulative loan amounts?
5. Which months are the busiest?
6. How much has been disbursed in a certain month?
7. How many clients have been disbursed to and by how much?
8. How much has been repaid? Both overally and of the the loans that have matured (loan tenure is 1 month)?
9. How many days does it take from loan disbursement to repayment?

## Dashboard Preview
### Executive Summary
<img width="581" height="328" alt="image" src="https://github.com/user-attachments/assets/0e504063-99fb-4844-83d4-eb04416d3578" />

### Disbursement and Collections (MoM & YoY)
<img width="577" height="327" alt="image" src="https://github.com/user-attachments/assets/ab72d47d-9124-4de8-b836-8fcd0644ccc4" />

### Repayments Data 
<img width="579" height="325" alt="image" src="https://github.com/user-attachments/assets/d8a75724-c720-49db-9f7a-af6fdfc4d50d" />


## 📊 Key Metrics

| Metric | Description |
|---|---|
| **Principal Disbursed** | Total loan principal issued in the selected period |
| **Interest Earned** | Interest revenue recognized |
| **Total Repaid** | Collections received (principal + interest + fees) |
| **Recovery Rate %** | Repaid ÷ Total Due — measures collection efficiency |
| **Avg Days to Collect** | Average time between disbursement and full repayment |
| **Open Loans Ageing** | Days since disbursement for active loans |
| **Date Joined** | Duration since first disbursement per client |


## 🛠️ Tools & Techniques

**Tools:**
- Power BI Desktop (data modelling, DAX, visual design)
- Python (pandas) for data cleaning in Google Colab
- GitHub for version control

## Repo Contents 
 - PowerBI Report Files  (.pbix). Open the file using PowerBI to view the Dashboard. 
 - Python Notebook (.ipynb) for data cleaning.
 - This documentation file (README.md)
