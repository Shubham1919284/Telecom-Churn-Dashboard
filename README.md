# 📊 Telecom Customer Churn Analysis – Power BI Dashboard

This project is a detailed business intelligence dashboard built using **Power BI** to analyze **customer churn data** for a telecom company. It identifies patterns, trends, and insights that help understand the reasons behind customer churn and provide actionable business recommendations.

---

## 🧠 Project Objective
 
The primary objective of this project is to explore and visualize factors that influence customer churn in the telecom industry, enabling the company to:

- Understand **which customers are leaving and why**
- Identify **key demographic and behavioral patterns**
- Support **data-driven decision-making** for churn reduction

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `TelecomChurnDashboard.pbix` | Full Power BI report (includes visuals, data model, and loaded dataset) |
| `TelecomChurnDashboard.pbit` | Power BI report template (same visuals and model, **no data**) |
| [**Telecom Churn Analysis Dashboard**](./Telecom%20Churn%20Analysis%20Dashboard.png) | High-resolution image of the dashboard used in this repository |


---

## 📷 Dashboard Overview

![Dashboard Screenshot](https://github.com/Shubham1919284/Telecom-Churn-Dashboard/blob/9ede81c84a3463145f4f6df3c2d4d5862e66c57c/Telecom%20Churn%20Analysis%20Dashboard--.png)

The dashboard contains multiple visualizations to break down the churn analysis from various angles.

---

## 📌 Key Dashboard Visuals & Insights

### 1. 🛜 Peoples Preferred Internet Service

- **Fiber optic** is the most used service (43.96%), followed by **DSL** (34.37%), and a small percentage with **No Internet** (21.67%).
- Important for understanding which services are most linked to churn.

---

### 2. 📄 People Churn by Contract Type

- Customers with **Month-to-month** contracts exhibit the **highest churn**.
- Long-term contracts (One year, Two year) show better customer retention.
- Insight: **Contract length directly influences loyalty**.

---

### 3. 📊 People Churn Percentage (Pie Chart)

- Shows the **proportion of customers who have churned** (Yes) vs. those who have stayed (No).
- Quick overview of churn rate: ~**26.54% churned**.

---

### 4. 👨‍🦱 People Churn by Gender

- Churn is **almost equal** across genders:
  - Male: ~0.9K churned
  - Female: ~0.9K churned
- Insight: **Gender is not a strong churn indicator**.

---

### 5. 💳 People Churn by Payment Method

- Highest churn in **Electronic Check** users.
- Customers using **automatic payment methods** (Credit Card, Bank Transfer) tend to stay longer.
- Insight: Manual payments may be associated with churn risk.

---

### 6. 👵 Churn by Senior Citizen Status

- Senior citizens (marked as `1`) churn **more frequently** than non-seniors.
- Insight: Age group needs special attention, potentially due to service usability or pricing issues.

---

### 7. 📈 People Churn by Tenure

- Customers with **shorter tenure (new customers)** are more likely to churn.
- There’s a spike in churn for tenure < 10 months and again towards 70+ months.
- Insight: **First few months are critical** — onboarding experience matters.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Data cleaning, modeling, and interactive dashboard creation |
| DAX | For calculated columns, measures, and KPIs |
| Power Query | For data transformation (ETL steps) |
| CSV Dataset | Simulated telecom customer data |

---

## 💡 Business Recommendations

1. 📞 Offer **contract-based incentives** to encourage longer-term plans.
2. 💳 Promote **auto-payment options** (like credit cards or bank transfers).
3. 👵 Provide **personalized support for senior citizens** to improve retention.
4. 📅 Focus on **retention strategies during early customer lifecycle** (0–10 months).
5. 📣 Educate fiber-optic users on service quality if churn is higher among them.

---

## ⚙️ How to Use This Project

1. **Clone or download** this repository.
2. Open the `.pbix` file in **Power BI Desktop** to explore or modify.
3. If you want to use your own data:
   - Open the `.pbit` template
   - Load your data (matching schema required)
   - Power BI will auto-refresh visuals and insights

---

## 📈 Possible Future Enhancements

- Add **predictive churn scoring** using Power BI with Python/R integration
- Integrate **Power BI Service** for cloud sharing and auto-refresh
- Add **slicer filters** for region, customer type, or plan type
- Connect to **live databases** (SQL Server, Azure) for real-time analysis

---

## 👨‍💻 Author

Shubham Kumar Jha 🎓 B.Tech CSE (Data Science) | Gulzar Group of Institutes (PTU)  
📧 Email: sk1919284@gmail.com  
🔗 LinkedIn: [linkedin.com/in/shubham-kumar-jha-1a2b3c](https://linkedin.com/in/shubham-kumar-jha-1a2b3c)  
🔗 GitHub: [github.com/Shubham1919284](https://github.com/Shubham1919284)

---

## 📝 License

This project is open-source and free to use for educational and portfolio purposes. Attribution appreciated.

---

⭐ If you like this project, don’t forget to **star the repo** and share feedback!

---
