# Telecom Customer Churn Analysis — Power BI Dashboard

> An end-to-end business intelligence dashboard analyzing customer churn patterns in the telecom industry, built to surface actionable retention insights through interactive visualizations.

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat&logo=powerbi&logoColor=black)](https://github.com/Shubham1919284/Telecom-Churn-Dashboard)
[![DAX](https://img.shields.io/badge/DAX-Measures%20%26%20KPIs-0078D4?style=flat)](https://github.com/Shubham1919284/Telecom-Churn-Dashboard)
[![Status](https://img.shields.io/badge/Status-Completed-28a745?style=flat)](https://github.com/Shubham1919284/Telecom-Churn-Dashboard)

---

## Dashboard Preview

![Telecom Churn Analysis Dashboard](https://github.com/Shubham1919284/Telecom-Churn-Dashboard/blob/9ede81c84a3463145f4f6df3c2d4d5862e66c57c/Telecom%20Churn%20Analysis%20Dashboard--.png)

---

## Project Objective

This project explores and visualizes the key factors driving customer churn in a telecom company. The dashboard enables business stakeholders to:

- Identify **which customers are at risk of leaving and why**
- Uncover **demographic and behavioral churn patterns**
- Support **data-driven retention strategy decisions**

---

## Key Findings

| Metric | Value |
|--------|-------|
| Overall Churn Rate | ~26.54% |
| Highest Churn Segment | Month-to-month contract holders |
| Most Used Internet Service | Fiber Optic (43.96%) |
| Lowest Churn Payment Method | Auto-pay (Credit Card / Bank Transfer) |
| Critical Churn Window | Customers with tenure < 10 months |
| Gender Impact on Churn | Negligible (~equal across Male & Female) |

---

## Dashboard Insights

### Contract Type
Month-to-month contract holders show the highest churn rate. Customers on one-year or two-year contracts demonstrate significantly better retention — confirming that **contract length directly correlates with loyalty**.

### Payment Method
Electronic check users churn at the highest rate. Customers on automatic payment methods (credit card, bank transfer) tend to stay longer, suggesting **manual payment friction is a churn risk signal**.

### Customer Tenure
Churn is highest in the first 10 months. The **early customer lifecycle is the most critical retention window** — onboarding experience and early engagement directly impact long-term loyalty.

### Senior Citizens
Senior citizens churn more frequently than non-seniors, likely due to service usability or pricing sensitivity. This segment requires **targeted support and personalized communication**.

### Internet Service
Fiber optic is the dominant service (43.96%), followed by DSL (34.37%). Understanding churn within each service tier helps prioritize **service quality improvements**.

### Gender
Churn is nearly equal across male (~0.9K) and female (~0.9K) customers. **Gender is not a meaningful churn predictor** in this dataset.

---

## Business Recommendations

1. **Incentivize long-term contracts** — Offer discounts or perks to convert month-to-month customers to annual plans.
2. **Promote auto-payment enrollment** — Nudge electronic check users toward credit card or bank transfer options.
3. **Strengthen early onboarding** — Implement proactive engagement programs for customers in their first 10 months.
4. **Support senior citizens** — Create a dedicated support tier with simplified interfaces and personalized assistance.
5. **Monitor fiber optic churn** — Investigate whether service quality issues are driving churn among fiber users.

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard design, data modeling, interactive visuals |
| DAX | Calculated columns, custom measures, KPIs |
| Power Query | Data transformation and ETL pipeline |
| CSV Dataset | Telco Customer Churn (Kaggle) |

---

## Project Files

| File | Description |
|------|-------------|
| `TelecomChurnDashboard.pbix` | Full Power BI report with data, visuals, and model |
| `TelecomChurnDashboard.pbit` | Power BI template — load your own data |
| `Telecom Churn Analysis Dashboard.png` | High-resolution dashboard screenshot |

---

## Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/Shubham1919284/Telecom-Churn-Dashboard.git
cd Telecom-Churn-Dashboard
```

**To explore the dashboard:**
- Open `TelecomChurnDashboard.pbix` in Power BI Desktop

**To use with your own data:**
- Open `TelecomChurnDashboard.pbit` (template)
- Load a dataset matching the original schema
- Power BI will auto-refresh all visuals

---

## Future Enhancements

- [ ] Add predictive churn scoring using Python/R integration within Power BI
- [ ] Deploy to Power BI Service for cloud sharing and scheduled refresh
- [ ] Add slicers for region, customer segment, and plan type
- [ ] Connect to live SQL Server or Azure database for real-time analysis

---

## Author

**Shubham Kumar Jha**  
B.Tech CSE (Data Science) — Gulzar Group of Institutes, PTU

[![Email](https://img.shields.io/badge/Email-sk1919284@gmail.com-D44638?style=flat&logo=gmail&logoColor=white)](mailto:sk1919284@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shubham--kumar--jha-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubham-kumar-jha-1a2b3c)
[![GitHub](https://img.shields.io/badge/GitHub-Shubham1919284-181717?style=flat&logo=github&logoColor=white)](https://github.com/Shubham1919284)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-4CAF50?style=flat&logo=googlechrome&logoColor=white)](https://shubham1919284.github.io/Portfolio/)

---

*Open-source and free to use for educational and portfolio purposes. Attribution appreciated.*
