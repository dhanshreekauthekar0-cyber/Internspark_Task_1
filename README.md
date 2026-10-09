# Task 1 — Sales Data Cleaning & Analysis

## InternSpark Business Analytics Internship

This repository contains the complete submission for **Task 1: Sales Data Cleaning & Analysis**.

### Business objective
Clean the sales dataset, derive core sales KPIs, identify data-quality issues, and generate insights on sales by product, region/market, time and order status.

### Files

| File | Purpose |
|---|---|
| `Sales_Data_Analysis.ipynb` | Complete technical analysis, code, tables, visuals, insights and recommendations |
| `cleaned_sales_data.csv` | Cleaned dataset deliverable |
| `sales_data_sample.csv` | Public source dataset included for reproducibility |
| `Sales_Analysis_Report.pdf` | Business-facing report with executive summary, charts, recommendations and KPI framework |

### Headline results

- Total sales: **$10,032,628.85**
- Unique orders: **307**
- Average order value: **$32,679.57**
- Classic Cars sales contribution: **39.07%**
- USA sales contribution: **36.16%**
- Average November sales: **$1,059,443**
- Shipped order share: **93.16%**

### Important analytical assumptions

- The dataset is analyzed at order-line level; `ORDERNUMBER` identifies unique orders.
- AOV = total sales / unique orders.
- Missing Territory values are retained rather than artificially imputed.
- Deal Size is treated as an order-line attribute because multiple deal sizes occur within many orders.
- 2005 is partial (January–May), so it is not compared with complete years for annual growth.
- The public Kaggle dataset is a representative internship dataset and is not presented as Alfido Tech internal data.

### Submission

For the InternSpark form, use the **GitHub repository URL** in the `Task 1 GitHub Link` field. If no LinkedIn post is required/available, enter `NA` in the LinkedIn field.
