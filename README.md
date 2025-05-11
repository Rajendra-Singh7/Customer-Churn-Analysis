# 📉 Customer Churn Analysis – Telecom Industry

An end-to-end dashboard-driven project focused on analyzing and predicting customer churn in the telecom industry. Built using SQL Server, Power BI, and Python — this project uncovers churn trends, visualizes risk segments, and provides actionable insights through rich, interactive dashboards.

---

## 📌 Objective

To understand customer churn through descriptive dashboard analytics and build a predictive model using historical churn data — enabling better retention strategies and informed decision-making.

---

## 🧑‍💼 User Stories

| # | Role              | Request                                  | Value Provided                 | Acceptance Criteria                    |
| - | ----------------- | ---------------------------------------- | ------------------------------ | -------------------------------------- |
| 1 | Retention Manager | View total churn, churn rate, and trends | Plan offers & retention calls  | KPIs and filterable churn views        |
| 2 | Business Analyst  | Identify churn patterns by category      | Recommend service improvements | Churn by services and contract visuals |
| 3 | Data Scientist    | Predict churn for new customers          | Support early intervention     | Churn prediction dashboard             |

---

## 🛠️ Tools & Technologies

* **SQL Server** – For structured data storage and querying
* **Python (Random Forest Classifier, Pandas, Matplotlib)** – For churn model development and evaluation
* **Power BI** – For building multi-page interactive dashboards
* **ODBC** – Used for live SQL Server–Power BI connectivity

👉 Scripts and datasets are included in the `scripts/`, `notebook/`, and `data/` folders.

---

## 📊 Dashboard Structure

### **Page 1: Main Churn Dashboard**

Focused on descriptive analytics.

* **Filters**:

  * Monthly Charges (range)
  * Gender

* **KPI Cards**:

  * Total Customers
  * New Joiners
  * Total Churn
  * Churn Rate

* **Visuals**:

  * Pie Chart: Total Churn by Gender
  * Line + Stacked Column: Total Customers & Churn Rate by Age Group
  * Clustered Bar: Churn Rate by State
  * Clustered Bar: Churn Rate by Internet Type
  * Clustered Bar: Churn Rate by Payment Method
  * Clustered Bar: Churn Rate by Contract Type
  * Line + Stacked Column: Total Customers & Churn Rate by Tenure Group
  * Clustered Bar: Total Churn by Category
  * Matrix: Churn by Services (`Yes`/`No` status)

### **Page 2: Tooltip – Churn by Reason**

* Tooltip chart: Total Churn by Churn Reason
* Triggered when hovering over churn categories in Page 1

### **Page 3: Churn Prediction Dashboard**

* Visualizes churn predictions for joined customers (based on historical patterns)
* Displays demographic and service characteristics of high-risk customers
* Supports targeted outreach planning

---

## 🔍 Key Insights

* 🔻 **Churn Rate**: \~26.99% overall
* 📶 **Monthly Contracts** lead to highest churn
* 🧾 **Add-on Services** like Online Backup and Device Protection impact churn
* 🎯 **Model Accuracy**: \~82% using Random Forest Classifier, with strong recall for churned customers

---

## ✅ Recommendations

* Push long-term contracts with bundled services
* Monitor customers in first 6 months for churn indicators
* Prioritize states and payment methods with higher churn rates
* Integrate churn scores into CRM for early alerts

---

## 🧠 Project Takeaways

* Developed a **Random Forest churn prediction model** using Scikit-learn
* Visualized complex customer behavior and KPIs with Power BI
* Queried and transformed structured telecom data using SQL
* Built a live, multi-page dashboard with filters and tooltips
* Practiced data storytelling to present actionable insights

---

## 👨‍💻 About Me

I'm **Rajendra Singh Shah**, a Computer Science graduate with 1+ year of experience in data analytics. This project showcases my ability to combine SQL, Power BI, and Python-based machine learning to solve real-world business challenges.

---

## 🌐 Connect with Me

* **Portfolio**: [rajendrasinghshah.github.io](https://rajendrasinghshah.github.io)
* **LinkedIn**: [linkedin.com/in/rajendrasinghshah](https://linkedin.com/in/rajendrasinghshah)
* **Email**: [rajendrasinghshah25@gmail.com](mailto:rajendrasinghshah25@gmail.com)

---

## 📎 Project Deliverables

✔️ Power BI Dashboard (3 pages)
✔️ Python scripts using Random Forest for churn prediction
✔️ SQL scripts for data extraction
✔️ Cleaned datasets and model outputs

---

