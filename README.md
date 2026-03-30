# Cash Flow Dynamics & Liquidity Analytics (2025)

## 📖 Project Background

**Logistics Company A**, established in 2018, is a high-volume provider of supply chain and transportation services. The company processes thousands of client payment transactions monthly, covering freight invoices, duty payments, and service fees. 

Historically, these payment records were used only for basic bookkeeping. This project analyzes this transactional data to uncover critical insights into the company’s **liquidity** and **cash inflow speed**. By understanding when and how money enters the business, **Logistics Company A** can better manage its daily expenses and payments to partners.

> **Note:** The data and the company name utilized in this project are synthetic (fake) and have been modified for project purposes to demonstrate financial analytical capabilities.

**Main Project Goals:**
* **Cash Inflow Tracking:** Monitoring total money received to identify high-liquidity periods.
* **Payment Timing:** Analyzing weekly patterns to understand exactly when capital enters the business.
* **Seasonality:** Identifying yearly peaks in cash flow, specifically the surges in May and October.
* **Working Capital Management:** Creating a baseline for short-term financial planning and cash reserve management.

---

## 📊 Dashboard Overview (Power BI)

<img width="2630" height="1516" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/90d5a2d7-eb07-42bd-88b2-19fb708c8192" />

### **Executive Insights**

#### **Monthly Cash Inflow Trends**
<img width="2085" height="822" alt="Monthly Trend" src="https://github.com/user-attachments/assets/5c90a282-fc85-430a-a7e1-f322d7e90555" />

* **Peak Periods:** Cash inflow hit an annual high in **October 2025** with over **$69M** received. This matches the busy shipping season as clients settle high-volume holiday invoices.
* **Early Year Slowdown:** In **February 2025**, the company saw a decline in money received, dropping by **16.11%** to a low of **$45.9M**. This reflects the natural "cooling off" period after the holiday rush.
* **End-of-Year Strength:** The final quarter of the year (**Q4**) recorded the highest total cash volume ($180M+), providing a strong cash position for year-end obligations.

#### **Weekly Cash Flow Details**
<img width="2683" height="900" alt="Weekly Trend" src="https://github.com/user-attachments/assets/93c6208c-6038-4f12-a986-b8e360f80ac6" />

* **Weekly Spikes:** While monthly totals look steady, the weekly data shows major swings. **Week 02** saw a massive **196.57% increase** in money received compared to the previous week, likely due to a backlog of payments being settled after New Year's.
* **Inconsistent Timing:** Sharp weekly drops, such as the **44.67% decline in Week 04**, show that cash flow can be "lumpy," meaning the business must be prepared for weeks with lower-than-average income.

---

### **Strategic Recommendations**

Based on these cash flow patterns, the following actions are recommended for **Logistics Company A**:

* **Prepare for February:** Since the data shows a **16% drop in February**, the company should keep extra cash in reserve during January to cover costs during the slow month.
* **Encourage Faster Payments:** To avoid the huge weekly swings (like the 196% spike followed by a 44% drop), the company could offer small discounts to clients who pay more consistently throughout the month.
* **Plan for Peak Demand:** Knowing that **May and October** are peak cash months, the company should prepare its operations 30 days in advance to handle the increased volume.
* **Monitor Unusual Swings:** Create an alert system for when weekly cash flow is 20% higher or lower than usual. This helps management quickly find out if a major client is late on a payment.

---

### **🔍 Future Analysis & Scalability**

* **Top Customer Analysis:** Identifying the top 20% of clients who provide the most cash to ensure their accounts are managed with high priority.
* **Regional Cash Performance:** Breaking down payments by location to see which parts of the world provide the most consistent cash flow.
* **Inflow Forecasting:** Using this 2025 data to build a prediction model for 2026, helping the finance team stay ahead of future "peaks" and "valleys."

## 🛠️ Technical Stack
* **Python (Google Colab):** Data cleaning, ETL (Extract, Transform, Load), and exploratory data analysis of raw payment extractions.
* **Power BI:** Advanced data modeling and UI/UX design for financial reporting.
* **DAX:** Implementation of Time-Intelligence measures (WoW%, MoM%, YTD).

---

## 🚀 Interactive Analysis
The full code can be viewd here. Also the data transformations, and visualizations here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dnlsantos78a/project-2-sample/blob/main/Project_1.ipynb)

---

## 📂 Repository Structure
| File | Description |
| :--- | :--- |
| `Project_1.ipynb` | Python Notebook containing the ETL process and Exploratory Data Analysis. |
| `README.md` | Project documentation and Business Case details. |
