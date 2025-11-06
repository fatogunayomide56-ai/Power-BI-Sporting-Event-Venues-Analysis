# Power-BI-Sporting-Event-Venues-Analysis
This project explores sporting event data and venue performance using Excel, Power BI, and R integration. It demonstrates a complete end-to-end workflow from data modeling in Excel to advanced DAX calculations and interactive Power BI dashboards, highlighting insights into venue utilization, energy efficiency, and CO₂ emissions.

# Project Overview

The dataset consists of two sheets:

Event Data: Sporting events, their venues, attendance, temperature, and energy usage.

Venue Data: Detailed information about each sporting venue (capacity, region, and age).

The analysis focuses on:

Understanding venue utilization and operational efficiency.

Analyzing energy consumption and CO₂ emissions across venues.

Developing interactive dashboards and DAX-based performance measures to evaluate patterns and correlations.

# Data Modeling Process

Loaded both Excel sheets into Power Pivot as data model tables.

Created a relationship between the tables using Venue as the common identifier.

Imported the data model into Power BI, confirming the link in Model View.

Renamed tables appropriately:

Event – sporting event data

Venue – venue details

# Reports Created
# Utilization Report

Includes:

Line Chart: Venue utilization trends over time.

Stacked Bar Charts: Breakdown of utilization by venue and region.

Data Table: Key venue information, titled “Venue Information”.

Formatting: Professional layout with clean labels and visual consistency.

Report tab renamed “Utilization”.

# CO₂ Emissions Report

This report integrates R scripting within Power BI to perform correlation analysis.

Visuals: 

 Scatter Plot:

  X-Axis: Utilization 

  Bubble Size: Electricity-related CO₂ emissions

Text Box: Contextual note describing the analysis.

Slicer: Filter by Venue Region.

R Visual: Correlation Heatmap of event and venue variables.

# Measures Report

Introduces advanced DAX measures for deeper analytical insights.

Measure Table: MyMeasures

All new measures were created and organized in a dedicated table: Attendance Per Event, CO2 per Dollar,Heater On Natural Gas Expense and Heater Off Electric Expense.

# Skills Demonstrated

Data modeling and relationship creation in Excel Power Pivot

Power Query transformations and calculated column creation

Advanced DAX measures using DIVIDE, AVERAGEX, and CALCULATE

Integration of R visuals within Power BI

Dashboard design and interactive navigation setup

Business-oriented analysis of utilization, cost efficiency, and CO₂ impact
