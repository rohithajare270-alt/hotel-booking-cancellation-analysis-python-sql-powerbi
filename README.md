🏨 Hotel Booking Cancellation Analysis

Analyzing booking cancellations to improve revenue, occupancy, and demand forecasting using Python, SQL, and Power BI.

📑 Table of Contents

Overview

Business Problem

Dataset

Tools & Technologies

Project Structure

Data Cleaning & Preparation

Exploratory Data Analysis (EDA)

Key Insights

Dashboard

Business Recommendations

How to Run This Project

Author

Overview

This project analyzes hotel booking data to identify key drivers of cancellations and revenue loss.
The goal is to help hotels optimize pricing, improve occupancy, and reduce demand uncertainty.

Business Problem

Hotels face high booking cancellations causing:

Revenue leakage

Poor room utilization

Unreliable demand forecasting

Dataset

118,896 booking records

32 features

Hotel Types: City & Resort Hotels

Time Period: Multi-year historical data

Tools & Technologies

Python – EDA, feature engineering

SQL – Aggregations, KPIs

Power BI – Dashboards & insights

Project Structure
README.md
hotel_bookings.csv
eda.ipynb
analysis.ipynb
final_dashboard.pbix
presentation.pptx
images/

Data Cleaning & Preparation

Removed duplicates and invalid records

Handled missing values

Standardized date and numeric fields

Created new features (Month, Year, Lead Time Group)

Exploratory Data Analysis (EDA)

Cancellation distribution analysis

City vs Resort comparison

ADR trends by season

Lead time vs cancellation behavior

Key Insights

37% cancellation rate represents major revenue risk

Long lead time significantly increases cancellation probability

City Hotels dominate total cancellations

High ADR bookings are more likely to be cancelled

Strong seasonal patterns impact bookings and pricing

Dashboard

The Power BI dashboard provides:

Cancellation & booking trends

Hotel type comparison

ADR seasonality analysis

Revenue impact KPIs

Business Recommendations

Introduce prepayment for long lead-time bookings

Offer non-refundable discounted rates

Apply dynamic pricing during peak seasons

Launch loyalty programs to increase repeat customers

How to Run This Project

Open the Jupyter notebooks in VS Code or Jupyter

Run EDA and analysis files

Open the Power BI .pbix file to view the dashboard

Author

Rohit Hajare
Data Analyst | Python | SQL | Power BI
📧 rohithajare270@gmail.com
🔗 https://www.linkedin.com/in/rohit-hajare-95052b292
