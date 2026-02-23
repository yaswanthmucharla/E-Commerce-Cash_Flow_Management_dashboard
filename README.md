## E-Commerce Cash Flow Management Dashboard – 2024
This project presents an end-to-end Power BI dashboard developed to analyze and monitor cash flow performance in an e-commerce environment.
The dashboard focuses on sales performance, actual cash realization, payment behavior, settlement delays, and customer transaction patterns using transactional and monthly aggregated data.

## Project Overview
E-commerce organizations handle large volumes of daily transactions across multiple payment methods and customer segments.
Tracking only total sales is not sufficient to understand real financial performance, because cash realization may differ due to payment failures, settlement delays and processing differences.

This project provides an interactive and centralized dashboard that enables stakeholders to monitor financial performance and operational efficiency related to cash flow.


## Problem Statement
Maintaining a healthy cash flow is a persistent challenge for small and medium-sized enterprises (SMEs).
Inconsistent customer payments, settlement delays and payment failures often result in irregular cash inflows, which can disrupt daily operations, delay supplier payments and limit the ability to invest in business growth.
Poor cash flow visibility makes it difficult for organizations to identify revenue leakages, monitor delayed settlements and understand payment performance across different channels.

According to multiple surveys, more than 80% of businesses fail due to poor cash flow management. Without a stable cash flow, SMEs often struggle to meet payroll, secure inventory, or adapt to unexpected financial shocks.

The objective of this project is to design an interactive dashboard that supports better financial visibility and data-driven decision-making.

##  Business Questions

This dashboard answers the following key business questions:

1.How much total revenue is generated and how much cash is actually received?

2.How does gross sales compare with actual cash received on a monthly basis?

3.Which payment methods contribute the most to actual cash received?

4.How much cash is associated with settlement delays?

5.Which customer age groups generate the highest number of transactions?

6.How do product categories and countries influence cash flow performance?


##  Datasets Used

 <a href="https://github.com/yaswanthmucharla/E-Commerce-Cash_Flow_Management_dashboard/blob/main/Ecommerce_transactions.xlsx">E-commerce_Transaction_dataset</a> –-Raw transactional dataset.<br>
  <a href="https://github.com/yaswanthmucharla/E-Commerce-Cash_Flow_Management_dashboard/blob/main/cashflow_transactions.xlsx">Cashflow_transactions</a> – Cleaned transaction-level dataset used for analysis and reporting.<br>
 <a href="https://github.com/yaswanthmucharla/E-Commerce-Cash_Flow_Management_dashboard/blob/main/monthly_cashflow.xlsx>monthly_cashflow">Monthly_transaction</a> – Monthly aggregated cash flow dataset.


##  Key KPIs

**Total Sales (Gross)** – Total value of all orders placed before settlement.

**Actual Cash Received** – Total cash successfully received.

**Total Orders** – Total number of transactions.

**Cash Loss** – Difference between gross sales and actual cash received.



## Dashboard Visuals

The dashboard contains the following visualizations:

Monthly Gross Sales vs Actual Cash Received (trend analysis)
Net cash by payment method
Cash received by settlement delay days
Transactions by customer age group
KPI cards for financial performance
<a href="https://github.com/yaswanthmucharla/E-Commerce-Cash_Flow_Management_dashboard/blob/main/Cashflow_dashboard.png">View dashboard</a>.<br>
Powerbi_link:<a href="https://github.com/yaswanthmucharla/E-Commerce-Cash_Flow_Management_dashboard/blob/main/CASH%20FLOW%20MANAGEMENT%20PROJECT.pbix">powerbi_Dashboard</a>

## Interactive Filters

* Payment Method
* Product Category
* Country

All KPIs and visuals update dynamically based on the selected filters.



##  Tools & Technologies

* Microsoft Power BI
* Microsoft Excel
* Python (Pandas)
* Jupyter Notebook



##  Data Preparation

Data cleaning, transformation and monthly aggregation were performed using Python in the notebook.
The prepared datasets were then used to build the Power BI data model and visuals.<a href="https://github.com/yaswanthmucharla/E-Commerce-Cash_Flow_Management_dashboard/blob/main/Cash_flow_management.ipynb">python</a>


##  Project Objective

To build a clean and interactive financial dashboard that helps business and finance teams:

* track real cash inflow,
* detect payment settlement delays,
* analyze payment method performance, and
* understand customer transaction behaviour using age-group segmentation.


