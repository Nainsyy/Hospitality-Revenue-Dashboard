# Project Title – Hospitality Revenue Dashboard

## 📌 Overview

The Hospitality Revenue Analysis Dashboard is an interactive business intelligence tool designed to provide hotel and hospitality operators with a comprehensive overview of operational and financial performance. It offers detailed insights into revenue generation, room performance, booking patterns, and guest behavior—empowering data-driven decision-making for property managers and revenue analysts.

---

## 🔍 Problem Statement

In the hospitality industry, managing revenue performance across multiple properties, cities, and booking platforms is a complex challenge. Hotel operators often struggle with fragmented data sources, inconsistent performance metrics, and limited visibility into key indicators such as revenue, occupancy, RevPAR, and customer behavior.

This lack of centralized and actionable insights leads to:

Missed opportunities for optimizing pricing strategies and booking channels

Difficulty identifying underperforming properties or time periods

Inefficient forecasting and decision-making due to delayed or manual reporting

---

## 📊 Tools & Technologies Used

- SQL
- Power BI / Tableau
- Python (Pandas, NumPy, Matplotlib)
- Excel
- Git & GitHub

---

## 📁 Dataset

Used Atliq dataset from Atliq's site containing:
- Time Dimension: Weekly (W19–W31), aggregated for trend and comparative analysis

- Geographic Dimension: City-level, with property-level detail

- Platform Dimension: Bookings grouped by source/channel

- Category Dimension: Room types (Business vs Luxury) details.

---

## 🧠 Approach

1. Data Collection & Integration
- Gathered raw data
- Consolidate data into a structured format with dimensions like: Time (weekly/monthly), Geography (city, property), Room category, Platform source

2. Data Cleaning & Transformation
- Handle missing values (e.g., blank ratings or occupancy %)
- Normalize naming conventions (e.g., platform names, property IDs)
- Convert numeric fields to consistent formats
- Derive calculated metrics: RevPAR , Occupancy %, Realisation %, Cancellation %

3. Data Modeling
- Design star schema with fact and dimension tables:
- Fact Table: Bookings, revenue, ratings, cancellations
- Dimension Tables: Properties, Cities, Platforms, Time
- Establish relationships between tables to enable filtering and slicing
  
4. Dashboard Design & Development
- Tool: Power BI
- Components built: KPI cards for revenue, ADR, RevPAR, occupancy, realization; Filters by city, room type, and time; Pie chart for category-wise occupancy; Bar/line charts for trend analysis; Detailed table for property-wise comparison; Platform performance with dual-axis visuals (ADR vs realization)

---

## 📈 Key Features

1. Comprehensive KPI Overview
- Revenue, Occupancy %, ADR, RevPAR, Realisation %, DSRN shown at a glance
- Weekday vs Weekend breakdowns for deeper operational insights

2. City & Room Type Filters
- Dynamic filters allow users to drill down by city or room type
- Enables location-based performance comparisons

3. Property-Level Performance Table
- Metrics displayed for each hotel/property:
- Revenue, Total Bookings, RevPAR, Occupancy %, ADR
- Realisation %, Cancellations, Ratings
- Easily identify top-performing and underperforming properties

4. Booking Platform Analysis
- Compares Realisation % and ADR across various platforms:
- Tripper, Journey, Direct Online, Marketplaces, Others
- Helps in identifying the most profitable booking channels

5. Occupancy by Category
- Visual donut chart segmenting occupancy between Business and Luxury rooms
- Useful for tailoring pricing and promotion strategies

6. Trends Over Time
-Weekly trend line for:
- ADR, RevPAR, and Occupancy %
- Helps detect patterns and anomalies across weeks or seasonal periods

7. Clean, Visual Design
- Use of color-coded metrics for quick interpretation
- Icons and bar/line graphs make data more intuitive and engaging

8. Performance Benchmarks
- Average rating and cancellation percentage highlighted
- Benchmarks properties and platforms against key success indicators.

---

## ✅ Results

- Total Revenue: ₹1.69B
- Occupancy Rate: 57.79%
- ADR: ₹12.7K
- RevPAR: ₹7.34K
- Realisation: 70.14%
- Total Bookings: 132,939

🔝 Top Performer
- Altiq Exotica, Mumbai – ₹117M revenue, 7,251 bookings

📊 Platform Insights
- Highest Realisation: Direct Offline (70.99%)
- Highest ADR: Direct Offline & Tripper

🏨 Room Category
- Luxury Rooms: 58.12%
- Business Rooms: 41.77%

📉 Other Insights
- Avg. Cancellation: ~24.84%
- Top Ratings: 4.32 (Altiq Exotica & Palace)


---

## 📷 Screenshots

![Screenshot 2025-05-06 151530](https://github.com/user-attachments/assets/d072239d-2bd0-43bb-b1fa-4c4ae1805304)
![Screenshot 2025-05-06 151506](https://github.com/user-attachments/assets/3c1578e6-40d6-4c6a-a81a-f822e80dddc1)


---

## 📚 Learnings

- Luxury Segment Dominates: Higher occupancy (58.12%) in luxury rooms suggests a stronger preference for premium offerings.
- Direct Offline Channels Are Most Profitable: Highest realization % and ADR indicate better margins through direct bookings.
- Performance Varies Sharply by Property: Mumbai-based properties outperform others in both revenue and bookings, pointing to location advantages.
- Occupancy Needs Improvement: With occupancy at 57.79%, there’s significant room to increase utilization of sellable room nights.
- High Cancellations Affect Revenue: Nearly 25% cancellation rate highlights the need for better booking policies or incentives for confirmed stays.
- Consistent ADR & RevPAR Trends: Stable pricing and revenue per room suggest effective yield management over the weeks.
- Guest Ratings Are Strong: Multiple properties maintaining ratings above 4.2 signals good guest satisfaction

---

## 🤝 Acknowledgements

https://codebasics.io/resources/end-to-end-data-analyst-project 
