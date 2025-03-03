# Hospital-Management-Data-Analysis-Project

# Project Overview
This project aims to analyze hospital data using Power BI, focusing on patient demographics, doctor performance, financial transactions, and general operational trends. 
The goal is to provide actionable insights to improve hospital management, billing efficiency, and patient care.

# Dashboards Created

1. General Dashboard

2. Patient Dashboard

3. Doctor Dashboard

4. Financial Dashboard

# Data Cleaning & Processing

To ensure high-quality analysis, the dataset was cleaned and processed using Power BI’s Power Query:

Removed Duplicates to ensure unique records.

Handled Missing Data by filling gaps in patient names, treatment costs, and payment statuses.

Standardized Categorical Data (e.g., correcting typos in gender, room types, and insurance providers).

Formatted Numeric and Date Columns for consistency.

Derived New Columns:

Total Cost = Treatment Cost + Room Charges

Insurance Type = IF(Insurance Provider is blank, "Self-Paid", "Insurance")

# Key Insights & Findings

Peak Admissions occur in monsoon months, suggesting a need for increased staffing.

ICU & Private Rooms generate the most revenue, indicating high demand for premium services.

30% of total revenue is pending payments, requiring better follow-up mechanisms.

Doctor workload is uneven, leading to some doctors handling significantly more patients than others.

Self-paid patients contribute more revenue, highlighting the importance of insurance partnerships.

# Future Enhancements

Implement predictive analytics to forecast admissions and treatment costs.

Use AI models to detect fraudulent claims and billing inconsistencies.

Automate real-time alerts for overdue payments and financial risks.

# Technologies Used

Power BI - Data visualization & dashboard creation

DAX - Advanced calculations & measures

Power Query - Data transformation & preprocessing

