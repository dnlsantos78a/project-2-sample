# Cash Flow Dynamics & Liquidity Analytics (2025)

## 📖 Project Background

**SwiftFreight Logistics**, established in 2018, is a high-volume third-party logistics (3PL) provider facilitating global supply chain solutions via road, air, and maritime networks. 

The company processes thousands of client payment transactions monthly, covering freight invoices, duty disbursements, and service fees. While these payment "extractions" were previously used only for basic bookkeeping, they remained an underutilized asset for strategic planning. This project thoroughly analyzes and synthesizes this transactional data to uncover critical insights into the company’s liquidity and cash inflow velocity, ensuring that **SwiftFreight** can meet its operational obligations and carrier payouts with precision.

> **Note:** The data utilized in this project is synthetic (fake) and has been modified or anonymized for project purposes and to demonstrate analytical capabilities.

**Insights and recommendations are provided on the following key areas:**

* **Cash Inflow Velocity:** Evaluation of historical payment patterns, focusing on **Total Amount Received**, **Month-over-Month (MoM)** growth, and identifying high-liquidity periods.
* **Payment Cycle Granularity:** An analysis of inflow timing using **ISO Year-Week** metrics to understand exactly when capital enters the business.
* **Inflow Volatility & Seasonality:** Understanding the impact of "Peak Freight Seasons" on cash reserves, specifically identifying revenue surges in May and October.
* **Liquidity Trend Analysis:** An evaluation of weekly and monthly fluctuations to provide a baseline for short-term financial forecasting and working capital management.

---

## 📊 Dashboard Overview (Power BI)

<img width="2630" height="1516" alt="image" src="https://github.com/user-attachments/assets/90d5a2d7-eb07-42bd-88b2-19fb708c8192" />





### **Executive Insights**

#### **Monthly Inflow Trends**

<img width="2085" height="822" alt="image" src="https://github.com/user-attachments/assets/5c90a282-fc85-430a-a7e1-f322d7e90555" />

* **Peak Seasonality:** Cash inflow peaked in **October 2025** with over **$69M** in total payments received. This correlates with the global logistics "Peak Season" surge as retail clients prepare for Q4 holiday inventory demands.
* **Q1 Liquidity Contraction:** Beginning in **February 2025**, revenue saw a notable month-over-month decline of **16.11%**, hitting a localized low of **$45.9M**. This reflects the post-holiday cooling period common in the freight industry.
* **Quarterly Growth Trajectory:** Full-year 2025 performance maintained a strong upward trend, with **Q4** recording the highest quarterly volume ($180M+), securing a stable liquidity position for year-end carrier disbursements.

#### **Weekly Liquidity Micro-Trends**


<img width="2683" height="900" alt="image" src="https://github.com/user-attachments/assets/93c6208c-6038-4f12-a986-b8e360f80ac6" />


* **High-Precision Volatility:** While monthly views appear stable, **ISO Year-Week** analysis reveals significant micro-volatility. Specifically, **Week 02** recorded a massive **196.57% WoW increase**, likely due to a backlog of early-year invoice settlements.
* **Corrective Fluctuations:** Sharp weekly drops, such as the **44.67% contraction in Week 04**, highlight the "lumpy" nature of freight payments where large enterprise settlements can skew weekly liquidity.
* **Operational Agility:** The consistent "W-shaped" recovery patterns throughout the year suggest that the business requires high cash-on-hand agility to manage carrier payouts during weeks of lower-than-average inflow.

### **Strategic Recommendations**

Based on the uncovered cash flow patterns, the following strategic actions are recommended for **SwiftFreight Logistics**:

* **Optimize Working Capital during Q1:** Given the identified **16.11% liquidity contraction in February**, the treasury department should maintain a higher cash reserve ratio in January. This ensures that carrier payouts and operational overhead are covered during the seasonal post-holiday dip.
* **Incentivize Mid-Quarter Settlements:** To flatten the extreme weekly volatility seen in **ISO Week 02 (196% surge)** and **Week 04 (44% drop)**, the company should implement "Early Payment Discounts" for enterprise clients. This will encourage more consistent weekly inflows rather than lumpy, month-end settlements.
* **Capacity Scaling for Peak Months:** With the data confirming consistent revenue peaks in **May** and **October**, the operations team should secure additional carrier capacity 30–45 days in advance. This aligns logistical strength with periods of high-volume customer payments.
* **Dynamic Surcharge Modeling:** During high-velocity weeks (like those seen in Q4), SwiftFreight should evaluate the implementation of dynamic fuel or peak-season surcharges to maximize margins when market demand for freight space is at its highest.
* **Automate Exception Tracking:** The high variance in weekly WoW% suggests a need for an automated "Threshold Alert" system. Finance managers should be alerted whenever a weekly inflow deviates by more than 20% from the monthly average to investigate potential billing bottlenecks or delayed client settlements.

### **🔍 Recommendations for Future Analysis**

To further mature the **SwiftFreight** data model, the following deep-dive analyses are proposed for the next phase of the project:

* **High-Value Customer Segmentation (ABC Analysis):** Perform a Pareto analysis to identify the "Top 20%" of clients who contribute 80% of total cash inflow. This allows the finance team to prioritize relationship management and credit terms for the most liquidity-critical accounts.


* **Regional & Trade Lane Performance:** Breakdown cash inflows by geographic origin and destination. Analyzing which regions (e.g., APAC, EMEA, LATAM) generate the highest revenue per shipment will help steer sales efforts toward high-margin territories.
* **Service Line:** Categorize inflows by freight type (e.g., Air vs. Sea vs. Road) 
* **Predictive Inflow Forecasting:** Utilize the existing 2025 historical data to build a time-series forecasting model. This would allow the treasury team to anticipate future peaks and valleys with a 95% confidence interval, optimizing cash reserve planning for 2026.
---

## 🛠️ Technical Stack
* **Python (Google Colab):** Data cleaning, ETL (Extract, Transform, Load), and exploratory data analysis of raw payment extractions.
* **Power BI:** Advanced data modeling and UI/UX design for financial reporting.
* **DAX:** Implementation of Time-Intelligence measures (WoW%, MoM%, YTD).

---

## 🚀 Interactive Analysis
If the Python notebook does not render directly on GitHub, you can view the full code, data transformations, and visualizations here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dnlsantos78a/project-2-sample/blob/main/Project_1.ipynb)

---

## 📂 Repository Structure
| File | Description |
| :--- | :--- |
| `Project_1.ipynb` | Python Notebook containing the ETL process and Exploratory Data Analysis. |
| `image_b0722a.jpg` | Main Dashboard overview for 2025 Fiscal Year. |
| `image_b14486.png` | Deep-dive visualization of the Monthly Customer Cash Inflow. |
| `README.md` | Project documentation and Business Case details. |
