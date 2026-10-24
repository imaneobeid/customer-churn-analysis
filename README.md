# Customer Churn Analysis 

##  Project Overview
This project analyzes customer churn in the telecommunications industry using Microsoft Excel. The goal is to identify patterns associated with customer cancellations, compare churn rates across customer groups, and recommend strategies to improve customer retention.

##  Objectives
- Calculate the overall customer churn rate.
- Analyze churn by contract type.
- Compare churn rates based on customer tenure.
- Visualize key findings using Excel charts.
- Recommend strategies to improve customer retention.

##  Dataset
The project uses the **Telco Customer Churn** dataset, which contains 7,043 customer records and information about customer accounts, services, contracts, and churn status.

**Dataset source:** [Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

##  Tools Used
- **Microsoft Excel** — data analysis, formulas, summary tables, and charts.
- **GitHub** — project documentation and version control.

##  Key Findings

### 1. Overall Customer Churn
- Total customers: **7,043**
- Churned customers: **1,869**
- Retained customers: **5,174**
- Overall churn rate: **26.54%**

### 2. Churn by Contract Type

| Contract Type | Total Customers | Churned Customers | Churn Rate |
|---|---:|---:|---:|
| Month-to-month | 3,875 | 1,655 | 42.71% |
| One year | 1,473 | 166 | 11.27% |
| Two year | 1,695 | 48 | 2.83% |

Month-to-month customers have the highest churn rate, while customers with two-year contracts have the lowest.

### 3. Churn by Customer Tenure

| Customer Group | Total Customers | Churned Customers | Churn Rate |
|---|---:|---:|---:|
| New customers (0–12 months) | 2,186 | 1,037 | 47.44% |
| Established customers (13+ months) | 4,857 | 832 | 17.13% |

Customers in their first year have a substantially higher churn rate than established customers.

##  Recommendations
1. **Improve onboarding:** Provide new customers with clear guidance and proactive support during their first year.
2. **Encourage longer contracts:** Consider appropriate incentives for customers who choose longer-term plans.
3. **Monitor at-risk customers:** Identify customers who may need additional support and contact them proactively.
4. **Collect customer feedback:** Use cancellation surveys to understand customer concerns.
5. **Track churn regularly:** Monitor churn by contract type and tenure to evaluate retention strategies.

##  Visualizations
The Excel workbook includes two charts:
- Churn Rate by Contract Type
- Churn Rate by Customer Tenure

##  Conclusion
The analysis identifies month-to-month contract customers and customers in their first year as priority groups for retention efforts. Targeted onboarding, appropriate contract incentives, and proactive customer support may help improve retention.

These results show associations between customer characteristics and churn; they do not establish causation.

##  Project Type
Data Analytics Internship Project — Customer Churn Analysis

##  Files
- `Customer_Churn_Analysis.xlsx` — Excel workbook containing analysis tables and visualizations.

##  Acknowledgment
The dataset was obtained from Kaggle and is used for educational and analytical purposes.
