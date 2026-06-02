# HR-Workforce-Analytics-Dashboard
The project is fully built out as an isolated .pbix file. I structured the data modeling within Power Query using a star schema, caching the dataset directly inside the workspace so that anyone evaluating the project can open it seamlessly without having to configure local database pipelines or handle broken connection strings.
<img width="1342" height="742" alt="image" src="https://github.com/user-attachments/assets/fa80f78d-a2a4-4fb2-966b-2a693c0bc567" />

# HR Analytics & Workforce Intelligence Dashboard

## 📊 Project Overview
This enterprise-grade Power BI dashboard transforms raw, disparate human resources data into an interactive executive asset. Designed for HR leadership, the dashboard provides a macroscopic view of workforce dynamics, monitoring headcount distributions, systemic diversity ratios, department-level compensation brackets, and employee leave patterns. 

The goal of this analytical hub is to replace static spreadsheet reporting with an interactive tool that uncovers operational imbalances and drives talent retention strategies.

## 🛠️ Technical Architecture & Tools
- **Analytics Platform:** Microsoft Power BI Desktop
- **Data Modeling:** Star Schema design optimized for quick slicing and dicing (Fact tables joined with structured Dimension tables)
- **Data Transformation (ETL):** Power Query (M Engine) utilized for data cleaning, text formatting, and date-handling normalization
- **Calculations Engine:** Custom Data Analysis Expressions (DAX) used to calculate dynamic rolling averages, diversity percentages, and conditional metrics

## 📈 Core Analytical Perspectives & Features
- **Workforce Demographics:** Live monitoring of total active headcount, departmental growth, and precise gender diversity distribution.
- **Compensation Auditing:** Granular breakdown of salary structures, evaluating average pay scaling mapped directly against employee qualification tiers and tenure.
- **Operational Leave Tracking:** Identification of systemic bottlenecks and burnout risks by measuring cumulative unused leave balances across teams.
- **Interactive Filtering:** Fully synchronized cross-filtering enabling users to drill down by Department, Job Role, and Location instantly.

## 📁 How To Access and Run the Project
1. Download or clone this repository to your local machine.
2. Open Microsoft Power BI Desktop (Ensure you are on the latest version).
3. Click on File > Open and select the `HR_Dashboard.pbix` file.
4. The dataset is fully optimized and cached natively within the file—no external SQL database connections or local CSV path configurations are required to explore the full dashboard.

