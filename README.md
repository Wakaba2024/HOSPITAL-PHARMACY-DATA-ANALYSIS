# 🏥Hospital Patient & Pharmacy Performance Dashboard

------------------------------------------------------------------------

## 📌 Project Overview

This project analyzes patient visits, disease distribution, and pharmacy
billing performance for a hospital. The objective was to
transform fragmented departmental data into a clean, structured
analytical model and deliver actionable insights to hospital management
through an executive Power BI dashboard.

The dataset consisted of multiple hospital records, including patient
visits and pharmacy transactions. The data required cleaning, modeling,
and measure creation before meaningful insights could be derived.

The final deliverable is a one-page executive dashboard designed to
support data-driven decision-making in areas such as resource
allocation, disease monitoring, pharmacy performance tracking, and
demographic analysis.

------------------------------------------------------------------------

## 🛠 Tools and Framework

-   **Power BI Desktop** -- Data modeling, DAX calculations, and
    dashboard creation
-   **Power Query** -- Data cleaning and transformation
-   **DAX** -- KPI and analytical measure
    creation
-   **Excel Dataset** -- Source data for hospital visits and pharmacy
    transactions

### Key Technical Components

-   Data cleaning using Power Query
-   Creation of Age Groups using custom column logic
-   Star-schema relationship modeling
-   Use of measures such as:
    -   `Total Visits`
    -   `Total Pharmacy Revenue (SUM of Total_Cost)`
    -   `Average Length of Stay`
    -   `Total Drug Quantity`
-   Interactive dashboard design with slicers for:
    -   County
    -   Department
    -   Diagnosis
    -   Visit Date (Between filter)

------------------------------------------------------------------------

## 🔄 Project Methodology

### 1️⃣ Data Cleaning & Preparation

-   Standardized column names
-   Corrected data types (Date, Whole Number, Decimal)
-   Created Age Group categories
-   Ensured referential integrity across tables

### 2️⃣ Data Modeling

-   Established relationships between:
    -   Visits and Pharmacy Transactions (via Visit_ID)
    -   Visits and Departments
    -   Visits and Diagnoses
-   Implemented a star-schema design for optimized performance

### 3️⃣ Measure Creation (DAX)

Created analytical measures to answer business questions:

-   Total patient visits
-   Total pharmacy billing (SUM of Total_Cost)
-   Drug quantity consumption
-   Average length of hospital stay

### 4️⃣ Dashboard Development

Built a one-page executive dashboard featuring:

-   KPI Cards
-   Disease trends over time
-   Pharmacy billing breakdown by drug category
-   Department performance comparison
-   Age group medication consumption
-   Visit vs pharmacy billing correlation (scatter analysis)

------------------------------------------------------------------------

## 📊 Results and Key Insights

### 🔹 Disease Concentration

A small number of diagnoses account for a significant proportion of
total visits. Disease distribution varies by county, indicating
localized healthcare challenges.

### 🔹 Visit Volume vs Pharmacy Billing

Higher patient volume does not always result in proportionally higher
pharmacy billing. Revenue is driven more by treatment complexity than by
visit count alone.

### 🔹 Departmental Impact

Pharmacy billing is concentrated within a few key departments managing
medication-intensive cases. These units represent high operational and
financial impact areas.

### 🔹 Age-Driven Medication Utilization

Older patient groups consume significantly more medication compared to
younger demographics, indicating increased chronic disease burden.

### 🔹 Length of Stay Analysis

Longer hospital stays are not always associated with higher pharmacy
billing. Some diagnoses require extended monitoring rather than
intensive pharmaceutical intervention.

------------------------------------------------------------------------

## 🎯 Business Value

This dashboard enables hospital leadership to:

-   Monitor disease trends across counties
-   Identify high-burden departments
-   Forecast pharmaceutical demand
-   Improve inventory planning
-   Support strategic healthcare decisions




