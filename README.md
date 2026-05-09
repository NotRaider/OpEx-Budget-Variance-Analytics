# OpEx Budget Tracker: Corporate Financial Performance Dashboard

## Project Overview
This project focuses on transforming raw financial transaction data into an actionable executive dashboard. The primary goal was to provide department heads with a clear view of their **Actual Spend vs. Budgeted Allocation** to manage fiscal year burn rates effectively.

## 📱 [Live Dashboard Screenshot Here]
<img width="1502" height="864" alt="image" src="https://github.com/user-attachments/assets/427554ac-058f-4dc8-8635-5c302db1e913" />

## Technical Skills Demonstrated
* **Data Modeling:** Established a Star Schema with a dedicated Date Dimension and Departmental lookup tables to ensure efficient filtering.
* **DAX (Data Analysis Expressions):** Created custom measures for:
    * `Total Actuals` & `Total Budget`
    * `Variance` (Actuals - Budget)
    * `Monthly Burn Rate Trends`
* **Advanced Visualization:** * Implemented **Date Hierarchies** (Year > Quarter > Month) for granular time-series analysis.
    * Applied **Conditional Formatting** to highlight unfavorable budget variances in real-time.
* **UI/UX Design:** Built an intuitive, borderless interface designed for corporate executive reporting.

## Key Business Insights
* **Departmental Accountability:** identified that the **Finance** department is currently significantly over budget by $443K, triggering a red KPI alert.
* **Fiscal Seasonality:** The monthly trend analysis reveals consistent spending patterns, allowing for better future budget forecasting.

## Tools Used
* **Power BI Desktop**
* **DAX**
* **CSV Data Sources** (Standardized Financial Ledger)

## How to Use
1. Clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Use the **Dept Slicer** to filter by specific business units (Finance, HR, IT).
