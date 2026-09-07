# 🏥 Healthcare ER Analytics Dashboard | Power BI

<p align="center">
  <img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/HealthCare%20ER%20Analytics%20Banner.png">
</p>

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-success)
![Healthcare Analytics](https://img.shields.io/badge/Domain-Healthcare-red)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

</p>

---

# 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Overview](#-dataset-overview)
- [Dashboard Preview](#-dashboard-preview)
- [Tools & Technologies](#-tools--technologies)

---

# 📌 Project Overview

Emergency Rooms (ERs) operate in a fast-paced environment where thousands of patient visits, admissions, referrals, and treatment decisions occur over time. Transforming this operational data into meaningful insights is essential for improving hospital efficiency, reducing patient waiting times, and enhancing the overall patient experience.

This project presents an **interactive Healthcare ER Analytics Dashboard** developed in **Microsoft Power BI** to analyze Emergency Room performance using patient-level data. The dashboard consolidates key operational metrics—including patient volume, admission rates, waiting times, satisfaction scores, referral patterns, demographic distribution, and service-level performance—into a single reporting solution.

Designed for hospital administrators, healthcare managers, and operational teams, the dashboard enables users to monitor emergency department performance, identify bottlenecks, evaluate patient flow, and support data-driven decision-making through interactive visualizations and dynamic filtering.

---

# 🚨 Business Problem

Hospital Emergency Departments often face several operational challenges that directly impact patient care and resource utilization.

Some of the most common challenges include:

- Long patient waiting times
- Increasing patient volumes
- Uneven departmental workload
- Low patient satisfaction
- Limited visibility into admission trends
- Difficulty identifying peak operating hours
- Inefficient allocation of medical staff and hospital resources

Without an integrated analytical solution, hospital administrators must rely on multiple reports, making it difficult to identify performance issues and respond proactively.

This dashboard addresses these challenges by providing a centralized, interactive reporting solution that enables stakeholders to monitor emergency department performance, analyze patient trends, and make informed operational decisions based on real-time insights.

---

# 🎯 Project Objectives

The primary objective of this project is to transform raw Emergency Room data into an interactive Business Intelligence solution that supports operational and strategic decision-making.

The dashboard aims to:

- Analyze overall Emergency Room patient volume.
- Monitor patient admission and non-admission rates.
- Track average patient waiting times.
- Evaluate Emergency Room service-level performance.
- Measure patient satisfaction scores.
- Identify peak patient arrival hours and weekdays.
- Analyze patient demographics including age, gender, and race.
- Evaluate department referral distribution.
- Monitor monthly Emergency Room performance trends.
- Provide detailed patient-level information through interactive reporting.
- Support hospital management with data-driven operational insights.

---

# 📂 Dataset Overview

The dashboard is built using a healthcare Emergency Room dataset containing patient-level operational records collected between **April 2023 and October 2024**. :contentReference[oaicite:0]{index=0}

### Dataset Summary

| Attribute | Details |
|------------|---------|
| **Domain** | Healthcare |
| **Department** | Emergency Room (ER) |
| **Time Period** | April 2023 – October 2024 |
| **Total Patients** | 9,216 |
| **Dashboard Pages** | 4 Interactive Pages |
| **Visualization Tool** | Microsoft Power BI |

The dataset contains information related to:

- Patient ID
- Patient Name
- Gender
- Age
- Race
- Admission Date
- Admission Status
- Wait Time
- Satisfaction Score
- Department Referral
- Target Status
- Administrative Flag
- Hour of Visit
- Date Attributes

The dataset enables comprehensive analysis of patient demographics, Emergency Room operations, waiting time performance, admissions, referral patterns, and hospital service quality.

---

# 📊 Dashboard Preview

## Executive Dashboard

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Monthly%20View%20SS.png" width="100%">
</p>

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Consolidated%20View%20SS.png" width="100%">
</p>

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Table%20View%20SS.png" width="100%">
</p>

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Key%20Findings%20SS.png" width="100%">
</p>

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Recommendation%20SS.png" width="100%">
</p>

The Executive Dashboard provides a high-level overview of Emergency Room operations, highlighting key performance indicators, patient demographics, waiting time metrics, admission statistics, referral analysis, and patient distribution across multiple dimensions.

---

# 🛠 Tools & Technologies

| Category | Technologies |
|----------|--------------|
| Business Intelligence | Microsoft Power BI |
| Data Transformation | Power Query |
| Data Modeling | Power BI Data Model |
| Calculations | DAX (Data Analysis Expressions) |
| Visualization | Interactive Charts & KPIs |
| Data Source | CSV Dataset |
| Reporting | Interactive Multi-page Dashboard |

---

# 🧹 Data Cleaning & Preparation

Before designing the dashboard, the raw Emergency Room dataset was cleaned and transformed using **Power Query** to ensure consistency, improve data quality, and support accurate reporting.

The following data preparation steps were performed:

- Imported the raw CSV dataset into Power BI.
- Converted **Admission Date** into the correct Date data type.
- Standardized text fields for better consistency.
- Verified Patient IDs for uniqueness.
- Checked for missing and blank values.
- Created additional date-related fields for time-based analysis.
- Organized categorical fields for demographic and referral analysis.
- Prepared the dataset for efficient data modeling and visualization.

These transformations improved overall data quality and enabled reliable KPI calculations and interactive reporting.

---

# 🔄 Power Query Transformations

The following transformations were implemented using **Power Query Editor**:

| Transformation | Purpose |
|---------------|---------|
| Changed Data Types | Ensured correct formatting for numerical, categorical, and date fields |
| Renamed Columns | Improved readability and reporting consistency |
| Removed Unnecessary Columns | Reduced model complexity |
| Checked Null Values | Improved data quality |
| Created Date Attributes | Enabled monthly and yearly analysis |
| Data Validation | Ensured accurate dashboard calculations |

---

# 📊 Data Modeling

A clean and optimized data model was developed to support fast report performance and interactive filtering across multiple dashboard pages.

The model consists of:

- Fact Table containing patient-level records
- Date Dimension for time intelligence
- Relationships optimized for filtering and aggregation
- Interactive slicers connected across report pages

A dedicated **Date Table** was created using DAX to support Month, Year, Quarter, Weekday, and other time-based calculations. :contentReference[oaicite:0]{index=0}

---

# 📅 Date Table

A custom Calendar Table was created using **CALENDARAUTO()**, allowing the dashboard to perform time intelligence calculations efficiently.

Additional columns were generated including:

- Year
- Month Name
- Month Number
- Weekday
- Quarter
- Week Type (Weekday / Weekend)

This structure enables dynamic filtering and trend analysis across different time periods. :contentReference[oaicite:1]{index=1}

---

# 🧮 DAX Measures & KPIs

Several DAX measures were developed to calculate operational KPIs and improve dashboard interactivity.

## 📌 Core KPIs

- Number of Patients
- Total Admitted Patients
- Admission Rate
- Non-Admission Rate
- Average Wait Time
- Average Satisfaction Score
- Seen Within 30 Minutes
- Target Status (Within SLA vs Missed SLA)

The dashboard reports:

| KPI | Value |
|------|-------:|
| Total Patients | 9,216 |
| Total Admitted | 4,612 |
| Average Wait Time | 35.26 Minutes |
| Average Satisfaction Score | 4.99 / 10 |
| Seen Within 30 Minutes | 41% |
| Target Missed | 59% |

These KPIs provide hospital administrators with an instant overview of Emergency Room performance. :contentReference[oaicite:2]{index=2}

---

# 📈 Dashboard Features

The dashboard was designed with a strong focus on usability, interactivity, and executive reporting.

### Executive KPI Cards

- Total Patients
- Total Admitted Patients
- Average Wait Time
- Average Satisfaction Score
- Patients Seen Within 30 Minutes
- Target Status Performance

---

### Interactive Visualizations

- Patient Volume by Age Group
- Admission vs Non-Admission Analysis
- Department Referral Analysis
- Patient Distribution by Gender
- Patient Distribution by Race
- Patient Arrivals by Weekday
- Patient Arrivals by Hour
- Monthly Performance Trends

---

### Interactive Filters

Users can dynamically filter the dashboard by:

- Month
- Admission Date
- Department
- Gender

This enables detailed exploration without modifying the underlying dataset.

---

# 📄 Dashboard Pages

The report consists of four interactive pages, each designed for a different analytical purpose.

## 1️⃣ Monthly View

Provides a month-by-month overview of Emergency Room activity, enabling users to monitor patient trends, waiting times, admissions, and operational performance over time.

---

## 2️⃣ Consolidated View

Presents an executive summary of key performance indicators, demographic insights, referral patterns, and patient distribution in a single dashboard.

---

## 3️⃣ Patient Details

Displays patient-level records in a searchable table, allowing users to review individual cases, admission status, referral department, wait time, and demographic information.

---

## 4️⃣ Key Takeaways

Summarizes the most important business insights and operational recommendations derived from the dashboard analysis, helping stakeholders quickly understand performance trends and potential improvement areas. :contentReference[oaicite:3]{index=3}

---

# ✨ Key Dashboard Capabilities

- Interactive multi-page reporting
- Executive KPI monitoring
- Dynamic slicers and filters
- Time-based trend analysis
- Patient demographic analysis
- Referral department analysis
- Wait time monitoring
- Service-level performance tracking
- Patient-level drill-down reporting
- Responsive and professional dashboard design

---

# 📊 Dashboard Walkthrough

The **Healthcare ER Analytics Dashboard** consists of four interactive report pages, each designed to answer different business questions related to Emergency Room operations. Together, these pages provide hospital administrators and operational managers with a comprehensive view of patient flow, service quality, and departmental performance.

---

# 📄 Dashboard Page 1 — Monthly View

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Monthly%20View%20SS.png" width="100%">
</p>

## 🎯 Purpose

The Monthly View allows users to monitor Emergency Room performance over time. By filtering the report by month or date range, hospital managers can identify trends, seasonal patterns, and changes in patient volume or operational efficiency.

---

## 📈 Key KPIs

- Total Patients
- Total Admitted Patients
- Average Wait Time
- Average Patient Satisfaction Score
- Patients Seen Within 30 Minutes
- Admission Rate

---

## 📊 Visualizations Included

- Patient Count by Age Group
- Department Referral Distribution
- Patient Distribution by Gender
- Patient Distribution by Race
- Patient Visits by Weekday
- Patient Visits by Hour
- Admission Status Breakdown

---

## 💼 Business Value

This page helps decision-makers:

- Monitor monthly ER performance.
- Detect changes in patient demand.
- Compare operational efficiency across different periods.
- Evaluate service-level performance.
- Track waiting time trends.

---

# 📄 Dashboard Page 2 — Consolidated View

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Consolidated%20View%20SS.png" width="100%">
</p>

## 🎯 Purpose

The Consolidated View provides a complete executive summary of Emergency Room performance by combining operational KPIs, patient demographics, referral statistics, and service-level metrics into a single dashboard.

It serves as the primary reporting page for hospital executives and department managers.

---

## 📊 Executive KPIs

- Number of Patients
- Total Admitted Patients
- Average Wait Time
- Average Satisfaction Score
- Patients Seen Within 30 Minutes
- Target Status (Within SLA vs Missed SLA)

---

## 📈 Dashboard Components

### 👥 Patient Demographics

- Patient Age Groups
- Gender Distribution
- Race Distribution

---

### 🏥 Operational Metrics

- Admission Status
- Wait Time Performance
- SLA Achievement
- Hourly Patient Distribution
- Weekly Patient Distribution

---

### 🩺 Department Analysis

- Referral Department Distribution
- High-volume Referral Departments
- Department Workload

---

## 💼 Business Value

This page enables hospital leadership to:

- Monitor hospital performance from one screen.
- Identify operational bottlenecks.
- Evaluate patient demographics.
- Measure service quality.
- Improve staffing decisions.

---

# 📄 Dashboard Page 3 — Patient Details

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Table%20View%20SS.png" width="100%">
</p>

## 🎯 Purpose

The Patient Details page provides a detailed record of every Emergency Room visit, allowing users to drill down into individual patient information for operational review and reporting.

---

## 🔍 Information Available

Each patient record includes:

- Patient ID
- Full Name
- Gender
- Age
- Admission Date
- Department Referral
- Wait Time
- Patient Race
- Admission Status
- Administrative Flag

The dashboard allows users to dynamically filter the table using:

- Admission Date
- Department
- Gender

Patient-level information shown in the dashboard includes these fields. :contentReference[oaicite:0]{index=0}

---

## 💼 Business Value

This page supports:

- Individual patient lookup
- Administrative reporting
- Operational audits
- Data validation
- Patient record verification

---

# 📄 Dashboard Page 4 — Key Takeaways

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Key%20Findings%20SS.png" width="100%">
</p>

<p align="center">
<img src="https://github.com/sabbirakash/HealthCare-ER-Analytics-Power-BI-Dashboard-Project/blob/main/Images/Recommendation%20SS.png" width="100%">
</p>

## 🎯 Purpose

The Key Takeaways page summarizes the most important findings from the dashboard, allowing hospital administrators to quickly understand Emergency Room performance without exploring every visualization.

It transforms analytical results into actionable business insights and operational recommendations.

---

## 📋 Executive Summary

The dashboard highlights:

- Overall Emergency Room performance
- Patient admission trends
- Waiting time performance
- Patient satisfaction
- Referral department workload
- Demographic distribution
- Operational challenges
- Strategic recommendations

The source dashboard summarizes these metrics, including 9,216 patients, 4,612 admissions, an average wait time of 35.26 minutes, and only 41% of patients being seen within 30 minutes. :contentReference[oaicite:1]{index=1}

---

# 🎛 Interactive Dashboard Features

The dashboard includes several interactive capabilities that improve usability and allow users to perform self-service analysis.

### 📅 Date Filtering

Users can analyze Emergency Room performance across different months and custom date ranges.

---

### 🏥 Department Filtering

Department slicers allow users to evaluate referral patterns and operational performance by medical department.

---

### 👤 Gender Filtering

Users can compare operational metrics across male and female patient populations.

---

### 📊 Dynamic Cross Filtering

Selecting any visual automatically filters related charts across the report, enabling faster exploratory analysis.

---

### 📑 Multi-page Navigation

Navigation buttons allow users to move seamlessly between:

- Monthly View
- Consolidated View
- Patient Details
- Key Takeaways

---

# 🎨 Dashboard Design Highlights

The dashboard was designed following Business Intelligence best practices to maximize readability and user experience.

### Design Principles

- Clean and professional layout
- Consistent color palette
- Executive-style KPI cards
- Interactive slicers
- Minimal visual clutter
- Easy navigation between pages
- Responsive report layout
- High information density without overwhelming users

---

# ⭐ Project Highlights

- Interactive multi-page Power BI dashboard
- End-to-end healthcare operational analysis
- Executive KPI reporting
- Patient demographic analysis
- Wait time and SLA performance monitoring
- Referral department analysis
- Patient-level drill-down reporting
- Dynamic filtering across all report pages
- Business-focused storytelling with executive recommendations

---

# 💡 Business Questions Answered

This dashboard was designed to answer several key business questions that hospital administrators and Emergency Room managers face in their daily operations.

### Patient Flow

- How many patients visited the Emergency Room?
- What percentage of patients were admitted?
- What percentage of patients were discharged without admission?
- Which age groups visit the ER most frequently?
- How does patient volume change over time?

---

### Operational Performance

- What is the average patient waiting time?
- What percentage of patients were seen within the 30-minute target?
- How many patients missed the service-level agreement (SLA)?
- Which weekdays experience the highest patient traffic?
- What are the busiest hours of the day?

---

### Patient Demographics

- What is the gender distribution of ER patients?
- Which race groups visit the ER most frequently?
- Which age categories generate the highest patient volume?

---

### Department Performance

- Which departments receive the highest number of referrals?
- Which departments require additional staffing?
- How is patient demand distributed across referral departments?

---

### Service Quality

- What is the average patient satisfaction score?
- Does long waiting time appear to affect patient satisfaction?
- Which operational areas require immediate improvement?

---

# 📈 Key Business Findings

The dashboard uncovered several important operational insights regarding Emergency Room performance.

## 🏥 1. High Patient Volume

The Emergency Room handled **9,216 patient visits** between **April 2023 and October 2024**, indicating a consistently busy healthcare environment. :contentReference[oaicite:0]{index=0}

---

## ⏱️ 2. Long Patient Waiting Times

The average waiting time was **35.26 minutes**, exceeding the hospital's desired service target.

Only **41%** of patients were seen within 30 minutes, while **59%** exceeded the target wait time. :contentReference[oaicite:1]{index=1}

**Business Impact**

- Lower patient satisfaction
- Increased operational pressure
- Higher risk of overcrowding
- Potential decline in quality of care

---

## 😊 3. Patient Satisfaction Needs Improvement

The average patient satisfaction score is only **4.99 / 10**, suggesting that the current Emergency Room experience does not fully meet patient expectations. :contentReference[oaicite:2]{index=2}

Possible contributing factors include:

- Long waiting times
- High patient traffic
- Operational bottlenecks
- Resource constraints

---

## 🚑 4. Balanced Admission Rate

Approximately **50%** of patients were admitted while the remaining **50%** were discharged after treatment. :contentReference[oaicite:3]{index=3}

This balanced distribution indicates that the Emergency Room manages both critical and non-critical cases, requiring flexible staffing and efficient triage processes.

---

## 🏥 5. Referral Departments

Referral analysis shows that:

- General Practice receives the highest referral volume.
- Orthopedics is the second busiest referral department.
- Cardiology, Neurology, Gastroenterology, and Renal receive significantly fewer referrals. :contentReference[oaicite:4]{index=4}

This suggests that workload is concentrated in a small number of departments.

---

## 👨‍👩‍👧‍👦 6. Young Adults Visit the ER Most Frequently

Patients aged **20–39 years** represent the largest share of Emergency Room visits. :contentReference[oaicite:5]{index=5}

This may indicate:

- Higher accident rates
- Occupational injuries
- Lifestyle-related health conditions

---

## 👨‍⚕️ 7. Gender Distribution is Balanced

The patient population is nearly evenly distributed:

- Male — **51%**
- Female — **49%** :contentReference[oaicite:6]{index=6}

This indicates that healthcare demand is relatively balanced across genders.

---

## 📅 8. Patient Traffic Shows Predictable Patterns

The dashboard reveals consistent patient arrivals across weekdays, with **Saturday** showing the highest patient count. :contentReference[oaicite:7]{index=7}

Understanding these patterns can help optimize workforce planning and shift scheduling.

---

# 🚀 Recommendations

Based on the dashboard analysis, several operational improvements can help enhance Emergency Room performance.

## 1️⃣ Optimize Staff Scheduling

Increase staffing during peak hours and high-volume days to reduce patient waiting times and improve service efficiency.

---

## 2️⃣ Improve Triage Workflow

Introduce fast-track pathways for non-critical patients so that minor cases can be treated quickly without affecting critical care.

---

## 3️⃣ Reduce Waiting Time

Conduct workflow analysis to identify operational bottlenecks responsible for delays exceeding the 30-minute target.

---

## 4️⃣ Strengthen High-Demand Departments

Allocate additional physicians, nurses, and resources to General Practice and Orthopedics, where referral volumes are highest. :contentReference[oaicite:8]{index=8}

---

## 5️⃣ Improve Patient Experience

Implement:

- Digital queue displays
- Estimated waiting time notifications
- SMS updates
- Self-service patient check-in

These initiatives can improve communication and patient satisfaction.

---

## 6️⃣ Monitor Service-Level Agreements (SLAs)

Track the percentage of patients seen within the target waiting time on a regular basis and establish performance benchmarks for continuous improvement.

---

## 7️⃣ Build Predictive Staffing Models

Use historical patient arrival trends to forecast demand and proactively schedule healthcare staff during expected peak periods.

---

## 8️⃣ Launch Preventive Healthcare Programs

Since adults aged 20–39 account for the largest share of ER visits, community education and preventive health initiatives may help reduce avoidable Emergency Room utilization. This aligns with the report's recommendation for community outreach targeting young adults. :contentReference[oaicite:9]{index=9}

---

# 🛠 Skills Demonstrated

## Business Intelligence

- Interactive Dashboard Design
- Executive Reporting
- KPI Development
- Data Storytelling
- Business Analysis

---

## Power BI

- Power Query
- DAX
- Data Modeling
- Relationships
- Custom Measures
- Calculated Columns
- Interactive Slicers
- Multi-page Reporting

---

## Data Analysis

- Healthcare Analytics
- Operational Analysis
- Patient Flow Analysis
- Demographic Analysis
- Service-Level Monitoring
- Performance Reporting

---

## Data Visualization

- KPI Cards
- Bar Charts
- Column Charts
- Donut Charts
- Line Charts
- Tables
- Interactive Filters

---

# 📂 Repository Structure

```text
Healthcare-ER-Analytics-Dashboard/
│
├── Dashboard/
│   └── Healthcare ER Analytics Dashboard.pbix
│
├── Dataset/
│   └── Hospital ER.csv
│
├── Images/
│   ├── Healthcare ER Analytics Banner.png
│   ├── Dashboard Preview.png
│   ├── Monthly View.png
│   ├── Consolidated View.png
│   ├── Patient Details.png
│   └── Key Takeaways.png
│
├── Documents/
│   ├── Dashboard Requirements.pdf
│   ├── Dashboard Summary.pdf
│   └── DAX & KPI's.pdf
│
└── README.md
```

---

# 🎯 Future Improvements

Potential enhancements for future versions of the dashboard include:

- Real-time data integration with hospital information systems
- Predictive models for patient arrivals
- Emergency Room occupancy monitoring
- Bed availability tracking
- Physician workload analysis
- Patient revisit analysis
- Readmission rate monitoring
- Average treatment duration analysis
- Mobile-optimized dashboard layout
- Row-Level Security (RLS) for role-based access

---

# 📝 Conclusion

The **Healthcare ER Analytics Dashboard** demonstrates how Business Intelligence can transform raw healthcare data into actionable operational insights. By combining interactive visualizations, KPI monitoring, patient demographics, referral analysis, and service-level metrics, the dashboard provides hospital administrators with a comprehensive view of Emergency Room performance.

The analysis highlights opportunities to reduce patient waiting times, improve satisfaction, optimize staffing, and better allocate resources across departments. Through dynamic filtering and multi-page reporting, stakeholders can quickly explore trends, identify bottlenecks, and support data-driven decisions that enhance both operational efficiency and patient care.

---

# 👨‍💻 Author

**Sabbir Uddin Akash**

**Aspiring Data Analyst**

### Connect with me

- 💼 LinkedIn: [Sabbir Uddin Akash](https://www.linkedin.com/in/sabbirakash/)
- 💻 Portfolio: [Sabbir Uddin Akash](https://github.com/sabbirakash)

If you found this project helpful or interesting, consider giving it a ⭐ to support my work.

---
