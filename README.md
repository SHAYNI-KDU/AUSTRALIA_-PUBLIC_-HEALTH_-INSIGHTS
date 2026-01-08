Western Australia Public Health Insights Dashboard 

## Project Overview

The Western Australia Public Health Insights Dashboard is an interactive analytical report that visualizes key public health trends in Western Australia. It uses Microsoft SQL Server for database management and Power BI for data visualization.

This project aims to provide data-driven insights for policymakers, healthcare providers, and researchers — helping them identify and respond to public health challenges through clear, evidence-based decision-making.


## Objectives

- Import and manage public health datasets using SQL Server

- Clean and transform raw data for analysis

- Build interactive visual dashboards using Power BI

- Identify key trends in health indicators such as birth rates, alcohol usage, cancer incidence, and injuries

- Support data-informed public health strategies


## Methodology

Data Source
Data were obtained from the Australian Government’s open data portal: 🔗 https://www.data.gov.au

Data Preparation
Imported datasets into Microsoft SQL Server

Created a new database (health1)

Cleaned data (renamed columns, set data types, replaced null values)

Imported cleaned data into Power BI

Tools Used Tool Purpose Microsoft SQL Server Data import, cleaning, and querying Power BI Visualization and dashboard design Excel Preprocessing and restructuring data 📈 Dashboard Visualizations
Total Potentially Preventable Hospitalizations (PPH)
Donut Chart showing Acute, Chronic, and Vaccine-preventable conditions

DAX functions used to calculate proportions

Highlights the major contributors to hospitalizations

-Low Birth Weight Trends
Shows birth weight trends (2010–2014) by region

Identifies disparities between metropolitan and rural areas

Recommends mobile healthcare and nutrition programs

-Risk of Alcohol Usage
Line chart visualizing alcohol-related harm rate changes

DAX-based year-over-year risk growth calculations

Provides actionable insights for awareness campaigns and policy regulation

-Cancer Incidents
Decomposition Tree showing population breakdown by cancer type

Regional and gender-based comparisons for breast, lung, prostate, and colorectal cancers

Fertility & Stillbirth Rates
Line and Clustered Column Chart

Fertility rates averaged 1.85 births/woman (2009–2014)

Consistent stillbirth rates (~0.45%) indicate effective maternal healthcare

-Injuries and Poisoning Contributions
Waterfall Chart highlighting decreases in accidents and poisoning rates

Uses DAX to calculate injury contributions dynamically

Demonstrates effectiveness of public safety policies

-Age-Standardized Birth Rates (ASBR)
Line Chart for age-specific birth rate variations

Identifies teenage pregnancy trends and socioeconomic impacts

-Consumer Health Indicators (Card Visuals)
Average daily fruit and vegetable intake

Physical activity rates

Smoking prevalence

Male-to-female ratio and total population metrics

-Slicers
Region and Year filters (2009–2014) for dynamic interactivity

## Key Insights

-Maternal health and fertility indicators show positive stability

-Alcohol-related harm fluctuates due to social and policy factors

-Cancer incidence varies by region and population density

-Injury rates have declined, showing the success of safety interventions

-Data visualization enables faster, clearer decision-making in healthcare

## Conclusion

This project demonstrates how SQL and Power BI can transform raw data into meaningful insights. By visualizing public health metrics interactively, stakeholders can:

-Identify regional health disparities

-Evaluate policy effectiveness

-Develop targeted public health strategies

-Future work includes integrating real-time data, enhancing predictive analysis, and promoting equitable resource allocation across regions.

## Group Members
