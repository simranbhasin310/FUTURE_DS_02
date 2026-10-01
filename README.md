# 📉 Customer Churn & Retention Analytics

### Future Interns — Data Science & Analytics Internship | Task 2

[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel) [![Formulas](https://img.shields.io/badge/Excel%20Formulas-Data%20Analysis-217346?style=flat-square)]() [![Dashboard](https://img.shields.io/badge/Dashboard-Customer%20Churn-0078D4?style=flat-square)]() [![Status](https://img.shields.io/badge/Status-Complete-success?style=flat-square)]()

*Turning customer subscription data into a client-ready story of churn, retention, and customer behaviour.*

---

## 🎯 Objective

Analyze customer subscription data to uncover **churn patterns**, **retention drivers**, and **customer behaviour trends** — then translate that into a client-ready Excel dashboard with actionable insights and recommendations.

## 🗂️ Dataset

📦 **Telco Customer Churn Dataset** (Kaggle)
7,043 customer records covering demographics, tenure, contract type, internet service, payment method, monthly charges, subscribed services, and churn status — including pre-labeled Tenure Group, Contract Group, Monthly Charges Group, and Total Services fields used throughout the analysis.

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| 📊 Microsoft Excel | Data cleaning, analysis & dashboard |
| 🧮 Excel Formulas | `COUNTIF` / `SUMIFS` / `AVERAGEIF` — live calculated churn rates and segment breakdowns, not hardcoded values |
| 📈 Excel Charts | Bar and pie charts visualizing churn patterns across segments |
| 🎨 Excel Dashboard | Client-ready business presentation across 10 sheets |

## 📌 Headline Numbers

| 👥 Total Customers | 🔴 Churned Customers | 🟢 Active Customers | 📉 Churn Rate |
|---|---|---|---|
| **7,043** | **1,869** | **5,174** | **26.5%** |

## 🔬 Analysis Covered

1. ✅ Data cleaning & quality checks (blank `TotalCharges` handled via formula)
2. 📉 Overall customer churn breakdown (pie chart)
3. 📅 Customer tenure group & churn patterns (0-1 / 1-2 / 2-4 / 4+ years)
4. 📄 Contract type & churn (month-to-month / 1-year / 2-year)
5. 🌐 Internet service & churn (DSL / Fiber optic / None)
6. 💳 Payment method & churn
7. 🔐 Online Security, Online Backup, Device Protection & Tech Support vs. churn
8. 🧩 Total services subscribed & churn
9. 💰 Monthly charges group & churn (Low / Medium / High)
10. 💡 Key retention insights & recommendations

Every churn rate in the workbook is a **live formula** referencing the raw customer-level data — not a static number — so it recalculates if the underlying data changes.

## 💡 Key Insights

> **📅 Early-tenure risk** — Customers in the '0-1 Year' tenure group churn at ~48.3%, falling to under 10% for customers with 4+ years of tenure.

> **📄 Contract effect** — Month-to-month customers churn at ~42.7%, compared with ~11.3% for 1-year and ~2.8% for 2-year contracts.

> **🌐 Internet service** — Fiber optic customers churn more than DSL customers, despite paying more on average.

> **🧩 Service adoption** — Customers subscribed to more add-on services (security, backup, protection, tech support) churn noticeably less.

> **🔐 Support & security** — Customers without Online Security or Tech Support churn at roughly double the rate of those with these services.

> **💰 Customer charges** — Churn rises steadily from ~10.9% in the "Low" monthly-charges group to ~35.5% in the "High" group.

📊 *The complete analysis — formulas, segment tables, and charts — is available in the Excel workbook.*

## 📈 Dashboard

The Excel workbook brings the analysis together into a business-focused view of **customer churn and retention**, organized into dedicated sheets:

- Overall churn KPIs
- Tenure group analysis
- Contract analysis
- Internet service analysis
- Payment method analysis
- Customer service adoption
- Monthly charges segmentation
- Insights & recommendations

## 💡 Recommendations

- 🤝 Strengthen onboarding and engagement during the first year of the customer lifecycle, where churn risk is highest.
- 📄 Offer incentives to migrate month-to-month customers onto longer-term contracts.
- 🌐 Investigate the customer experience and pricing factors associated with fiber-optic customers.
- 🛠️ Proactively bundle support add-ons (security, backup, tech support) for new and at-risk customers.
- 🎯 Review pricing/value perception for the "High" monthly-charges segment, where churn is most elevated.

## 📁 Project Files

| File | Description |
|---|---|
| `Churn_Dashboard.xlsx` | Excel workbook — raw data, formula-driven churn analysis, and dashboard charts |
| `Telco-Customer-Churn.csv` | Customer churn dataset |
| `README.md` | Project documentation |

---

## 👤 Author

**Simran Bhasin**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simranbhasin310/) [![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/simranbhasin310/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:simranbhasin310@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://github.com/simranbhasin310/SimranBhasin310.github.io)

---

*Submitted as part of the Future Interns Data Science & Analytics internship.*

⭐ *If you found this analysis useful, consider starring the repo!*
