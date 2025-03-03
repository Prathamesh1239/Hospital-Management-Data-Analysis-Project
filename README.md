# Hospital-Management-Data-Analysis-Project

Project Overview

This project aims to analyze hospital data using Power BI, focusing on patient demographics, doctor performance, financial transactions, and general operational trends. The goal is to provide actionable insights to improve hospital management, billing efficiency, and patient care.

Dashboards Created

1. General Dashboard

Hospital Admissions Trend (Line Chart)

Most Common Diagnoses (Bar Chart)

Treatment Costs by Disease (Treemap)

Revenue Over Time (Line Chart)

Satisfaction Trends (Gauge Chart)

2. Patient Dashboard

Age Group & Gender Distribution (Column & Donut Charts)

Insurance vs Non-Insurance Patients (Stacked Column Chart)

Room Type Preference (Stacked Bar Chart)

Admissions Over Time (Line Chart)

Pending Payments by Patient (Table)

3. Doctor Dashboard

Doctor-wise Revenue (Stacked Bar Chart)

Pending Payments by Doctor (Bar Chart)

Patient Satisfaction per Doctor (Gauge Chart)

Total Patients Treated per Doctor (Table)

Treatment Duration Analysis (Column Chart)

4. Financial Dashboard

Total Revenue & Pending Payments (KPI Cards)

Payment Status Breakdown (Pie Chart)

Insurance vs Self-Paid Revenue (Stacked Column Chart)

Top 5 Patients with Pending Payments (Table)

Revenue by Room Type (Bar Chart)

Data Cleaning & Processing

To ensure high-quality analysis, the dataset was cleaned and processed using Power BI’s Power Query:

Removed Duplicates to ensure unique records.

Handled Missing Data by filling gaps in patient names, treatment costs, and payment statuses.

Standardized Categorical Data (e.g., correcting typos in gender, room types, and insurance providers).

Formatted Numeric and Date Columns for consistency.

Derived New Columns:

Total Cost = Treatment Cost + Room Charges

Insurance Type = IF(Insurance Provider is blank, "Self-Paid", "Insurance")

Age Groups = 0-17, 18-35, 36-50, 51-65, 65+

Key Insights & Findings

Peak Admissions occur in monsoon months, suggesting a need for increased staffing.

ICU & Private Rooms generate the most revenue, indicating high demand for premium services.

30% of total revenue is pending payments, requiring better follow-up mechanisms.

Doctor workload is uneven, leading to some doctors handling significantly more patients than others.

Self-paid patients contribute more revenue, highlighting the importance of insurance partnerships.

How to Use This Project

Open Power BI and load the cleaned dataset.

Navigate through the dashboards to explore key insights.

Use filters (e.g., date range, doctor selection) to refine analysis.

Export visualizations for presentations or reports.

Future Enhancements

Implement predictive analytics to forecast admissions and treatment costs.

Use AI models to detect fraudulent claims and billing inconsistencies.

Automate real-time alerts for overdue payments and financial risks.

Project Contributors

[Your Name] - Data Cleaning, Dashboard Development, Insights Generation.

Technologies Used

Power BI - Data visualization & dashboard creation

DAX - Advanced calculations & measures

Power Query - Data transformation & preprocessing

