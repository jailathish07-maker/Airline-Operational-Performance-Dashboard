✈️ Operational Performance Analysis – Power BI Dashboard
📌 Project Overview

The Operational Performance Analysis Dashboard is an interactive Power BI dashboard designed to monitor and analyze airline operational performance.

It provides insights into flight delays, cancellations, diversions, On-Time Performance (OTP), and network delay contributions. Users can explore operational data through dynamic KPIs, visualizations, and interactive filters.

🎯 Project Objectives
Monitor airline operational performance and On-Time Performance (OTP).
Analyze flight delays across different airlines.
Identify airports with the highest total delay minutes.
Track operated flights and OTP trends over time.
Understand the major contributors to network delays.
Evaluate operational stability using performance thresholds.
📊 Dashboard Preview

!Operational Performance Analysis Dashboard

📈 Key Performance Indicators (KPIs)

The dashboard dynamically calculates and displays the following metrics:

KPI	Description
On-Time Performance (OTP)	Percentage of flights arriving on time
Delay Rate	Percentage of delayed flights
Diversion Rate	Percentage of diverted flights
Cancellation Rate	Percentage of cancelled flights
Total Delay Minutes	Total accumulated flight delay minutes
Average Delay	Average flight delay duration
Operated Flights	Total number of operated flights

Note: All KPI values are dynamic and may change based on selected filters, reporting periods, and underlying data.

📉 Dashboard Visualizations
1. Operational Disruptions by Airline
Analyzes operational disruptions across different airlines.
Identifies airlines with higher disruption volumes.
Supports airline performance comparisons.
2. Operated Flights and Rolling 12-Month OTP
Displays monthly operated flight volumes.
Tracks On-Time Performance trends.
Compares flight activity with OTP over time.
3. Total Delay Minutes by Airport
Highlights airports with the highest accumulated delay minutes.
Helps identify airports experiencing significant operational delays.
4. Network Delay Impact Contribution
Visualizes the contribution of different delay categories:
Late Aircraft
Carrier
NAS
Weather
Security
5. Network Delay Driver Breakdown
Provides a detailed breakdown of network delay drivers.
Displays delay contribution percentages and delay minutes.
Helps identify the major sources of operational delays.
🚦 Operational Status Thresholds

The dashboard categorizes operational performance into three levels:

Operational Status	OTP Threshold
🔴 Critical Operations	OTP < 75%
🟠 Operational Pressure	OTP < 84%
🟢 Stable Operations	OTP ≥ 85%
🎛️ Interactive Filters

The dashboard includes interactive filters for customized analysis:

Top Performer: Dynamically adjusts the number of top-performing records displayed.
Year Month: Filters the dashboard according to the selected reporting month.

All connected KPI cards, charts, and tables update based on the applied selections.

🛠️ Tools & Technologies
Microsoft Power BI – Dashboard development and data visualization.
Power Query – Data transformation and preparation.
DAX – Dynamic KPI calculations and analytical measures.
Data Visualization – Interactive charts, KPI cards, and performance indicators.
💡 Key Analytical Capabilities
Monitor airline operational performance.
Identify trends in flight delays and cancellations.
Compare airline and airport performance.
Analyze network delay contributors.
Track monthly operational performance.
Support data-driven operational decision-making.

All analytical results depend on the selected filters and available dataset. Dashboard values are not fixed.

📂 Project Structure
text
Operational-Performance-Analysis/
│
├── README.md
├── dashboard.png
└── Operational_Performance_Analysis.pbix

🚀 How to Use
Clone or download this repository.
Open the .pbix file using Microsoft Power BI Desktop.
Explore the interactive dashboard.
Apply the available filters to customize your analysis.
Monitor the dynamically updated KPIs and visualizations.
👨‍💻 Project Purpose

This project demonstrates the use of business intelligence, data analytics, and visualization techniques to transform airline operational data into actionable insights.

It showcases the capabilities of Microsoft Power BI in developing interactive dashboards for operational monitoring, performance evaluation, and data-driven decision-making.

⭐ If you find this project interesting, feel free to star the repository!
