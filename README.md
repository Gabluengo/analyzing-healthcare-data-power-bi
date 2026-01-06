# Case Study: HealthStat Hospital Efficiency Dashboard
**Project Role**: Data Analyst | **Tools**: Power BI, DAX, Power Query

## 📖 Project Overview
This project is a comprehensive case study analyzing hospital efficiency across New York State. Acting as a consultant for "HealthStat", a fictitious consulting firm, the objective was to analyze a dataset of Elective Hip Replacement Surgeries to uncover insights regarding Length of Stay (LOS) and Cost per Discharge.

The goal was to identify root causes for operational inefficiencies and provide a dynamic analytical tool for stakeholders to benchmark hospital performance.

## 💼 Business Problem
In healthcare analytics, efficiency is defined as reducing costs while improving patients service (this involves equipments, supplies, and resources). The project focuses on two critical Key Performance Indicators (KPIs):

**Length of Stay (LOS)**: The total duration in days of a patient's stay. Shorter LOS generally reduces costs and increases hospital throughput.

**Average Cost per Discharge**: The total cost attributed to each stay.

Key Questions Answered:

*Which hospitals have the highest/lowest costs and LOS relative to state averages?*

*What factors (Severity of Illness, Risk of Mortality, Demographics) influence these metrics the most?*

*Is there a correlation between the volume of surgeries and efficiency?*

## 📊 Data Source & Methodology
**Dataset:** NY State hospital discharge data (1 year snapshot).

**Scope:** 26,000+ discharges, 151 hospitals.

**Subject:** Patients admitted for elective hip replacement surgery.

**Privacy:** Data is de-identified (contains no Protected Health Information/PHI).

**Workflow:**

- *Data Cleaning:* Handled in Power Query to ensure data types and categories were accurate.

- *Data Modeling:* Created relationships between the fact table (hospital_discharges) and the surgical_program_size_summary table.

- *DAX Calculations:* Created measures for Average LOS, Total Discharges, and Avg Cost per Discharge.

- *Dashboard Design:* Built a multi-page report with navigation and enhanced capabilities.

## 🖥️ Dashboard Tour
1. **Landing Page**
A clean, branded navigation hub allowing users to jump to specific analytical contexts.

2. **Length of Stay (LOS) Analysis**
This section benchmarks hospitals based on how long patients occupy beds.

*Key Influencers Visual:* Uses AI to determine what drives LOS to increase (e.g., Extreme Severity of Illness).

*Top/Bottom Performers:* Highlights the hospitals with the most significant deviations from the mean.

3. **Cost Analysis**
This page introduces the financial dimension, correlating time spent in the hospital with financial output.

*Scatter Plot:* Analyzes the relationship between Average LOS and Average Cost. Quadrants help identify outliers (High Cost/High LOS).

*Benchmarking:* Compares individual facilities against the state average ($21k).

4. **Hospital Profile**
A detailed view for specific facility managers. By selecting a hospital, the user can see:

*Gauge/Donut Charts:* Visualizing the specific hospital's performance vs. the state baseline.

*Patient Mix:* Breakdowns by Severity of Illness and Risk of Mortality.

## 🔍 Key Findings & Insights
Based on the analysis performed in this report, the following conclusions were drawn for the HealthStat team:

*State Benchmarks:* The average cost per discharge for hip replacement is $21,000, with an average LOS of 2.65 days.

*Root Cause Analysis:* The primary drivers for increased LOS and Cost are "Extreme" Severity of Illness and "Extreme" Risk of Mortality.

*Geographic Variances:* Hospitals located in New York City trended towards higher costs and longer stays compared to rural facilities.

*Patient Disposition:* Discharging patients to Skilled Nursing Facilities (rather than home) was highly correlated with extended Length of Stay.

## 🛠️ Tech Stack & Concepts Applied
This project demonstrates proficiency in the following Power BI areas:

*DAX:* Used CALCULATE, DIVIDE, AVERAGE, and ALL for complex aggregation and benchmarking.

*AI Visuals:* Implementation of the "Key Influencers" visual to perform automated root cause analysis.

*Data Visualization:* Scatter plots, dual-axis charts, and KPI cards formatted for accessibility.

*UX/UI Design:* Custom page navigation using bookmarks and buttons; distinct color palette for "HealthStat" branding.

***

📬 Contact
Name: Gabriel Luengo | LinkedIn: https://www.linkedin.com/in/gabriel-antonio-luengo-rojas-07ba26359/

(Based on the DataCamp Case Study: "Analyzing Healthcare Data in Power BI")
