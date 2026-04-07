# Bank Loan Portfolio Analysis | Power BI 

## **Project Overview**
This project provides a comprehensive data-driven analysis of a bank’s loan portfolio. By leveraging Power BI, I transformed raw financial data into an interactive dashboard to monitor key performance indicators (KPIs) and assess credit risk.

The dashboard helps stakeholders distinguish between **Performing Loans** and **Non-Performing Loans (NPL)** while tracking vital metrics like the **NPL Ratio** and **Debt-to-Income (DTI)** ratios to ensure the bank's financial stability and portfolio health.

---

## **Key Insights & KPIs**
The analysis monitors the following critical metrics:
* **Total Loan Applications:** Volume of incoming credit requests over time.
* **Total Funded Amount:** Total capital disbursed to borrowers.
* **Total Amount Received:** Assessing cash inflow from repayments (Principal + Interest).
* **Portfolio Segmentation:**
    * **Performing Loans:** Loans with 'Fully Paid' or 'Current' status (reflecting healthy assets).
    * **Non-Performing Loans (NPL):** Loans classified as 'Charged Off' or 'Defaulted' (used to calculate the NPL Ratio).
* **Financial Ratios:** Average Interest Rates and Debt-to-Income (DTI) ratios across different loan grades and regions.

---

## **Banking Domain Knowledge Applied**
To ensure the dashboard provides actionable business value, the following banking principles were integrated:
* **Risk Assessment:** Evaluating borrower creditworthiness based on historical payment behavior.
* **DTI Ratio Analysis:** Monitoring repayment capacity to mitigate potential defaults.
* **Portfolio Segmentation:** Analyzing loan performance by state, grade, and purpose to identify high-risk segments.
* **Regulatory Reporting:** Structuring data to support internal audits and compliance checks.

---

## **Technical Implementation (DAX Measures)**
I developed several custom measures to track time-intelligence and portfolio performance. Key measures include:

* **Time Intelligence:** * `MTD Loan Applications`, `MTD Funded Amount`, `MTD Total Amount Received`
    * `MoM Loan Application`, `MoM Total Funded Amount`, `MoM Total Amount Received`
    * `PMTD Total Funded Amount`, `PMTD Total Amount Received`
* **Risk & Performance:**
    * `Performing Loan Applications`, `Performing Loan Funded Amount`
    * `Non-Performing Loan Applications`, `Non-Performing Loan Funded Amount`
    * `Performing vs Non-Performing Loan` (Dynamic Comparison)
    * `Avg DTI` and `Avg Interest Rate`
* **Data Modeling:** Established a robust star schema with a dedicated `Calendar Table` for seamless time-based filtering.

---

## **Interactive Visuals**
* **Summary View:** High-level executive KPIs and overall portfolio status including NPL percentages.
* **Overview View:** Regional trends (Map) and temporal analysis (Total Funded Amount by Month, State, and Purpose).
* **Details View:** A granular grid for deep-dive investigation into individual loan records, showing Loan Purpose, Grade, and Interest Rates.
* **Dynamic Slicers:** Enabled multi-dimensional filtering by **State**, **Grade**, **Purpose**, and **Employment Length**.

---

## **Dashboard Preview**
*(Note: Upload your screenshots to a folder named 'Screenshots' in this repo to display them here)*

![Summary Page](screenshots/summary_page.png)
![Overview Page](screenshots/overview_page.png)
![Details Page](screenshots/details_page.png)

---

## **How to Explore**
1.  **Download:** Clone the repo or download the `.pbix` file.
2.  **Open:** Use Power BI Desktop to view the interactive elements.
3.  **Navigate:** Use the left-hand navigation pane to toggle between the Summary, Overview, and Details reports.

---
*Project developed as part of a technical portfolio to demonstrate proficiency in Financial Data Analytics.*
