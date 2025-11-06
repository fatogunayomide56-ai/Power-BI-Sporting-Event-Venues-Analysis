# Power-BI-Sporting-Event-Venues-Analysis
This project explores sporting event data and venue performance using Excel, Power BI, and R integration. It demonstrates advanced skills in data modeling, DAX, Power Query transformations, and R visualization, highlighting the relationship between venue utilization, energy costs, and CO₂ emissions.

# Project Overview

The dataset consists of two sheets:

Event Data: Sporting events, their venues, attendance, temperature, and energy usage.

Venue Data: Detailed information about each sporting venue (capacity, region, and age).

The goal of this project was to model the data, perform calculated column operations, and visualize utilization and emissions insights through a multi-page Power BI report.

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

# Skills Demonstrated

Data modeling in Excel Power Pivot

Integration between Excel and Power BI

Data cleaning and transformation using Power Query

Calculated columns using DAX and RELATED()

R scripting inside Power BI for advanced analytics

Report design and visualization best practices
